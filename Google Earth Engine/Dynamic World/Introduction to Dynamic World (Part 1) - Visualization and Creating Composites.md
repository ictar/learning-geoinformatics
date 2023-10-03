原文：[Introduction to Dynamic World (Part 1) - Visualization and Creating Composites](https://developers.google.com/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1)

---

# Dynamic World 简介（第一部分）- 可视化和创建组合（Composites）


作者：[spatialthoughts](https://github.com/spatialthoughts "View the profile for spatialthoughts on GitHub") 




> Earth Engine 开发者社区提供的教程不属于 Earth Engine 官方产品文档的一部分。


*这是具有三部分的教程中的第一部分，另请参阅[第二部分](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2)和[第三部分](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3)。*

欢迎来到关于使用 Dynamic World(DW) 数据集的 Google Earth Engine 教程。该数据集包含根据 Sentinel-2 图像创建的近实时（NRT）土地利用土地覆盖（Land Use Land Cover, LULC）预测，涉及的九种 LULC 类别如下表所述。


| LULC 类别 | 描述 |
| --- | --- |
| Water | 永久性和季节性水体 |
| Trees | 包括原生林和次生林以及大型人工林 |
| Grass | 天然草原、畜牧场、公园 |
| Flooded vegetation | 红树林和其他被淹没的生态系统 |
| Crops | 包括中耕作物和水稻作物 |
| Shrub & Scrub | 由灌木组成的稀疏到茂密的开放植被 |
| Built Area | 低密度和高密度建筑物、道路和城市开放空间 |
| Bare ground | 沙漠和裸露的岩石 |
| Snow & Ice | 永久和季节性积雪 |


本教程提供了一些示例，关于如何使用 Earth Engine 加载和可视化这个具有 10m 分辨率（每个像素值都是概率）的丰富的 LULC 数据集。本教程还涵盖了计算统计数据和分析概率时间序列数据已进行变化检测的技术。


本教程分为三部分：

* 第一部分：可视化和创建组合
* 第二部分：计算区域统计数据
* 第三部分：探索时间序列

在每个部分中，代码将通过简短的代码片段和解释性文本逐渐构建。每个部分的末尾都会呈现完整的可用脚本。


## 先决条件

本教程假设您熟悉代码编辑器和 Earth Engine API。在继续之前，请确保：


* [注册 Earth Engine](https://signup.earthengine.google.com/)。一旦您的申请通过审批，您将收到一封包含额外信息的电子邮件。
* 熟悉使用 [Earth Engine 代码编辑器](https://code.earthengine.google.com/)，这是一个在 Web 浏览器中编写 Earth Engine JavaScript 代码的 IDE。[在此处](/earth-engine/guides/playground)了解有关代码编辑器的更多信息。
* 如果您不熟悉 JavaScript，请查看 [Earth Engine 的 JavaScript](/earth-engine/tutorials/tutorial_js_01) 教程。
* 如果您不熟悉 Earth Engine API，请查看[ Earth Engine API 简介](/earth-engine/tutorials/tutorial_api_01)教程。


一旦您熟悉了 JavaScript、Earth Engine API 和代码编辑器，就可以开始学习本教程啦！


## 你好，[Dynamic] World


Dynamic World (DW) 数据集是一个不断更新的图像集合，包含根据 Sentinel-2 图像创建的近实时 LULC 预测，这个预测全球一致，具有 10m 分辨率。该数据集中的图像包括十个波段：九个波段分别对应九个 DW LULC 类别的估计概率，以及一个名为“label”的类别波段，表示具有最大估计概率的类别。这些独特的属性使用户能够进行多时态分析并创建适合其需求的定制产品。


### 使用 NRT 图像集。


Dynamic World 近实时（NRT）图像集 includes LULC
predictions for Sentinel-2 L1C acquisitions from 2015-06-23 to the present
where the `CLOUDY_PIXEL_PERCENTAGE` metadata is less than 35%. The Image
Collection is continuously updated in near real-time with predictions generated
for new [Sentinel-2 L1C harmonized](/earth-engine/datasets/catalog/COPERNICUS_S2_HARMONIZED)
images as they become available in Google Earth Engine.


The [Dynamic World NRT collection](/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1)
is available at `GOOGLE/DYNAMICWORLD/V1`.
The images in this collection have names that match the individual Sentinel-2
L1C product names from which they were derived.


让我们看看如何查找并加载特定 Sentinel-2 图像的 Dynamic World 分类。

我们首先定义表示开始日期、结束日期和位置坐标的变量。在这里，我们定义了一个以美国马萨诸塞州夸宾水库为中心的点。

```
var startDate = '2021-10-15';
var endDate = '2021-10-25';
var geometry = ee.Geometry.Point([-72.28525, 42.36103]);

```

### 加载 Sentinel-2 图像

我们可以通过在 Sentinel-2 L1C 协调集合上应用筛选器来查找感兴趣的日期范围和位置的 Sentinel-2 图像。由于 Dynamic World 分类仅适用于云覆盖率 <35% 的场景，因此我们还应用了元数据过滤器。

```
var s2 = ee.ImageCollection('COPERNICUS/S2_HARMONIZED')
             .filterDate(startDate, endDate)
             .filterBounds(geometry)
             .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 35));

```

`s2` 变量中的结果集合包含与过滤器匹配的所有图像。我们可以调用 `.first()`，从集合中提取单个图像，即符合我们条件的最早的图像。获得图像后，我们将其添加到地图中以进行查看。该代码还将窗口中心设置为点位置的坐标。


```
var s2Image = ee.Image(s2.first());
var s2VisParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 3000};
Map.addLayer(s2Image, s2VisParams, 'Sentinel-2 Image');
Map.centerObject(geometry, 13);

```

![美国马萨诸塞州夸宾水库的 Sentinel-2 L1C 图像](https://developers.google.com/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1/dw01_1920.png)
  美国马萨诸塞州夸宾水库的 Sentinel-2 L1C 图像*


### 找到匹配的 Dynamic World 图像

为了在 Dynamic World 集合中找到匹配的分类图像，我们需要使用 `system:index` 属性提取产品 ID。

```
var imageId = s2Image.get('system:index');
print(imageId);
```
您将在控制台中看到打印的 Sentinel-2 产品 ID。我们可以使用相同的 id 来加载匹配的 Dynamic World 场景。下面的代码片段对 Dynamic World 集合应用过滤器并提取匹配的场景。

```
var dw = ee.ImageCollection('GOOGLE/DYNAMICWORLD/V1')
             .filter(ee.Filter.eq('system:index', imageId));
var dwImage = ee.Image(dw.first());
print(dwImage);

```
控制台将显示有关 Dynamic World 图像的信息。展开波段部分，您将看到图像包含 10 个波段。


![](https://developers.google.com/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1/dw02_1920.png)
*Dynamic World 图像信息*


### 查看分类图像

Dynamic World 图像的 `label` 波段包含根据概率最高的类别分配的每个像素的离散标签。下表描述了九个类别的分类法。


| Label | LULC 类别 | 颜色 | 描述 |
| --- | --- | --- | --- |
| 0 | Water | #419BDF | 永久性和季节性水体 |
| 1 | Trees | #397D49 | 包括原生林和次生林以及大型人工林 |
| 2 | Grass | #88B053 | 天然草原、畜牧场、公园 |
| 3 | Flooded vegetation | #7A87C6 | 红树林和其他被淹没的生态系统 |
| 4 | Crops | #E49635 | 包括中耕作物和水稻作物 |
| 5 | Shrub & Scrub | #DFC35A | 由灌木组成的稀疏到茂密的开放植被 |
| 6 | Built Area | #C4281B | 低密度和高密度建筑物、道路和城市开放空间 |
| 7 | Bare ground | #A59B8F | 沙漠和裸露的岩石 |
| 8 | Snow & Ice | #B39FE1 | 永久和季节性积雪 |

让我们使用`label` 波段可视化分类图像。

```
var classification = dwImage.select('label');
var dwVisParams = {
  min: 0,
  max: 8,
  palette: [
    '#419BDF', '#397D49', '#88B053', '#7A87C6', '#E49635', '#DFC35A',
    '#C4281B', '#A59B8F', '#B39FE1'
  ]
};

Map.addLayer(classification, dwVisParams, 'Classified Image');

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1/dw03.png)
*Visualization of the label classification*


### Create a Probability Hillshade Visualization


The label band of a Dynamic World image contains the class value with the
highest probability among the different LULC classes. Each image also
contains 9 other bands—each containing the pixel-wise probability for the
corresponding LULC class. We can use this information to create a better and
more information-rich visualization.


The technique uses a hillshade computed from a probability image containing
the value of the highest probability at each pixel (Top-1 Probability). This
probability image is then used as a pseudo-elevation image by the
`ee.Terrain.hillshade` algorithm. Higher confidence of a class membership
represents higher *elevation* and lower confidence represents lower *elevation*.
The resulting hillshade rendering contains ridges and valleys showing the
varying class confidence across the landscape—revealing features not normally
visible with discretized visualization.


To compute the hillshade, we first select all the probability bands and
compute the Top-1 probability using the `ee.Reducer.max()` reducer.



```
var probabilityBands = [
  'water', 'trees', 'grass', 'flooded_vegetation', 'crops', 'shrub_and_scrub',
  'built', 'bare', 'snow_and_ice'
];

var probabilityImage = dwImage.select(probabilityBands);

// Create the image with the highest probability value at each pixel.
var top1Probability = probabilityImage.reduce(ee.Reducer.max());

```

The pixel values in the resulting image range from 0-1. The hillshade
algorithm expects values in meters so we convert these to integer values by
multiplying them by 100. The hillshade algorithm returns an image from 0-255,
so we divide the result by 255 to get an image with pixel values from 0-1.



```
// Convert the probability values to integers.
var top1Confidence = top1Probability.multiply(100).int();

// Compute the hillshade.
var hillshade = ee.Terrain.hillshade(top1Confidence).divide(255);

```

For the last step, we colorize the hillshade by multiplying the
classification image with the hillshade.



```
// Colorize the classification image.
var rgbImage = classification.visualize(dwVisParams).divide(255);

// Colorize the hillshade.
var probabilityHillshade = rgbImage.multiply(hillshade);

var hillshadeVisParams = {min: 0, max: 0.8};
Map.addLayer(probabilityHillshade, hillshadeVisParams, 'Probability Hillshade');

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1/dw04.png)
*Probability Hillshade Visualization*


### Summary


In this section, you learnt how to find the matching LULC classification
image from the Dynamic World NRT collection using a Sentinel-2 L1C image. We
also covered two different techniques for visualizing the LULC classes: a
discrete visualization using the label band and a hillshade visualization
using the Top-1 confidence class. In the next section, we will learn how to
create annual composites for a larger region.


The full script for this section can be accessed from the link below
<https://code.earthengine.google.com/5a2d8406ed41ea177bf8e2bef34cd9e8>




| Sentinel-1C Image | Class Labels | Top-1 Confidence Hillshade |
| --- | --- | --- |
|  |  |  |


*A Sentinel-1C image along with matching Dynamic World products*


## Creating Multi-Temporal Composites


Being a continuous product, Dynamic World allows users to aggregate the NRT
collection over a longer, custom time period. For example, one can create a
monthly, seasonal or annual product from the NRT scenes collected during this
duration. In this section, you will learn how to create an annual land cover
product for a US County and export the results as a GeoTiff.


### Select a Region


For this tutorial, we will use the
[TIGER: US Census Counties 2018](/earth-engine/datasets/catalog/TIGER_2018_Counties)
dataset to extract the boundary for Dane County, Wisconsin.



```
var counties = ee.FeatureCollection('TIGER/2016/Counties');
var filtered = counties.filter(ee.Filter.eq('NAMELSAD', 'Dane County'));
var geometry = filtered.geometry();
Map.centerObject(geometry, 10);

```

### Filter the Dynamic World NRT Collection


Now we apply a date and bounds filter to select all images in the NRT
collection for the year 2020 over the selected region.



```
var startDate = '2020-01-01';
var endDate = '2021-01-01';

var dw = ee.ImageCollection('GOOGLE/DYNAMICWORLD/V1')
             .filterDate(startDate, endDate)
             .filterBounds(geometry);

```

### Create a Mode Composite


We can aggregate the estimated distribution of the LULC classes over the time
period by creating a mode composite using the highest probability label for
each NRT image. We can apply the `ee.Reducer.mode()` on the filtered collection
to select the most frequently occurring class label for each pixel during the
year. Once we have the composite image, we use `.clip()` to create an annual
landcover image for the region.



```
var classification = dw.select('label');
var dwComposite = classification.reduce(ee.Reducer.mode());

```

### Visualize the Annual Composite


As shown in the previous section, you may visualize the LULC image using the
class labels or the Top-1 hillshade. Here we add the result to the map using
the class taxonomy.



```
var dwVisParams = {
  min: 0,
  max: 8,
  palette: [
    '#419BDF', '#397D49', '#88B053', '#7A87C6', '#E49635', '#DFC35A',
    '#C4281B', '#A59B8F', '#B39FE1'
  ]
};

// Clip the composite and add it to the Map.
Map.addLayer(dwComposite.clip(geometry), dwVisParams, 'Classified Composite');

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1/composite1.png)
*Annual Composite for Dane County, WI*


### Create a Probability Hillshade Composite


As we saw in the previous section, you can use the pixel-wise probability
information contained in the 9 LULC bands to create a richer visualization by
calculating the Top-1 Probability Hillshade. We can use the same technique on
composites, but with a few adjustments.


The composite is created from a collection of images. Each image is collected
at a different time and has different pixel-wise probabilities. For our
visualization, we can create a mean composite that has the average pixel-wise
probability for each band across images captured at different times.



```
var probabilityBands = [
  'water', 'trees', 'grass', 'flooded_vegetation', 'crops', 'shrub_and_scrub',
  'built', 'bare', 'snow_and_ice'
];

// Select probability bands.
var probabilityCol = dw.select(probabilityBands);

// Create an image with the average pixel-wise probability
// of each class across the time-period.
var meanProbability = probabilityCol.reduce(ee.Reducer.mean());

```

The `meanProbability` image is a composite image with 9 bands having the
average pixel-wise probability calculated from all the source image bands. In
Earth Engine, a composite of input images will have the
[default projection](/earth-engine/guides/projections#the-default-projection),
which is WGS84 with 1-degree scale. This is not suitable for hillshade
computation. To fix this, we can set another default projection for the
composite image. For visualizing the image in the Code Editor, the
[*EPSG:3857* CRS](https://epsg.io/3857) is a good choice (Code Editor CRS is
EPSG:3857). We also set the scale of the projection to be the same as the source
images (10m).



```
var projection = ee.Projection('EPSG:3857').atScale(10);
var meanProbability = meanProbability.setDefaultProjection(projection);

```

We can now proceed and create the colorized hillshade visualization as
described in the previous section.



```
// Create the Top-1 Probability Hillshade.
var top1Probability = meanProbability.reduce(ee.Reducer.max());
var top1Confidence = top1Probability.multiply(100).int();
var hillshade = ee.Terrain.hillshade(top1Confidence).divide(255);
var rgbImage = dwComposite.visualize(dwVisParams).divide(255);
var probabilityHillshade = rgbImage.multiply(hillshade);

```

Finally, clip and add the layer to the Map.



```
var hillshadeVisParams = {min: 0, max: 0.8};
Map.addLayer(
    probabilityHillshade.clip(geometry), hillshadeVisParams,
    'Probability Hillshade');

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1/composite2.png)
*Top-1 Probability Hillshade Visualization of the Annual Composite*


### Export the Composite


We can export the resulting composite annual LULC product to download it as a
GeoTIFF. If you want to further analyze this dataset with GIS software, you
can export the raw image with the pixel values representing classes. We use
the `Export.image.toDrive()` function to create a task for exporting the
composite.


Once you run the script, switch to the Tasks tab and click Run. Upon
confirmation, the task will start running and create a GeoTIFF file in your
Google Drive in a few minutes.



```
Export.image.toDrive({
  image: dwComposite.clip(geometry),
  description: '2020_dw_composite_raw',
  region: geometry,
  scale: 10,
  maxPixels: 1e10
});

```

Alternatively, if you wish to create a map using this composite or use it as
a background map, it is advisable to export the probability hillshade
visualization. The code below creates an export task for the visualized
composite.



```
// Top-1 Probability Hillshade Composite.
var hillshadeComposite = probabilityHillshade.visualize(hillshadeVisParams);

Export.image.toDrive({
  image: hillshadeComposite.clip(geometry),
  description: '2020_dw_composite_hillshade',
  region: geometry,
  scale: 10,
  maxPixels: 1e10
});

```

Once the Export tasks finish, you can download the GeoTIFF file from your
Google Drive.




| Raw Composite | Top-1 Probability Hillshade Composite |
| --- | --- |
|  |  |


*Exported GeoTIFF Images Loaded in QGIS*


### Summary


You now know how to create temporally aggregated products from the Dynamic
World NRT collection for a region of your choice and visualize them. This
section also showed how you can download a GeoTIFF of the resulting composite
using the `Export` function.


The full script for this section can be accessed from this Code Editor link:
<https://code.earthengine.google.com/35657f5dc56c19e8d957cd729138a327>


In [Part 2](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2) of this tutorial, we will learn how to calculate and summarize statistics of a region.




---




The data described in this tutorial were produced by Google, in partnership with the World Resources Institute and National Geographic Society and are provided under a CC-BY-4.0 Attribution license.
