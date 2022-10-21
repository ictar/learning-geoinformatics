原文：[End-to-End Google Earth Engine (Full Course Material)](https://courses.spatialthoughts.com/end-to-end-gee.html)

---

# 端到端 Google Earth Engine (完整课程资料)


### 使用 Google Earth Engine 进行遥感应用的实践介绍。

#### Ujaval Gandhi


- [端到端 Google Earth Engine (完整课程资料)](#端到端-google-earth-engine-完整课程资料)
		- [使用 Google Earth Engine 进行遥感应用的实践介绍。](#使用-google-earth-engine-进行遥感应用的实践介绍)
			- [Ujaval Gandhi](#ujaval-gandhi)
- [简介](#简介)
- [设置环境](#设置环境)
	- [注册 Google Earth Engine](#注册-google-earth-engine)
	- [完成课前作业](#完成课前作业)
		- [遥感简介](#遥感简介)
		- [Google Earth Engine 简介](#google-earth-engine-简介)
		- [小测验](#小测验)
	- [获取课程资料](#获取课程资料)
- [模块 1: Earth Engine 基础](#模块-1-earth-engine-基础)
	- [01. Hello World](#01-hello-world)
		- [练习](#练习)
		- [保存你的工作](#保存你的工作)
	- [02. 使用图像集合](#02-使用图像集合)
		- [练习](#练习-1)
	- [03. 过滤图像集合](#03-过滤图像集合)
		- [练习](#练习-2)
	- [04. 基于 ImageCollection 创建拼接图像和合成图像](#04-基于-imagecollection-创建拼接图像和合成图像)
		- [练习](#练习-3)
	- [05. 使用特征集合](#05-使用特征集合)
		- [练习](#练习-4)
	- [06. 导入数据](#06-导入数据)
		- [练习](#练习-5)
	- [07. 裁剪图像](#07-裁剪图像)
		- [练习](#练习-6)
	- [08. 导出数据](#08-导出数据)
		- [练习](#练习-7)
	- [作业 1](#作业-1)
- [模块 2: Earth Engine 中级](#模块-2-earth-engine-中级)
	- [01. Earth Engine 对象](#01-earth-engine-对象)
		- [练习](#练习-8)
	- [02. 计算指标](#02-计算指标)
		- [练习](#练习-9)
	- [03. Computation on ImageCollections](#03-computation-on-imagecollections)
		- [练习](#练习-10)
	- [04. 云遮蔽（Cloud Masking）](#04-云遮蔽cloud-masking)
		- [练习](#练习-11)
	- [05. Reducers](#05-reducers)
		- [练习](#练习-12)
	- [06. Time-Series Charts](#06-time-series-charts)
		- [练习](#练习-13)
	- [作业 2](#作业-2)
- [模块 3: 有监督分类](#模块-3-有监督分类)
	- [机器学习和有监督分类简介](#机器学习和有监督分类简介)
	- [01. 有监督分类基础知识](#01-有监督分类基础知识)
		- [练习](#练习-14)
	- [02. 准确度评估](#02-准确度评估)
		- [练习](#练习-15)
	- [03. 改进分类](#03-改进分类)
		- [练习](#练习-16)
	- [04. 导出分类结果](#04-导出分类结果)
		- [练习](#练习-17)
	- [05. 计算面积](#05-计算面积)
		- [练习](#练习-18)
- [模块 4: 变化检测](#模块-4-变化检测)
	- [变化检测简介](#变化检测简介)
	- [01. 光谱指数变化](#01-光谱指数变化)
		- [练习](#练习-19)
	- [02. 光谱距离变化](#02-光谱距离变化)
		- [练习](#练习-20)
	- [03. 变化的直接分类](#03-变化的直接分类)
		- [练习](#练习-21)
	- [04. 分类后对比](#04-分类后对比)
		- [练习](#练习-22)
- [模块 5: Earth Engine 应用](#模块-5-earth-engine-应用)
	- [01. 客户端与服务器](#01-客户端与服务器)
		- [练习](#练习-23)
	- [02. 使用 UI 元素](#02-使用-ui-元素)
		- [练习](#练习-24)
	- [03. 构建和发布应用程序](#03-构建和发布应用程序)
		- [练习](#练习-25)
	- [04. 发布应用程序](#04-发布应用程序)
		- [练习](#练习-26)
	- [05. 创建一个拆分面板应用程序](#05-创建一个拆分面板应用程序)
		- [练习](#练习-27)
- [模块 6: Google Earth Engine Python API](#模块-6-google-earth-engine-python-api)
	- [GEE Python API 简介](#gee-python-api-简介)
		- [Google Colab](#google-colab)
		- [本地开发环境](#本地开发环境)
	- [01. Python API 语法](#01-python-api-语法)
			- [初始化](#初始化)
			- [变量](#变量)
			- [Earth Engine 对象](#earth-engine-对象)
			- [Line Continuation](#line-continuation)
			- [函数](#函数)
			- [函数参数](#函数参数)
			- [打印值](#打印值)
			- [内联函数](#内联函数)
		- [练习](#练习-28)
	- [02. Javascript 代码到 Python 到自动转换](#02-javascript-代码到-python-到自动转换)
		- [练习](#练习-29)
	- [03. 批量导出](#03-批量导出)
			- [创建一个 Collection](#创建一个-collection)
			- [导出所有图像](#导出所有图像)
			- [管理 Running/Waiting 任务](#管理-runningwaiting-任务)
		- [练习](#练习-30)
	- [04. 使用 Python 创建图像](#04-使用-python-创建图像)
		- [使用 geemap 创建交互式图表](#使用-geemap-创建交互式图表)
		- [使用 Matplotlib 创建图表](#使用-matplotlib-创建图表)
		- [练习](#练习-31)
	- [05. 自动下载](#05-自动下载)
- [补充](#补充)
	- [高级有监督分类技术](#高级有监督分类技术)
		- [超参数调优](#超参数调优)
		- [Post-Processing Classification Results](#post-processing-classification-results)
		- [主成分分析（PCA）](#主成分分析pca)
		- [Multi-temporal Composites for Crop Classification](#multi-temporal-composites-for-crop-classification)
		- [计算相关性](#计算相关性)
		- [Calculating Area by Class](#calculating-area-by-class)
		- [Spectral Signature Plots](#spectral-signature-plots)
		- [识别错误分类的 GCP](#识别错误分类的-gcp)
		- [图像归一化和标准化](#图像归一化和标准化)
		- [计算特征重要性](#计算特征重要性)
	- [时序平滑和间隙填充](#时序平滑和间隙填充)
		- [移动窗口平滑](#移动窗口平滑)
		- [时间插值](#时间插值)
		- [Savitzky-Golay 平滑](#savitzky-golay-平滑)
	- [用户界面模版](#用户界面模版)
		- [添加离散图例](#添加离散图例)
		- [Adding a Continous Legend](#adding-a-continous-legend)
		- [更改可视化 UI 应用程序](#更改可视化-ui-应用程序)
		- [NDVI Explorer UI 应用程序](#ndvi-explorer-ui-应用程序)
	- [代码共享和脚本模块](#代码共享和脚本模块)
		- [分享单个脚本](#分享单个脚本)
		- [分享多个脚本](#分享多个脚本)
		- [在脚本间共享代码](#在脚本间共享代码)
		- [有用的公共存储库](#有用的公共存储库)
- [指导项目](#指导项目)
	- [获取代码](#获取代码)
	- [项目 1：干旱监测](#项目-1干旱监测)
	- [项目 2：洪水测绘](#项目-2洪水测绘)
	- [项目 3：提取时间序列](#项目-3提取时间序列)
	- [项目 4：土地覆盖分析](#项目-4土地覆盖分析)
- [学习资源](#学习资源)
- [Data Credits](#data-credits)
- [License](#license)
- [引用和参考](#引用和参考)

---

![](https://courses.spatialthoughts.com/images/spatial_thoughts_logo.png)

---

# 简介

Google Earth Engine 是一个云平台，它允许我们对卫星图像进行大规模处理，以检测地球表面的变化、绘制趋势图并量化差异。本教程涵盖了 Earth Engine 的所有主题，从而为参与者提供掌握该平台以及实现遥感项目的实用技能。

[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/course_overview.png)](https://docs.google.com/presentation/d/1q8HRDTqgQEp3Hmi8IG0T7djPLTC1wRig3jXrwFTmoVE/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/1q8HRDTqgQEp3Hmi8IG0T7djPLTC1wRig3jXrwFTmoVE/edit?usp=sharing)


# 设置环境

## 注册 Google Earth Engine

如果你已经有了 Google Earth Engine 账号，那你可以跳过这一步。


访问 <https://signup.earthengine.google.com/>，然后使用您的 Google 账户注册。你也可以使用现有的 gmail 账户进行注册。通常需要 1-2 天进行批准。故而请尽快进行这一步。

确保注册过程顺利的提示：
* 使用 Google Chrome 浏览器。
* 注册 Earth Engine 时，请退出所有的 Google 账户，并且确保只登录了一个希望与 Earth Engine 关联的账户。
* 使用你所在的学校或者组织的邮箱进行注册更好。
* 通过 Google 群组授予对 Google Earth Engine 的访问权限。默认设置即可，但请确保您启用了正确的设置。
	+ 访问 [groups.google.com](http://groups.google.com/)
	+ 点击 Settings（齿轮图标）并选择 Global Settings。
	+ 确保选项“Allow group managers to add me to their groups”已选中。

## 完成课前作业

本课程需要大约 2 小时的课前准备。请观看以下视频，以便更好地了解遥感以及 Earth Engine 的工作原理。可在线观看视频，也可以使用下面的视频链接。

### 遥感简介

该视频介绍了遥感感念、术语和技术。

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/intro_to_remote_sensing.png)](https://www.youtube.com/watch?v=xAyNu9HbK8s)


* [观看视频](https://www.youtube.com/watch?v=xAyNu9HbK8s)
* [查看演示文档 ↗](https://docs.google.com/presentation/d/1opRKXIV8XSMa5h7Gqw10KXY5nW7_khfdiBmyDEcylUE/edit?usp=sharing)


### Google Earth Engine 简介

该视频通过选定的案例学习和应用，对 Google Earth Engine 进行了概述。它还介绍了 Earth Engine 的架构以及 EE 与其他传统的遥感软件的不同之处。

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/intro_to_gee.png)](https://www.youtube.com/watch?v=kpfncBHZBto)


* [观看视频](https://www.youtube.com/watch?v=kpfncBHZBto)
* [查看演示文档 ↗](https://docs.google.com/presentation/d/1RMyufK1bD7_Mj0b0Pub-CADiBsmT8LqyGMXIgem3UW4/edit?usp=sharing)


### 小测验

观看视频后，请完成以下两个测验：

1. Quiz-1 [遥感基础](https://forms.gle/BoaYhMgpjwNn3amS8).
2. Quiz-2 [Google Earth Engine 基础](https://forms.gle/pGVShApd9f6uVYR89).


## 获取课程资料

本课程资料和练习采用 Earth Engine 脚本的形式，通过代码库进行共享。

1. [点击此链接](https://code.earthengine.google.co.in/?accept_repo=users/ujavalgandhi/End-to-End-GEE)以打开 Google Earth Engine 代码编辑器，并将存储库添加到你的账户。
2. 如果成功了，那么在 *Reader* 会话的 *Scripts* 选项卡中会有一个名为 `users/ujavalgandhi/End-to-End-GEE` 的新存储库。
3. 验证你的代码编辑器是否如下所示
> 
> 如果你在 *Reader* 会话中没有看到存储库，请刷新你的浏览器页面，之后它会出现。
> 


![添加类存储库后的代码编辑器](https://courses.spatialthoughts.com/images/end_to_end_gee/repository.png)


# 模块 1: Earth Engine 基础

模块 1 旨在为您提供一些基本技能，使您能够找到项目所需的数据集、过滤数据以得到感兴趣的区域、应用基本的处理并导出结果。掌握这些技能将使您能够快速地在您的项目中使用 Earth Engine，并节省大量的数据预处理时间。


## 01. Hello World

该脚本介绍了基本的 Javascript 语法，视频涵盖了使用 Earth Engine 时需要学习的编程概念。要了解更多信息，请访问 Earth Engine 用户指南里的[用于 Earth Engine 的 JavaScript 简介](https://developers.google.com/earth-engine/tutorials/tutorial_js_01) 部分。

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/intro_to_javascript.png)](https://www.youtube.com/watch?v=RV3Sv5iogHs)

* [观看视频](https://www.youtube.com/watch?v=RV3Sv5iogHs)


*代码编辑器*是 Earth Engine Javascript API 的集成开发环境（IDE）。它提供了一种简单的方式来输入、调试、运行和管理代码。输入下面的代码并点击 *Run* 来执行这些代码，并在 *Console* 选项卡中查看输出。
> 
> 提示：在代码编辑器中，你可以使用快捷键 *Ctrl+Enter* 来运行代码
> 

![Hello World](https://courses.spatialthoughts.com/images/end_to_end_gee/hello_world.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F01b_Hello_World_(complete))


```js
print('Hello World');

// Variables
var city = 'Bengaluru';
var country = 'India';
print(city, country);

var population = 8400000;
print(population);
 
// List
var majorCities = ['Mumbai', 'Delhi', 'Chennai', 'Kolkata'];
print(majorCities);

// Dictionary
var cityData = {
 'city': city,
 'population': 8400000,
 'elevation': 930
};
print(cityData);

// Function
var greet = function(name) {
 return 'Hello ' + name;
};
print(greet('World'));

// This is a comment
```


### 练习

[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F01c_Hello_World_(exercise))

```js
// These are the 5 largest cities in the world: 
// Tokyo, Delhi, Shanghai, Mexico City, Sao Paulo

// Create a list named 'largeCities'
// The list should have names of all the above cities
// Print the list 
```

### 保存你的工作

当你修改课程存储库中的任何脚本时，你或许想要保存一份自己的副本。如果你尝试点击 *Save* 按钮，将会看到类似下面的错误信息
![](https://courses.spatialthoughts.com/images/end_to_end_gee/setup1.png)

这是因为该共享类存储库时一个*只读*存储库。你可以点击 *Yes*，从而在你自己的存储库中保存一个副本。如果这是你第一次使用 Earth Engine，系统将提示你选择 *home folder* 的名称。谨慎选择名称，因为一旦创建将无法更改。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/setup2.png)


## 02. 使用图像集合

Earth Engine 中的大部分数据集都以 `ImageCollection` 的形式提供。ImageCollection 是一个数据集，由在不同时间不同地点拍摄的图像组成 —— 通常来自同一个卫星或者数据提供者。你可以通过在 [Earth Engine 数据目录](https://developers.google.com/earth-engine/datasets)中搜索的 *ImageCollection ID* 来加载集合。搜索 *Sentinel-2 Level 1C* 数据集，你将找到它的 id `COPERNICUS/S2_SR`。访问 [Sentinel-2, Level 1C 页面](https://developers.google.com/earth-engine/datasets/catalog/COPERNICUS_S2)并查看*Explore in Earth Engine* 部分以查找加载和可视化该集合的代码片段。该代码片段是你使用此数据集的一个很好的起点。点击 **Copy Code Sample** 按钮，并将代码复制到代码编辑器中。点击 *Run*，然后你将看到地图中加载的图像贴片。


![](https://courses.spatialthoughts.com/images/end_to_end_gee/image_collection1.png)

在代码片段中，你将看到函数 `Map.setCenter()`，它将视窗设置为特定的位置和缩放级别。该函数的参数分别是 X 坐标（经度）、Y 坐标（纬度）和缩放级别。将 X 和 Y 坐标替换为你所在城市的坐标，然后点击 *Run* 以查看你所在城市的图像。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/image_collection2.png)


### 练习

[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F02c_Image_Collections_(exercise))


```js
// Find the 'Sentinel-2 Level-1C' dataset page
// https://developers.google.com/earth-engine/datasets

// Copy/page the code snippet

// Change the code to display images for your home city
```




## 03. 过滤图像集合

该图像集合包含了传感器曾收集到的所有图像。一般我们不会使用整个集合。大部分的应用程序都是使用集合中的一部分图像。我们可以使用 **filters** 来选择合适的图像。有许多类型的过滤函数，查看 `ee.Filter...` 模块以了解所有可用的过滤器。选择一个过滤器，然后使用过滤参数以运行 `filter()` 函数。

我们将学习 3 种主要类型的过滤技术。

* **按元数据过滤**: 你可以在图像元数据上应用诸如 `ee.Filter.eq()`、`ee.Filter.lt()` 这样的过滤器。你可以根据路径/行值、轨道编码、云覆盖等进行过滤。
* **按日期过滤**: 你可以使用像 `ee.Filter.date()` 这样的过滤器来选择特定日期范围内的图像。
* **按位置过滤**: 你可以使用 `ee.Filter.bounds()` 选择带有边界框、位置或者几何形状的图像子集。你还可以使用绘图工具绘制几何图形进行过滤。

应用过滤器后，你可以使用 `size()` 函数来检查有多少图像与过滤器匹配。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/filters.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F03b_Filtering_Image_Collection_(complete))


```js
var geometry = ee.Geometry.Point([77.60412933051538, 12.952912912328241])
Map.centerObject(geometry, 10)

var s2 = ee.ImageCollection("COPERNICUS/S2");

// Filter by metadata
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))

// Filter by date
var filtered = s2.filter(ee.Filter.date('2019-01-01', '2020-01-01'))

// Filter by location
var filtered = s2.filter(ee.Filter.bounds(geometry))

// Let's apply all the 3 filters together on the collection

// First apply metadata fileter
var filtered1 = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
// Apply date filter on the results
var filtered2 = filtered1.filter(
 ee.Filter.date('2019-01-01', '2020-01-01'))
// Lastly apply the location filter
var filtered3 = filtered2.filter(ee.Filter.bounds(geometry))

// Instead of applying filters one after the other, we can 'chain' them
// Use the . notation to apply all the filters together
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))
 
print(filtered.size())
```

### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F03c_Filtering_Image_Collection_(exercise))



```js
// Add one more filter in the script below to select images
// from only one of the satellites - Sentinel-2A - from the
// Sentinel-2 constellation

// Hint1: Use the 'SPACECRAFT\_NAME' property
// Hint2: Use the ee.Filter.eq() filter

var geometry = ee.Geometry.Point([77.60412933051538, 12.952912912328241])
Map.centerObject(geometry, 10)

var s2 = ee.ImageCollection("COPERNICUS/S2");

var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))
 // Remove this comment and add a filter here
 
print(filtered.size())
```

## 04. 基于 ImageCollection 创建拼接图像和合成图像

集合默认按日期排序。因此，当显示集合时，它会隐式创建一个拼接图像，最新的像素在最上面。可以在 ImageCollection 上调用 `.mosaic()`，从而从最上面的像素创建拼接图像。

我们还可以通过对堆栈中的所有像素应用选择标准来创建合成图像。这里，使用 `median()` 函数来创建一个合成图像，该合成图像的每个像素值是堆栈中所有像素的中值。

> 
> 提示：如果需要从按特定顺序排列的图像中创建一个拼接图像，可以使用 `.sort()` 函数按照某个属性对集合进行排序。
> 
> 


![Mosaic vs. Composite](https://courses.spatialthoughts.com/images/end_to_end_gee/mosaic_composite.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F04b_Mosaics_and_Composites_(complete))


```js
var geometry = ee.Geometry.Point([77.60412933051538, 12.952912912328241])
var s2 = ee.ImageCollection("COPERNICUS/S2");

var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))
 
var mosaic = filtered.mosaic() 
 
var medianComposite = filtered.median();

Map.addLayer(filtered, rgbVis, 'Filtered Collection');
Map.addLayer(mosaic, rgbVis, 'Mosaic');
Map.addLayer(medianComposite, rgbVis, 'Median Composite')
```

### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F04c_Mosaics_and_Composites_(exercise))

```js
// Create a median composite for the year 2020 and load it to the map

// Compare both the composites to see the changes in your city
```


## 05. 使用特征集合

特征集合类似于图像集合，但它们包含的是*特征*，而非图像。它们等同于 GIS 中的矢量图层。我们可以使用目前学到的类似技术来加载、过滤和展示特征集合。

搜索 *GAUL Second Level Administrative Boundaries* 并加载集合。这是一个全局集合，它包含所有所有 Admin2 边界。我们可以使用 `ADM1_NAME` 属性，应用过滤器来获取一个州的所有 Admin2 边界（即地区）。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/feature_collection.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F05b_Feature_Collections_(complete))


```js
var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");

var karnataka = admin2.filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))

var visParams = {'color': 'red'}
Map.addLayer(karnataka, visParams, 'Karnataka Districts')
```

### 练习

[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F05c_Feature_Collections_(exercise))


```js
// Apply a filter to select only the 'Bangalore Urban' district
// Display only the selected district

// Hint: The district names are in ADM2\_NAME property

var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");
var karnataka = admin2.filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))

var visParams = {'color': 'red'}
```

## 06. 导入数据

你可以将矢量数据或者栅格数据导入到 Earth Engine。现在，我们将为 Natural Earth导入一个 [Urban Areas](https://www.naturalearthdata.com/downloads/10m-cultural-vectors/10m-urban-area/) 的 shapefile。将 `ne_10m_urban_areas.zip` 解压到电脑上的一个文件夹中。在代码编辑器中，转到 *Assets → New → Table Upload → Shape Files*。选择 `.shp`, `.shx`, `.dbf` 和 .`prj` 文件。输入 `ne_10m_urban_areas` 作为 *Asset Name* 并点击 *Upload*。上传并摄取完毕后，在 *Assets* 选项卡中将出现一个新的资产。shapefile 在 Earth Engine 中作为特征集合导入。选择 `ne_10m_urban_areas` 资产并点击 *Import*。然后，你就可以查看导入的数据了。

![导入 Shapefile](https://courses.spatialthoughts.com/images/end_to_end_gee/import.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F06b_Import_(complete))



```js
// Let's import some data to Earth Engine
// Upload the ne\_10m\_urban\_areas.shp shapefile

// Import the collection
var urban = ee.FeatureCollection("users/ujavalgandhi/e2e/ne\_10m\_urban\_areas");

// Visualize the collection
Map.addLayer(urban, {color: 'blue'}, 'Urban Areas')
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F06c_Import_(exercise))

```js
// Apply a filter to select only large urban areas
// Use the property 'area\_sqkm' and select all features 
// with area > 400 sq.km

var urban = ee.FeatureCollection("users/ujavalgandhi/e2e/ne\_10m\_urban\_areas");
```

## 07. 裁剪图像

通常，我们需要将图像裁剪到所感兴趣的区域。可以使用 `clip()` 函数，利用几何图形遮盖图像。

> 
> 虽然在桌面软件中，裁剪有助于删除大图像的不必要部分并节省计算时间，但在 Earth Engine 中，裁剪实际上会增加计算时间。正如 [Earth Engine 编码最佳实践](https://developers.google.com/earth-engine/guides/best_practices?hl=en#if-you-dont-need-to-clip,-dont-use-clip) 指南中所述，请避免裁剪图像，或在脚本末尾再进行裁剪。
> 
> 

![Original vs. Clipped Image](https://courses.spatialthoughts.com/images/end_to_end_gee/clipping.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F07b_Clipping_(complete))



```js
var s2 = ee.ImageCollection("COPERNICUS/S2")
var urban = ee.FeatureCollection("users/ujavalgandhi/e2e/ne\_10m\_urban\_areas")

// Find the feature id by adding the layer to the map and using Inspector.
var filtered = urban.filter(ee.Filter.eq('system:index', '00000000000000002bf8'))

var geometry = filtered.geometry()

var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'], 
};
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

var image = filtered.median(); 

var clipped = image.clip(geometry)

Map.addLayer(clipped, rgbVis, 'Clipped')
```

### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F07c_Clipping_(exercise))

```js
// Add the imported table to the Map
// Use the Inspector to find the id of your home city or any urban area of your choice
// Change the filter to use the id of the selected feature
```

## 08. 导出数据

Earth Engine 允许我们导出矢量和栅格数据以便外部程序使用。矢量数据可以导出为 `CSV` 活着 `Shapefile`，而栅格数据可以导出为 `GeoTIFF` 文件。我们现在将 Sentinel-2 Composite 导出为 GeoTIFF 文件。

> 
> 提示：代码编辑器支持使用 *Ctrl+Space* 组合键对 API 函数自动补全。输入函数的几个字符，然后按 *Ctrl+Space* 以查看自动补全建议。你还可以使用相同的组合键来自动填充函数的所有参数。
> 

运行此脚本后， *Tasks* 选项卡将突出显示。切换到选项卡，你将看到等待中的任务。点击每个任务旁边的 *Run* 以启动处理。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/export_task01.png)

点击 *Run* 按钮后，系统将提示以便确认。检查设置并单击 *Run* 以开始导出。


![](https://courses.spatialthoughts.com/images/end_to_end_gee/export_task02.png)

一旦结束导出，每个导出任务涉及到的的 GeoTiff 文件将添加到你的 Google Drive 中的指定文件夹中。你可以下载它们并在 GIS 软件中使用。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/exporting_data.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F08b_Export_(complete))

```js
var s2 = ee.ImageCollection("COPERNICUS/S2")
var urban = ee.FeatureCollection("users/ujavalgandhi/e2e/ne\_10m\_urban\_areas")

var filtered = urban.filter(ee.Filter.eq('system:index', '00000000000000002bf8'))
var geometry = filtered.geometry()

var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'], 
};
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

var image = filtered.median(); 

var clipped = image.clip(geometry)

Map.addLayer(clipped, rgbVis, 'Clipped') 

var exportImage = clipped.select('B.\*')

Export.image.toDrive({
 image: exportImage,
 description: 'Bangalore\_Composite\_Raw',
 folder: 'earthengine',
 fileNamePrefix: 'bangalore\_composite\_raw',
 region: geometry,
 scale: 10,
 maxPixels: 1e9
})

// Rather than exporting raw bands, we can apply a rendered image
// visualize() function allows you to apply the same parameters 
// that are used in earth engine which exports a 3-band RGB image
print(clipped)
var visualized = clipped.visualize(rgbVis)
print(visualized)
// Now the 'visualized' image is RGB image, no need to give visParams
Map.addLayer(visualized, {}, 'Visualized Image') 

Export.image.toDrive({
 image: visualized,
 description: 'Bangalore\_Composite\_Visualized',
 folder: 'earthengine',
 fileNamePrefix: 'bangalore\_composite\_visualized',
 region: geometry,
 scale: 10,
 maxPixels: 1e9
})
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2F08c_Export_(exercise))

```js

// Write the export function to export the results for your chosen urban area
```


## 作业 1

加载 2019 年和 2020 年的夜灯数据（Night Lights Data）。比较你所在区域的图像并找出城市变化。

![作业1预期输出](https://courses.spatialthoughts.com/images/end_to_end_gee/assignment1.png)

[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A01-Earth-Engine-Basics%2FAssignment1)


```js
// Assignment
// Export the Night Lights images for May,2015 and May,2020

// Workflow:
// Load the VIIRS Nighttime Day/Night Band Composites collection
// Filter the collection to the date range
// Extract the 'avg\_rad' band which represents the nighttime lights
// Clip the image to the geometry of your city
// Export the resulting image as a GeoTIFF file.

// Hint1: 

// There are 2 VIIRS Nighttime Day/Night collections
// Use the one that corrects for stray light

// Hint2: 

// The collection contains 1 global image per month
// After filtering for the month, there will be only 1 image in the collection

// You can use the following technique to extract that image
// var image = ee.Image(filtered.first())
```

# 模块 2: Earth Engine 中级


Module 2 builds on the basic Earth Engine skills you have gained. This model introduces the parallel programming concepts using Map/Reduce - which is key in effectively using Earth Engine for analyzing large volumes of data. You will learn how to use the Earth Engine API for calculating various spectral indices, do cloud masking and then use map/reduce to do apply these computations to collections of imagery. You will also learn how to take long time-series of data and create charts.


[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/map_reduce.png)](https://docs.google.com/presentation/d/10qOyxhubkwnsAVjniW54ETgwUHq3DXYKo3HGb6Gemi0/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/10qOyxhubkwnsAVjniW54ETgwUHq3DXYKo3HGb6Gemi0/edit?usp=sharing)



## 01. Earth Engine 对象


This script introduces the basics of the Earth Engine API. When programming in Earth Engine, you must use the Earth Engine API so that your computations can use the Google Earth Engine servers. To learn more, visit [Earth Engine 对象和方法](https://developers.google.com/earth-engine/tutorial_js_02) section of the Earth Engine User Guide.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F01b_Earth_Engine_Objects_(complete))



```
// Let's see how to take a list of numbers and add 1 to each element
var myList = ee.List.sequence(1, 10);

// Define a function that takes a number and adds 1 to it
var myFunction = function(number) {
 return number + 1;
}
print(myFunction(1));

//Re-Define a function using Earth Engine API
var myFunction = function(number) { 
 return ee.Number(number).add(1);
}

// Map the function of the list
var newList = myList.map(myFunction);
print(newList); 

// Extracting value from a list

var value = newList.get(0)
print(value)

// Casting

// Let's try to do some computation on the extracted value
//var newValue = value.add(1)
//print(newValue)

// You get an error because Earth Engine doesn't know what is the type of 'value'
// We need to cast it to appropriate type first
var value = ee.Number(value)
var newValue = value.add(1)
print(newValue)

// Dictionary
// Convert javascript objects to EE Objects
var data = {'city': 'Bengaluru', 'population': 8400000, 'elevation': 930};
var eeData = ee.Dictionary(data);
// Once converted, you can use the methods from the
// ee.Dictionary module
print(eeData.get('city'))

// Dates
// For any date computation, you should use ee.Date module

var date = ee.Date('2019-01-01')
var futureDate = date.advance(1, 'year')
print(futureDate)
```


> 
> As a general rule, you should always use Earth Engine API methods in your code, there is one exception where you will need to use client-side Javascript method. If you want to get the current time, the server doesn’t know your time. You need to use javascript method and cast it to an Earth Engine object.
> 
> 
> 
> ```
> var now = Date.now()
> print(now)
> var now = ee.Date(now)
> print(now)
> ```
> 
> 



### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F01c_Earth_Engine_Objects_(exercise))



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var geometry = ee.Geometry.Point([77.60412933051538, 12.952912912328241]);

var now = Date.now()
var now = ee.Date(now) 
// Apply another filter to the collection below to filter images
// collected in the last 1-month
// Do not hard-code the dates, it should always show images
// from the past 1-month whenever you run the script
// Hint: Use ee.Date.advance() function
// to compute the date 1 month before now
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))
```




## 02. 计算指标


Spectral Indices are central to many aspects of remote sensing. Whether you are studying vegetation or tracking fires - you will need to compute a pixel-wise ratio of 2 or more bands. The most commonly used formula for calculating an index is the *Normalized Difference* between 2 bands. Earth Engine provides a helper function `normalizedDifference()` to help calculate normalized indices, such as Normalized Difference Vegetation Index (NDVI). For more complex formulae, you can also use the `expression()` function to describe the calculation.



![MNDWI, SAVI 和 NDVI 图像](https://courses.spatialthoughts.com/images/end_to_end_gee/indices.png)

MNDWI, SAVI and NDVI images




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F02b_Calculating_Indices_(complete))



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");

var bangalore = admin2.filter(ee.Filter.eq('ADM2\_NAME', 'Bangalore Urban'))
var geometry = bangalore.geometry()

var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

var image = filtered.median(); 

// Calculate Normalized Difference Vegetation Index (NDVI)
// 'NIR' (B8) and 'RED' (B4)
var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);

// Calculate Modified Normalized Difference Water Index (MNDWI)
// 'GREEN' (B3) and 'SWIR1' (B11)
var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 

// Calculate Soil-adjusted Vegetation Index (SAVI)
// 1.5 \* ((NIR - RED) / (NIR + RED + 0.5))

// For more complex indices, you can use the expression() function

// Note: 
// For the SAVI formula, the pixel values need to converted to reflectances
// Multiplyng the pixel values by 'scale' gives us the reflectance value
// The scale value is 0.0001 for Sentinel-2 dataset

var savi = image.expression(
 '1.5 \* ((NIR - RED) / (NIR + RED + 0.5))', {
 'NIR': image.select('B8').multiply(0.0001),
 'RED': image.select('B4').multiply(0.0001),
}).rename('savi');

var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};
var ndviVis = {min:0, max:1, palette: ['white', 'green']}
var ndwiVis = {min:0, max:0.5, palette: ['white', 'blue']}

Map.addLayer(image.clip(geometry), rgbVis, 'Image');
Map.addLayer(mndwi.clip(geometry), ndwiVis, 'mndwi')
Map.addLayer(savi.clip(geometry), ndviVis, 'savi') 
Map.addLayer(ndvi.clip(geometry), ndviVis, 'ndvi')
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F02c_Calculating_Indices_(exercise))



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");

var bangalore = admin2.filter(ee.Filter.eq('ADM2\_NAME', 'Bangalore Urban'))
var geometry = bangalore.geometry()
Map.centerObject(geometry)

var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

var image = filtered.median(); 

// Exercise

// Calculate the Normalized Difference Built-Up Index (NDBI) for the image
// Hint: NDBI = (SWIR1 – NIR) / (SWIR1 + NIR)
// Visualize the built-up area using a 'red' palette
```




## 03. Computation on ImageCollections


So far we have learnt how to run computation on single images. If you want to apply some computation - such as calculating an index - to many images, you need to use `map()`. You first define a function that takes 1 image and returns the result of the computation on that image. Then you can `map()` that function over the ImageCollection which results in a new ImageCollection with the results of the computation. This is similar to a *for-loop* that you maybe familiar with - but using `map()` allows the computation to run in parallel. Learn more at [Mapping over an ImageCollection](https://developers.google.com/earth-engine/guides/ic_mapping)



![NDVI computation on an ImageCollection](https://courses.spatialthoughts.com/images/end_to_end_gee/imagecollection_computation.png)

NDVI computation on an ImageCollection




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F03b_Computation_on_Image_Collections_(complete))



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var admin1 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level1");
 
var karnataka = admin1.filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))
var geometry = karnataka.geometry()
var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};

var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

var composite = filtered.median().clip(geometry)
Map.addLayer(composite, rgbVis, 'Karnataka Composite') 


// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

// Map the function over the collection
var withNdvi = filtered.map(addNDVI);

var composite = withNdvi.median()

var ndviComposite = composite.select('ndvi').clip(karnataka)

var palette = [
 'FFFFFF', 'CE7E45', 'DF923D', 'F1B555', 'FCD163', '99B718',
 '74A901', '66A000', '529400', '3E8601', '207401', '056201',
 '004C00', '023B01', '012E01', '011D01', '011301'];

var ndviVis = {min:0, max:0.5, palette: palette }
Map.addLayer(ndviComposite, ndviVis, 'ndvi')
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F03c_Computation_on_Image_Collections_(exercise))



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var admin1 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level1");
 
var karnataka = admin1.filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))
var geometry = karnataka.geometry()
var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};

var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

 
var composite = filtered.median().clip(geometry)
Map.addLayer(composite, rgbVis, 'Karnataka Composite') 

// This function calculates both NDVI an d NDWI indices
// and returns an image with 2 new bands added to the original image.
function addIndices(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 var ndwi = image.normalizedDifference(['B3', 'B8']).rename('ndwi');
 return image.addBands(ndvi).addBands(ndwi);
}

// Map the function over the collection
var withIndices = filtered.map(addIndices);

// Composite
var composite = withIndices.median()
print(composite)

// Extract the 'ndwi' band and display a NDWI map
// use the palette ['white', 'blue']
// Hint: Use .select() function to select a band
```




## 04. 云遮蔽（Cloud Masking）


Masking pixels in an image makes those pixels transparent and excludes them from analysis and visualization. To mask an image, we can use the `updateMask()` function and pass it an image with 0 and 1 values. All pixels where the mask image is 0 will be masked.


Most remote sensing datasets come with a QA or Cloud Mask band that contains the information on whether pixels is cloudy or not. Your *Code Editor* contains pre-defined functions for masking clouds for popular datasets under *Scripts Tab → Examples → Cloud Masking*.


The script below takes the Sentinel-2 masking function and shows how to apply it on an image.



![Applying pixel-wise QA bitmask](https://courses.spatialthoughts.com/images/end_to_end_gee/cloud_masking.png)

Applying pixel-wise QA bitmask




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F04b_Cloud_Masking_(complete))



```
var image = ee.Image('COPERNICUS/S2/20190703T050701\_20190703T052312\_T43PGP')
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};

Map.centerObject(image)
Map.addLayer(image, rgbVis, 'Full Image', false)

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}

var maskedImage = ee.Image(maskS2clouds(image))
Map.addLayer(maskedImage, rgbVis, 'Masked Image')
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F04c_Cloud_Masking_(exercise))



```
// Get the Level-2A Surface Reflectance image
var imageSR = ee.Image('COPERNICUS/S2\_SR/20190703T050701\_20190703T052312\_T43PGP')
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
Map.centerObject(imageSR)
Map.addLayer(imageSR, rgbVis, 'SR Image')


// Function to remove cloud and snow pixels from Sentinel-2 SR image
function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(5);
 var snow = snowProb.lt(5);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 5% or cloud shadow classification
 var mask = (cloud.and(snow)).and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask);
}

// Exercise
// Apply the above cloud masking function to SR image
// Add the masked image to the map

// Hint: After adding the masked image to the map, turn-off
// the original image layer to see the result of the masking function
```


> 
> If you are using Sentinel-2 data, do check out the an alternative cloud masking techninque using the *S2 Cloudless* dataset. [Learn more](https://medium.com/google-earth/more-accurate-and-flexible-cloud-masking-for-sentinel-2-images-766897a9ba5f)
> 
> 
> 
> ```
> var imageSR = ee.Image('COPERNICUS/S2_SR/20190703T050701_20190703T052312_T43PGP')
> var s2Cloudless = ee.Image('COPERNICUS/S2_CLOUD_PROBABILITY/20190703T050701_20190703T052312_T43PGP')
> var clouds = s2Cloudless.lt(50)
> var cloudlessMasked = imageSR.mask(clouds)
> var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};
> Map.addLayer(cloudlessMasked, rgbVis, 'S2 Cloudless Masked Image')
> ```
> 
> 





## 05. Reducers


When writing parallel computing code, a *Reduce* operation allows you to compute statistics on a large amount of inputs. In Earth Engine, you need to run reduction operation when creating composites, calculating statistics, doing regression analysis etc. The Earth Engine API comes with a large number of built-in reducer functions (such as `ee.Reducer.sum()`, `ee.Reducer.histogram()`, `ee.Reducer.linearFit()` etc.) that can perform a variety of statistical operations on input data. You can run reducers using the `reduce()` function. Earth Engine supports running reducers on all data structures that can hold multiple values, such as Images (reducers run on different bands), ImageCollection, FeatureCollection, List, Dictionary etc. The script below introduces basic concepts related to reducers.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F05b_Reducers_(complete))



```
// Computing stats on a list
var myList = ee.List.sequence(1, 10);
print(myList)

// Use a reducer to compute min and max in the list
var mean = myList.reduce(ee.Reducer.mean());
print(mean);

var geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]]);
var s2 = ee.ImageCollection("COPERNICUS/S2");
Map.centerObject(geometry)

// Apply a reducer on a image collection
var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))
 .select('B.\*')

print(filtered.size())
var collMean = filtered.reduce(ee.Reducer.mean());
print('Reducer on Collection', collMean);

var image = ee.Image('COPERNICUS/S2/20190223T050811\_20190223T051829\_T44RPR')
var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};
Map.addLayer(image, rgbVis, 'Image')
Map.addLayer(geometry, {color: 'red'}, 'Farm')
// If we want to compute the average value in each band,
// we can use reduceRegion instead
var stats = image.reduceRegion({
 reducer: ee.Reducer.mean(),
 geometry: geometry,
 scale: 100,
 maxPixels: 1e10
 })
print(stats);

// Result of reduceRegion is a dictionary. 
// We can extract the values using .get() function
print('Average value in B4', stats.get('B4'))
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F05c_Reducers_(exercise))



```
var geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]]);
 
var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};
var image = ee.Image('COPERNICUS/S2/20190223T050811\_20190223T051829\_T44RPR')
Map.addLayer(image, rgbVis, 'Image')
Map.addLayer(geometry, {color: 'red'}, 'Farm')
Map.centerObject(geometry)

var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');

// Exercise
// Compute the average NDVI for the farm from the given image
// Hint: Use the reduceRegion() function
```




## 06. Time-Series Charts


Now we can put together all the skills we have learnt so far - filter, map, reduce, and cloud-masking to create a chart of average NDVI values for a given farm over 1 year. Earth Engine API comes with support for charting functions based on the Google Chart API. Here we use the `ui.Chart.image.series()` function to create a time-series chart.



![Computing NDVI Time-series for a Farm](https://courses.spatialthoughts.com/images/end_to_end_gee/charts1.png)

Computing NDVI Time-series for a Farm





![NDVI Time-series showing Dual-Cropping Cycle](https://courses.spatialthoughts.com/images/end_to_end_gee/charts2.png)

NDVI Time-series showing Dual-Cropping Cycle




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F06b_Time_Series_Charts_(complete))



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]]);
Map.addLayer(geometry, {color: 'red'}, 'Farm')
Map.centerObject(geometry)
var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};

var filtered = s2
 .filter(ee.Filter.date('2017-01-01', '2018-01-01'))
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}

var filtered = filtered.map(maskS2clouds)
// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

// Map the function over the collection
var withNdvi = filtered.map(addNDVI);


// Display a time-series chart
var chart = ui.Chart.image.series({
 imageCollection: withNdvi.select('ndvi'),
 region: geometry,
 reducer: ee.Reducer.mean(),
 scale: 10
}).setOptions({
 lineWidth: 1,
 title: 'NDVI Time Series',
 interpolateNulls: true,
 vAxis: {title: 'NDVI'},
 hAxis: {title: '', format: 'YYYY-MMM'}
 })
print(chart);
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F06c_Time_Series_Charts_(exercise))



```
// Delete the farm boundary from the previous script 
// and add another farm at a location of your choice

// Print the chart.
```




## 作业 2



![Assignment2 Expected Output](https://courses.spatialthoughts.com/images/end_to_end_gee/assignment2.png)

Assignment2 Expected Output




[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2FAssignment2)



```
var terraclimate = ee.ImageCollection("IDAHO\_EPSCOR/TERRACLIMATE");
var geometry = ee.Geometry.Point([77.54849920033682, 12.91215102400037]);
 
// Assignment
// Use Gridded Climate dataset to chart a 40+ year time series
// if temparature at any location


// Workflow
// Load the TerraClimate collection
// Select the 'tmmx' band
// Scale the band values
// Filter the scaled collection
// Use ui.Chart.image.series() function to create the chart


// Hint1
// Data needed to be scaled by 0.1
// map() a function and multiply each image
// Multiplying creates a new image that doesn't have the same properties
// Use copyProperties() function to copy timestamp to new image
var tmax = terraclimate.select('tmmx')
var tmaxScaled = tmax.map(function(image) {
 return image.multiply(0.1)
 .copyProperties(image,['system:time\_start']);
})

// Hint2
// You will need to specify a scale in meters for charting
// Use projection().nominalScale() to find the 
// image resolution in meters
var image = ee.Image(terraclimate.first())
print(image.projection().nominalScale())
```





# 模块 3: 有监督分类



## 机器学习和有监督分类简介


Supervised classification is arguably the most important classical machine learning techniques in remote sensing. Applications range from generating Land Use/Land Cover maps to change detection. Google Earth Engine is unique suited to do supervised classification at scale. The interactive nature of Earth Engine development allows for iterative development of supervised classification workflows by combining many different datasets into the model. This module covers basic supervised classification workflow, accuracy assessment, hyperparameter tuning and change detection.


[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/supervised_classification.png)](https://docs.google.com/presentation/d/19L1b5vsxb38xS8GlHNKOjvPZ0IGqDhv93681btMEL5w/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/19L1b5vsxb38xS8GlHNKOjvPZ0IGqDhv93681btMEL5w/edit?usp=sharing)




## 01. 有监督分类基础知识

We will learn how to do a basic land cover classification using training samples collected from the Code Editor using the High Resolution basemap imagery provided by Google Maps. This method requires no prior training data and is quite effective to generate high quality classification samples anywhere in the world. The goal is to classify each source pixel into one of the following classes - urban, bare, water or vegetation. Using the drawing tools in the code editor, you create 4 new feature collection with points representing pixels of that class. Each feature collection has a property called `landcover` with values of 0, 1, 2 or 3 indicating whether the feature collection represents urban, bare, water or vegetation respectively. We then train a *Random Forest* classifier using these training set to build a model and apply it to all the pixels of the image to create a 4 class image.



> 
> Fun fact: The classifiers in Earth Engine API have names starting with **smile** - such as `ee.Classifier.smileRandomForest()`. The *smile* part refers to the [Statistical Machine Intelligence and Learning Engine (SMILE)](https://haifengl.github.io/index.html) JAVA library which is used by Google Earth Engine to implement these algorithms.
> 
> 
> 



![有监督分类输出](https://courses.spatialthoughts.com/images/end_to_end_gee/classified.png)

Supervised Classification Output




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F01d_Basic_Supervised_Classification_(noimport))



```
var bangalore = ee.FeatureCollection("users/ujavalgandhi/public/bangalore\_boundary")
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR")
// The following collections were created using the 
// Drawing Tools in the code editor 
var urban = ee.FeatureCollection("users/ujavalgandhi/e2e/urban\_gcps")
var bare = ee.FeatureCollection("users/ujavalgandhi/e2e/bare\_gcps")
var water = ee.FeatureCollection("users/ujavalgandhi/e2e/water\_gcps")
var vegetation = ee.FeatureCollection("users/ujavalgandhi/e2e/vegetation\_gcps")

 
var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(bangalore))
 .select('B.\*')

var composite = filtered.median().clip(bangalore) 

// Display the input composite.
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
Map.addLayer(composite, rgbVis, 'image');

var gcps = urban.merge(bare).merge(water).merge(vegetation)

// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: gcps, 
 properties: ['landcover'], 
 scale: 10
});


// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50).train({
 features: training, 
 classProperty: 'landcover', 
 inputProperties: composite.bandNames()
});
// // Classify the image.
var classified = composite.classify(classifier);
Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019'); 

// Display the GCPs
// We use the style() function to style the GCPs
var palette = ee.List(['gray','brown','blue','green'])
var landcover = ee.List([0, 1, 2, 3])

var gcpsStyled = ee.FeatureCollection(
 landcover.map(function(lc){
 var color = palette.get(landcover.indexOf(lc));
 var markerStyle = { color: 'white', pointShape: 'diamond', 
 pointSize: 4, width: 1, fillColor: color}
 return gcps.filter(ee.Filter.eq('landcover', lc))
 .map(function(point){
 return point.set('style', markerStyle)
 })
 })).flatten();
 
Map.addLayer(gcpsStyled.style({styleProperty:"style"}), {}, 'GCPs')
Map.centerObject(gcpsStyled)
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F01c_Basic_Supervised_Classification_(exercise))



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR")
var urbanAreas = ee.FeatureCollection("users/ujavalgandhi/e2e/ne\_10m\_urban\_areas")

// Perform supervised classification for your city
// Find the feature id by adding the layer to the map and using Inspector.
var city = urbanAreas.filter(ee.Filter.eq('system:index', '00000000000000002bf8'))
var geometry = city.geometry()
Map.centerObject(geometry)

var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))
 .select('B.\*')

var composite = filtered.median().clip(geometry) 

// Display the input composite.

var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};
Map.addLayer(composite, rgbVis, 'image');

// Exercise
// Add training points for 4 classes
// Assign the 'landcover' property as follows

// urban: 0
// bare: 1
// water: 2
// vegetation: 3

// After adding points, uncomments lines below

// var gcps = urban.merge(bare).merge(water).merge(vegetation)



// // Overlay the point on the image to get training data.
// var training = composite.sampleRegions({
// collection: gcps, 
// properties: ['landcover'], 
// scale: 10,
// tileScale: 16
// });
// print(training)


// // Train a classifier.
// var classifier = ee.Classifier.smileRandomForest(50).train({
// features: training, 
// classProperty: 'landcover', 
// inputProperties: composite.bandNames()
// });
// // // Classify the image.
// var classified = composite.classify(classifier);
// Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019'); 
```




## 02. 准确度评估

It is important to get a quantitative estimate of the accuracy of the classification. To do this, a common strategy is to divide your training samples into 2 random fractions - one used for *training* the model and the other for *validation* of the predictions. Once a classifier is trained, it can be used to classify the entire image. We can then compare the classified values with the ones in the validation fraction. We can use the `ee.Classifier.confusionMatrix()` method to calculate a *Confusion Matrix* representing expected accuracy.


Classification results are evaluated based on the following metrics


* **Overall Accuracy**: How many samples were classified correctly.
* **Producer’s Accuracy**: How well did the classification predict each class.
* **Consumer’s Accuracy (Reliability)**: How reliable is the prediction in each class.
* **Kappa Coefficient**: How well the classification performed as compared to random assignment.



![准确度评估](https://courses.spatialthoughts.com/images/end_to_end_gee/accuracy_assessment.png)

Accuracy Assessment





> 
> Don’t get carried away tweaking your model to give you the highest validation accuracy. You must use both qualitative measures (such as visual inspection of results) along with quantitative measures to assess the results.
> 
> 
> 


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F02b_Accuracy_Assessment_(complete))



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_gcps");
 
var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
 
var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .select('B.\*')

var composite = filtered.median().clip(boundary) 

// Display the input composite.
Map.addLayer(composite, rgbVis, 'image');


// Add a random column and split the GCPs into training and validation set
var gcp = gcp.randomColumn()

// This being a simpler classification, we take 60% points
// for validation. Normal recommended ratio is
// 70% training, 30% validation
var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));

// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: trainingGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});

// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50)
.train({
 features: training, 
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
});

// Classify the image.
var classified = composite.classify(classifier);

Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Accuracy Assessment
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Use classification map to assess accuracy using the validation fraction
// of the overall training set created above.
var test = classified.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 tileScale: 16,
 scale: 10,
});

var testConfusionMatrix = test.errorMatrix('landcover', 'classification')
// Printing of confusion matrix may time out. Alternatively, you can export it as CSV
print('Confusion Matrix', testConfusionMatrix);
print('Test Accuracy', testConfusionMatrix.accuracy());

// Alternate workflow 
// This is similar to machine learning practice
var validation = composite.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});

var test = validation.classify(classifier);

var testConfusionMatrix = test.errorMatrix('landcover', 'classification')
// Printing of confusion matrix may time out. Alternatively, you can export it as CSV
print('Confusion Matrix', testConfusionMatrix);
print('Test Accuracy', testConfusionMatrix.accuracy());
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F02c_Accuracy_Assessment_(exercise))



```
var classified = ee.Image('users/ujavalgandhi/e2e/arkavathy\_base\_classification');
var gcp = ee.FeatureCollection('users/ujavalgandhi/e2e/arkavathy\_gcps');
var gcp = gcp.randomColumn()

var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Accuracy Assessment
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Use classification map to assess accuracy using the validation fraction
// of the overall training set created above.
var test = classified.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 tileScale: 16,
 scale: 10,
});

var testConfusionMatrix = test.errorMatrix('landcover', 'classification')
print('Confusion Matrix', testConfusionMatrix);
print('Test Accuracy', testConfusionMatrix.accuracy());

// Exercise

// Calculate and print the following assessment metrics
// 1. Producer's accuracy
// 2. Consumer's accuracy
// 3. Kappa coefficient

// Hint: Look at the ee.ConfusionMatrix module for appropriate methods
```




## 03. 改进分类

The Earth Engine data-model is especially well suited for machine learning tasks because of its ability to easily incorporate data sources of different spatial resolutions, projections and data types together By giving additional information to the classifier, it is able to separate different classes easily. Here we take the same example and augment it with the following techniques


* *应用云遮蔽（Cloud Masking）*
* *Add Spectral Indices*: We add bands for different spectral indices such as - NDVI, NDBI, MNDWI and BSI.
* *Add Elevation and Slope*: We also add slope and elevation bands from the ALOS DEM.
* *Normalize the Inputs*: Machine learning models work best when all the inputs have the same scale. We will divide each band with the maximum value. This method ensures that all input values are between 0-1. A more [complete and robust technique](#image-normalization-and-standardization) for image normalization is provided in the course Supplement.


Our training features have more parameters and contain values of the same scale. The result is a much improved classification.



![Improved Classification Accuracy with use of Spectral Indices and Elevation Data](https://courses.spatialthoughts.com/images/end_to_end_gee/improving_classification.png)

Improved Classification Accuracy with use of Spectral Indices and Elevation Data




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F03b_Improving_the_Classification_(complete))



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_gcps");
var alos = ee.Image("JAXA/ALOS/AW3D30/V2\_2");


var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
// Function to remove cloud and snow pixels from Sentinel-2 SR image

function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(10);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 10% or cloud shadow classification
 var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask);
}


var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .map(maskCloudAndShadowsSR)
 .select('B.\*')

var composite = filtered.median().clip(boundary) 


var addIndices = function(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
 var bsi = image.expression(
 '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
 'X': image.select('B11'), //swir1
 'Y': image.select('B4'), //red
 'A': image.select('B8'), // nir
 'B': image.select('B2'), // blue
 }).rename('bsi');
 return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

var composite = addIndices(composite);


// Calculate Slope and Elevation
var elev = alos.select('AVE\_DSM').rename('elev');
var slope = ee.Terrain.slope(alos.select('AVE\_DSM')).rename('slope');

var composite = composite.addBands(elev).addBands(slope);

var visParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 3000, gamma: 1.2};
Map.addLayer(composite, visParams, 'RGB');

// Normalize the image 

// Machine learning algorithms work best on images when all features have
// the same range

// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function normalize(image){
 var bandNames = image.bandNames();
 // Compute min and max of the image
 var minDict = image.reduceRegion({
 reducer: ee.Reducer.min(),
 geometry: boundary,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var maxDict = image.reduceRegion({
 reducer: ee.Reducer.max(),
 geometry: boundary,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var mins = ee.Image.constant(minDict.values(bandNames));
 var maxs = ee.Image.constant(maxDict.values(bandNames));

 var normalized = image.subtract(mins).divide(maxs.subtract(mins))
 return normalized
}

var composite = normalize(composite);
// Add a random column and split the GCPs into training and validation set
var gcp = gcp.randomColumn()

// This being a simpler classification, we take 60% points
// for validation. Normal recommended ratio is
// 70% training, 30% validation
var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));

// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: trainingGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});
print(training)
// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50)
.train({
 features: training, 
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
});

// Classify the image.
var classified = composite.classify(classifier);

Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Accuracy Assessment
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Use classification map to assess accuracy using the validation fraction
// of the overall training set created above.
var test = classified.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});

var testConfusionMatrix = test.errorMatrix('landcover', 'classification')
// Printing of confusion matrix may time out. Alternatively, you can export it as CSV
print('Confusion Matrix', testConfusionMatrix);
print('Test Accuracy', testConfusionMatrix.accuracy());
 
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F03c_Improving_the_Classification_(exercise))



```
// Exercise

// Improve your classification from Exercise 01c 
// Add different spectral indicies to your composite
// by using the function below

var addIndices = function(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
 var bsi = image.expression(
 '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
 'X': image.select('B11'), //swir1
 'Y': image.select('B4'), //red
 'A': image.select('B8'), // nir
 'B': image.select('B2'), // blue
 }).rename('bsi');
 return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

 
```




## 04. 导出分类结果


When working with complex classifiers over large regions, you may get a *User memory limit exceeded* or *Computation timed out* error in the Code Editor. The reason for this is that there is a fixed time limit and smaller memory allocated for code that is run with the *On-Demand Computation* mode. For larger computations, you can use the *Batch* mode with the `Export` functions. Exports run in the background and can run longer than 5-minutes time allocated to the computation code run from the Code Editor. This allows you to process very large and complex datasets. Here’s an example showing how to export your classification results to Google Drive.



> 
> We can only export Images or FeatureCollections. What if you wanted to export a number that is the result of a long computation? A useful *hack* is to create a FeatureCollection with just 1 feature containing `null` geometry and a property containing the number you want to export.
> 
> 
> 



![导出分类结果](https://courses.spatialthoughts.com/images/end_to_end_gee/export_classification.png)

Exported Classification Outputs




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F04b_Exporting_Classification_Results_(complete))



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_gcps");
var alos = ee.Image("JAXA/ALOS/AW3D30/V2\_2");


var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
// Function to remove cloud and snow pixels from Sentinel-2 SR image

function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(10);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 10% or cloud shadow classification
 var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask);
}


var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .map(maskCloudAndShadowsSR)
 .select('B.\*')

var composite = filtered.median().clip(boundary) 


var addIndices = function(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
 var bsi = image.expression(
 '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
 'X': image.select('B11'), //swir1
 'Y': image.select('B4'), //red
 'A': image.select('B8'), // nir
 'B': image.select('B2'), // blue
 }).rename('bsi');
 return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

var composite = addIndices(composite);


// Calculate Slope and Elevation
var elev = alos.select('AVE\_DSM').rename('elev');
var slope = ee.Terrain.slope(alos.select('AVE\_DSM')).rename('slope');

var composite = composite.addBands(elev).addBands(slope);

var visParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 3000, gamma: 1.2};
Map.addLayer(composite, visParams, 'RGB');

// Normalize the image 

// Machine learning algorithms work best on images when all features have
// the same range

// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function normalize(image){
 var bandNames = image.bandNames();
 // Compute min and max of the image
 var minDict = image.reduceRegion({
 reducer: ee.Reducer.min(),
 geometry: boundary,
 scale: 20,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var maxDict = image.reduceRegion({
 reducer: ee.Reducer.max(),
 geometry: boundary,
 scale: 20,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var mins = ee.Image.constant(minDict.values(bandNames));
 var maxs = ee.Image.constant(maxDict.values(bandNames));

 var normalized = image.subtract(mins).divide(maxs.subtract(mins))
 return normalized
}

var composite = normalize(composite);
// Add a random column and split the GCPs into training and validation set
var gcp = gcp.randomColumn()

// This being a simpler classification, we take 60% points
// for validation. Normal recommended ratio is
// 70% training, 30% validation
var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));
Map.addLayer(validationGcp)
// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: trainingGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});
print(training)
// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50)
.train({
 features: training, 
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
});

// Classify the image.
var classified = composite.classify(classifier);

Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Accuracy Assessment
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Use classification map to assess accuracy using the validation fraction
// of the overall training set created above.
var test = classified.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});

var testConfusionMatrix = test.errorMatrix('landcover', 'classification')
print('Confusion Matrix', testConfusionMatrix);
print('Test Accuracy', testConfusionMatrix.accuracy()); 

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Exporting Results
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Create a Feature with null geometry and the value we want to export.
// Use .array() to convert Confusion Matrix to an Array so it can be
// exported in a CSV file
var fc = ee.FeatureCollection([
 ee.Feature(null, {
 'accuracy': testConfusionMatrix.accuracy(),
 'matrix': testConfusionMatrix.array()
 })
 ])
print(fc) 
Export.table.toDrive({
 collection: fc,
 description: 'Accuracy\_Export',
 folder: 'earthengine',
 fileNamePrefix: 'accuracy',
 fileFormat: 'CSV'
})
```


### 练习


It is also a good idea to export the classified image as an Asset. This will allows you to import the classified image in another script without running the whole classification workflow. Use the Export.image.toAsset() function to export the classified image as an asset.


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F04c_Exporting_Classification_Results_(exercise))



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_gcps");
var alos = ee.Image("JAXA/ALOS/AW3D30/V2\_2");


var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
// Function to remove cloud and snow pixels from Sentinel-2 SR image

function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(10);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 10% or cloud shadow classification
 var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask);
}


var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .map(maskCloudAndShadowsSR)
 .select('B.\*')

var composite = filtered.median().clip(boundary) 


var addIndices = function(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
 var bsi = image.expression(
 '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
 'X': image.select('B11'), //swir1
 'Y': image.select('B4'), //red
 'A': image.select('B8'), // nir
 'B': image.select('B2'), // blue
 }).rename('bsi');
 return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

var composite = addIndices(composite);


// Calculate Slope and Elevation
var elev = alos.select('AVE\_DSM').rename('elev');
var slope = ee.Terrain.slope(alos.select('AVE\_DSM')).rename('slope');

var composite = composite.addBands(elev).addBands(slope);

var visParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 3000, gamma: 1.2};
Map.addLayer(composite, visParams, 'RGB');

// Normalize the image 

// Machine learning algorithms work best on images when all features have
// the same range

// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function normalize(image){
 var bandNames = image.bandNames();
 // Compute min and max of the image
 var minDict = image.reduceRegion({
 reducer: ee.Reducer.min(),
 geometry: boundary,
 scale: 20,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var maxDict = image.reduceRegion({
 reducer: ee.Reducer.max(),
 geometry: boundary,
 scale: 20,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var mins = ee.Image.constant(minDict.values(bandNames));
 var maxs = ee.Image.constant(maxDict.values(bandNames));

 var normalized = image.subtract(mins).divide(maxs.subtract(mins))
 return normalized
}

var composite = normalize(composite);
// Add a random column and split the GCPs into training and validation set
var gcp = gcp.randomColumn()

// This being a simpler classification, we take 60% points
// for validation. Normal recommended ratio is
// 70% training, 30% validation
var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));
Map.addLayer(validationGcp)
// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: trainingGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});
// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50)
.train({
 features: training, 
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
});

// Classify the image.
var classified = composite.classify(classifier);

Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

// Exercise 

// Use the Export.image.toAsset() function to export the 
// classified image as a Earth Engine Asset.

// This will allows you to import the classified image in another script
// without running the whole classification workflow.

// Hint: For images with discrete pixel values, we must set the
// pyramidingPolicy to 'mode'.
// The pyramidingPolicy parameter should a dictionary specifying
// the policy for each band. A simpler way to specify it for all
// bands is to use {'.default': 'mode'}
```




## 05. 计算面积

Now that we have the results of our classification, we will learn how to calculate the area for pixels in each class. Calculating area for features is done using the `area()` function and for images using the `ee.Image.pixelArea()` function. The `ee.Image.pixelArea()` function creates an image where each pixel’s value is the area of the pixel. We multiply this pixel area image with our image and sum up the area using the `reduceRegion()` function.



> 
> The `ee.Image.pixelArea()` function uses a custom equal-area projection for area calculation. The result is area in square meters regardless of the projection of the input image. [Learn more](https://groups.google.com/g/google-earth-engine-developers/c/Ccaorx-obVw/m/_ZQdP2wVAgAJ)
> 
> 
> 



![Calculating Green Cover from Classified Image](https://courses.spatialthoughts.com/images/end_to_end_gee/area_calculation.png)

Calculating Green Cover from Classified Image




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F05b_Calculating_Area_(complete))



```
var classified = ee.Image("users/ujavalgandhi/e2e/bangalore\_classified");
var bangalore = ee.FeatureCollection("users/ujavalgandhi/public/bangalore\_boundary");

Map.addLayer(bangalore, {color: 'blue'}, 'Bangalore City')
Map.addLayer(classified,
 {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']},
 'Classified Image 2019');

// Calling .geometry() on a feature collection gives the
// dissolved geometry of all features in the collection

// .area() function calculates the area in square meters
var cityArea = bangalore.geometry().area()

// We can cast the result to a ee.Number() and calculate the
// area in square kilometers
var cityAreaSqKm = ee.Number(cityArea).divide(1e6).round()
print(cityAreaSqKm)


// Area Calculation for Images
var vegetation = classified.eq(3)
// If the image contains values 0 or 1, we can calculate the
// total area using reduceRegion() function

// The result of .eq() operation is a binary image with pixels
// values of 1 where the condition matched and 0 where it didn't
Map.addLayer(vegetation, {min:0, max:1, palette: ['white', 'green']}, 'Green Cover')

// Since our image has only 0 and 1 pixel values, the vegetation
// pixels will have values equal to their area
var areaImage = vegetation.multiply(ee.Image.pixelArea())


// Now that each pixel for vegetation class in the image has the value
// equal to its area, we can sum up all the values in the region
// to get the total green cover.

var area = areaImage.reduceRegion({
 reducer: ee.Reducer.sum(),
 geometry: bangalore.geometry(),
 scale: 10,
 maxPixels: 1e10
 })
// The result of the reduceRegion() function is a dictionary with the key
// being the band name. We can extract the area number and convert it to
// square kilometers
var vegetationAreaSqKm = ee.Number(area.get('classification')).divide(1e6).round()
print(vegetationAreaSqKm)
```


> 
> If you want to compute area covered by each class, you can use a [Grouped Reducer](https://developers.google.com/earth-engine/reducers_grouping). See the [Supplement](#calculating-area-by-class) to see a code snippet.
> 
> 
> 



### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F05c_Calculating_Area_(exercise))



```
// Exercise
// Compute and print the percentage green cover of the city
```





# 模块 4: 变化检测


## 变化检测简介

Many earth observation datasets are available at regular intervals over long periods of time. This enables us to detect changes on the Earth’s surface. Change detection technique in remote sensing fall in the following categories


* **Single Band Change**: Measuring change in a single band image or a spectral index using a threshold
* **Multi Band Change**: Measuring spectral distance and spectral angle between two multiband images
* **Classification of Change**: One-pass classification using stacked image containing bands from before and after an event
* **Post Classification Comparison**: Comparing two classified images and computing class transitions


In the following sections, we will apply the supervised classification techniques for change detection using multi-temporal images.


[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/change_detection.png)](https://docs.google.com/presentation/d/1vdFTWJ61yDuVfbfhpnumQ8zuMPGwGcHpHsBTRgo_o5I/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/1vdFTWJ61yDuVfbfhpnumQ8zuMPGwGcHpHsBTRgo_o5I/edit?usp=sharing)




## 01. 光谱指数变化

Many types of change can be detected by measuring the change in a spectral index and applying a threshold. This technique is suitable when there is a suitable spectral index is available for the type of change you are interested in detecting.


Here we apply this technique to map the extent and severity of a forest fire. The **Normalized Burn Ratio (NBR)** is an index that is designed to highlight burnt vegetation areas. We compute the NBR for before and after images. Then we apply a suitable threshold to find burnt areas.



![Spectral Index Change Detection](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_index_change.png)

Spectral Index Change Detection




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01b_Spectral_Index_Change_(complete))



```
// On 21st February 2019, massive forest fires broke out in
// numerous places across the Bandipur National Park of
// the Karnataka state in India.
// By 25 February 2019 most fire was brought under control
// This script shows how to do damage assessment using
// spectral index change detection technique.

// Define the area of interest
var geometry = ee.Geometry.Polygon([[
 [76.37639666685044, 11.766523239445169],
 [76.37639666685044, 11.519036946599561],
 [76.78426409849106, 11.519036946599561],
 [76.78426409849106, 11.766523239445169]
]]);
var fireStart = ee.Date('2019-02-20');
var fireEnd = ee.Date('2019-02-25');

Map.centerObject(geometry, 10)

var s2 = ee.ImageCollection("COPERNICUS/S2")

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
} 

// Apply filters and cloud mask
var filtered = s2
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 .select('B.\*')

// Create Before and After composites
var before = filtered
 .filter(ee.Filter.date(
 fireStart.advance(-2, 'month'), fireStart))
 .median()

var after = filtered
 .filter(ee.Filter.date(
 fireEnd, fireEnd.advance(1, 'month')))
 .median()

// Freshly burnt regions appeat bright in SWIR-bands
// Use a False Color Visualization
var swirVis = {
 min: 0.0,
 max: 3000,
 bands: ['B12', 'B8', 'B4'],
};
Map.addLayer(before, swirVis, 'Before')
Map.addLayer(after, swirVis, 'After')

// Write a function to calculate Normalized Burn Ratio (NBR)
// 'NIR' (B8) and 'SWIR-2' (B12)
var addNBR = function(image) {
 var ndbi = image.normalizedDifference(['B8', 'B12']).rename(['nbr']);
 return image.addBands(ndbi)
}

var beforeNbr = addNBR(before).select('nbr');
var afterNbr = addNBR(after).select('nbr');

var nbrVis = {min: -0.5, max: 0.5, palette: ['white', 'black']}

Map.addLayer(beforeNbr, nbrVis, 'Prefire NBR');
Map.addLayer(afterNbr, nbrVis, 'Postfire NBR');

// Calculate Change in NBR (dNBR)
var change = beforeNbr.subtract(afterNbr)

// Apply a threshold
var threshold = 0.3

// Display Burned Areas
var burned = change.gt(threshold)
Map.addLayer(burned, {min:0, max:1, palette: ['white', 'red']}, 'Burned', false) 
```


### 练习



![Classifying the Change Image](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_index_change_exercise.png)

Classifying the Change Image




[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01c_Spectral_Index_Change_(exercise))



```
// Define the area of interest
var geometry = ee.Geometry.Polygon([[
 [76.37639666685044, 11.766523239445169],
 [76.37639666685044, 11.519036946599561],
 [76.78426409849106, 11.519036946599561],
 [76.78426409849106, 11.766523239445169]
]]);
var fireStart = ee.Date('2019-02-20');
var fireEnd = ee.Date('2019-02-25');

Map.centerObject(geometry, 10)

var s2 = ee.ImageCollection("COPERNICUS/S2")

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
} 

// Apply filters and cloud mask
var filtered = s2
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 .select('B.\*')

// Create Before and After composites
var before = filtered
 .filter(ee.Filter.date(
 fireStart.advance(-2, 'month'), fireStart))
 .median()

var after = filtered
 .filter(ee.Filter.date(
 fireEnd, fireEnd.advance(1, 'month')))
 .median()


// Write a function to calculate Normalized Burn Ratio (NBR)
// 'NIR' (B8) and 'SWIR-2' (B12)
var addNBR = function(image) {
 var ndbi = image.normalizedDifference(['B8', 'B12']).rename(['nbr']);
 return image.addBands(ndbi)
}

var beforeNbr = addNBR(before).select('nbr');
var afterNbr = addNBR(after).select('nbr');

// Calculate Change in NBR (dNBR)
var change = beforeNbr.subtract(afterNbr)

var dnbrPalette = ['#ffffb2','#fecc5c','#fd8d3c','#f03b20','#bd0026'];
// Display the change image
Map.addLayer(change, {min:0.1, max: 0.7, palette: dnbrPalette},
 'Change in NBR')

// We can also classify the change image according to
// burn severity

// United States Geological Survey (USGS) proposed
// a classification table to interpret the burn severity
// We will assign a discrete class value and visualize it
// | Severity | dNBR Range | Class |
// |--------------|--------------------|-------|
// | Unburned | < 0.1 | 0 |
// | Low Severity | >= 0.10 and <0.27 | 1 |
// | Moderate-Low | >= 0.27 and <0.44 | 2 |
// | Moderate-High| >= 0.44 and< 0.66 | 3 |
// | High | >= 0.66 | 4 |

// Classification of continuous values can be done
// using the .where() function
var severity = change
 .where(change.lt(0.10), 0)
 .where(change.gte(0.10).and(change.lt(0.27)), 1)
 .where(change.gte(0.27).and(change.lt(0.44)), 2)
 .where(change.gte(0.44).and(change.lt(0.66)), 3)
 .where(change.gt(0.66), 4)


// Exercise

// The resulting image 'severity' is a discrete image with 
// pixel values from 0-4 representing the severity class

// Display the image according to the following color table

// | Severity | Class | Color |
// |--------------|-------|---------|
// | Unburned | 0 | green |
// | Low Severity | 1 | yellow |
// | Moderate-Low | 2 | organge |
// | Moderate-High| 3 | red |
// | High | 4 | magenta |
```




## 02. 光谱距离变化

When you want to detect changes from multi-band images, a useful technique is to compute the Spectral Distance and Spectral Angle between the two images. Pixels that exhibit a large change will have a larger distance compared to those that did not change. This technique is particularly useful when there are no suitable index to detect the change. It can be applied to detect change after natural disasters or human conflicts.


Here we use this technique to detect landslides using before/after composites. You may learn more about this technique at [Craig D’Souza’s Change Detection](https://goo.gl/xotYhk) presentation.



![Spectral Distance Change Detection](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_distance.png)

Spectral Distance Change Detection




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01b_Spectral_Distance_Change_(complete))



```
var geometry = ee.Geometry.Polygon([[
 [75.70357667713435, 12.49723970868507],
 [75.70357667713435, 12.470171844429931],
 [75.7528434923199, 12.470171844429931],
 [75.7528434923199, 12.49723970868507]
]]);
Map.centerObject(geometry)
var s2 = ee.ImageCollection("COPERNICUS/S2")
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
} 

var filtered = s2
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 .select('B.\*')
 
var dateOfIncident = ee.Date('2018-12-15')
var before = filtered
 .filter(ee.Filter.date(
 dateOfIncident.advance(-2, 'year'), dateOfIncident))
 .filter(ee.Filter.calendarRange(12, 12, 'month'))
 .median()
 
var after = filtered
 .filter(ee.Filter.date(
 dateOfIncident, dateOfIncident.advance(1, 'month')))
 .median()


Map.addLayer(before, rgbVis, 'Before')
Map.addLayer(after, rgbVis, 'After')

// Use the spectralDistnace() function to get spectral distance measures

// Use the metric 'Spectral Angle Mapper (SAM)
// The result is the spectral angle in radians
var angle = after.spectralDistance(before, 'sam');
Map.addLayer(angle, {min: 0, max: 1, palette: ['white', 'purple']}, 'Spectral Angle');

// Use the metric 'Squared Euclidian Distance (SED)'
var sed = after.spectralDistance(before, 'sed');
// Take square root to get euclidian distance
var distance = sed.sqrt();

Map.addLayer(distance, {min: 0, max: 1500, palette: ['white', 'red']}, 'spectral distance');
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01c_Spectral_Distance_Change_(exercise))



```
var geometry = ee.Geometry.Polygon([[
 [75.70357667713435, 12.49723970868507],
 [75.70357667713435, 12.470171844429931],
 [75.7528434923199, 12.470171844429931],
 [75.7528434923199, 12.49723970868507]
]]);
Map.centerObject(geometry)
var s2 = ee.ImageCollection("COPERNICUS/S2")
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
} 

var filtered = s2
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 .select('B.\*')
 
var dateOfIncident = ee.Date('2018-12-15')
var before = filtered
 .filter(ee.Filter.date(
 dateOfIncident.advance(-2, 'year'), dateOfIncident))
 .filter(ee.Filter.calendarRange(12, 12, 'month'))
 .median()
var after = filtered.filter(ee.Filter.date(
 dateOfIncident, dateOfIncident.advance(1, 'month'))).median()


Map.addLayer(before, rgbVis, 'Before')
Map.addLayer(after, rgbVis, 'After')

var sed = after.spectralDistance(before, 'sed');
var distance = sed.sqrt();

Map.addLayer(distance, {min: 0, max: 1500, palette: ['white', 'red']}, 'spectral distance');

// Exercise
// Inspect the distance image and find a suitable threshold
// that signifies damage after the landslides
// Apply the threshold and create a new image showing landslides
// Display the results

// Hint: Use the .gt() method to apply the threshold
```




## 03. 变化的直接分类

This technique of change detection is also known as *One-pass Classification* or *Direct Multi-date Classification*. Here we create a single stacked image containing bands from before and after images. We train a classifier with training data sampled from the stacked image and apply the classifier on the stacked image to find all change pixels.



![All pixels that changed from bare ground to built-up](https://courses.spatialthoughts.com/images/end_to_end_gee/change_classification.png)

All pixels that changed from bare ground to built-up




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F03b_Classifying_Change_(complete))



```
var bangalore = ee.FeatureCollection('users/ujavalgandhi/public/bangalore\_boundary');
var change = ee.FeatureCollection('users/ujavalgandhi/e2e/bangalore\_change\_gcps');
var nochange = ee.FeatureCollection('users/ujavalgandhi/e2e/bangalore\_nochange\_gcps')
var s2 = ee.ImageCollection("COPERNICUS/S2")

var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
} 

var filtered = s2
 .filter(ee.Filter.date('2019-01-01', '2019-02-01'))
 .filter(ee.Filter.bounds(bangalore))
 .map(maskS2clouds)

 
var image2019 = filtered.median().clip(bangalore)
// Display the input composite.
Map.addLayer(image2019, rgbVis, '2019');

var filtered = s2
 .filter(ee.Filter.date('2020-01-01', '2020-02-01'))
 .filter(ee.Filter.bounds(bangalore))
 .map(maskS2clouds)

var image2020 = filtered.median().clip(bangalore)

Map.addLayer(image2020, rgbVis, '2020');

var stackedImage = image2019.addBands(image2020)

// Overlay the point on the image to get training data.
var training = stackedImage.sampleRegions({
 collection: change.merge(nochange), 
 properties: ['class'], 
 scale: 10
});

// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50).train({
 features: training, 
 classProperty: 'class', 
 inputProperties: stackedImage.bandNames()
});

// Classify the image.
var classified = stackedImage.classify(classifier);
Map.addLayer(classified, {min: 0, max: 1, palette: ['white', 'red']}, 'change'); 
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F03c_Classifying_Change_(exercise))



```
// Add an NDBI band to improve the detection of changes.

var addNDBI = function(image) {
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 return image.addBands(ndbi)
}

// use addNDBI() function to add the NDBI band to both 2019 and 2020 composite images
// Hint1: You can save the resulting image in the same variable to avoid changing 
// a lot of code.
// var image = addNDBI(image)
```




## 04. 分类后对比

We dealing with multi-class images, a useful metric for change detection is to know how many pixels from class X changed to class Y. This can be accomplished using the `ee.Reducer.frequencyHistogram()` reducer as shown below.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F04b_Post_Classification_Comparison_(complete))



```
var bangalore = ee.FeatureCollection("users/ujavalgandhi/public/bangalore\_boundary")
var urban = ee.FeatureCollection("users/ujavalgandhi/e2e/urban\_gcps")
var bare = ee.FeatureCollection("users/ujavalgandhi/e2e/bare\_gcps")
var water = ee.FeatureCollection("users/ujavalgandhi/e2e/water\_gcps")
var vegetation = ee.FeatureCollection("users/ujavalgandhi/e2e/vegetation\_gcps")
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR")

Map.centerObject(bangalore)
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'], 
};

// 2019 Jan
var filtered = s2
 .filter(ee.Filter.date('2019-01-01', '2019-02-01'))
 .filter(ee.Filter.bounds(bangalore))
 .select('B.\*')

 
var before = filtered.median().clip(bangalore)
// Display the input composite.
Map.addLayer(before, rgbVis, 'before');

var training = urban.merge(bare).merge(water).merge(vegetation)

// Overlay the point on the image to get training data.
var training = before.sampleRegions({
 collection: training, 
 properties: ['landcover'], 
 scale: 10
});

// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50).train({
 features: training, 
 classProperty: 'landcover', 
 inputProperties: before.bandNames()
});

// // Classify the image.
var beforeClassified = before.classify(classifier);
Map.addLayer(beforeClassified,
 {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, 'before\_classified');


// 2020 Jan
var after = s2
 .filter(ee.Filter.date('2020-01-01', '2020-02-01'))
 .filter(ee.Filter.bounds(bangalore))
 .select('B.\*')
 .median()
 .clip(bangalore)

Map.addLayer(after, rgbVis, 'after');

// Classify the image.
var afterClassified= after.classify(classifier);
Map.addLayer(afterClassified,
 {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, 'after\_classified');

// Reclassify from 0-3 to 1-4
var beforeClasses = beforeClassified.remap([0, 1, 2, 3], [1, 2, 3, 4])
var afterClasses = afterClassified.remap([0, 1, 2, 3], [1, 2, 3, 4])

// Show all changed areas
var changed = afterClasses.subtract(beforeClasses).neq(0)
Map.addLayer(changed, {min:0, max:1, palette: ['white', 'red']}, 'Change')

// We multiply the before image with 100 and add the after image
// The resulting pixel values will be unique and will represent each unique transition
// i.e. 102 is urban to bare, 103 urban to water etc.
var merged = beforeClasses.multiply(100).add(afterClasses).rename('transitions')

// Use a frequencyHistogram to get a pixel count per class
var transitionMatrix = merged.reduceRegion({
 reducer: ee.Reducer.frequencyHistogram(), 
 geometry: bangalore,
 maxPixels: 1e10,
 scale:10,
 tileScale: 16
})
// This prints number of pixels for each class transition
print(transitionMatrix.get('transitions'))

// If we want to calculate the area of each class transition
// we can use a grouped reducer

// Divide by 1e6 to get the area in sq.km.
var areaImage = ee.Image.pixelArea().divide(1e6).addBands(merged);
// Calculate Area by each Transition Class
// using a Grouped Reducer
var areas = areaImage.reduceRegion({
 reducer: ee.Reducer.sum().group({
 groupField: 1,
 groupName: 'transitions',
 }),
 geometry: bangalore,
 scale: 100,
 tileScale: 4,
 maxPixels: 1e10
 }); 

// Post-process the result to generate a clean output
var classAreas = ee.List(areas.get('groups'))
var classAreaLists = classAreas.map(function(item) {
 var areaDict = ee.Dictionary(item)
 var classNumber = ee.Number(areaDict.get('transitions')).format()
 var area = ee.Number(areaDict.get('sum')).round()
 return ee.List([classNumber, area])
 })
var classTransitionsAreaDict = ee.Dictionary(classAreaLists.flatten())
print(classTransitionsAreaDict)
```


### 练习



![Lost water pixels between 2019 and 2020](https://courses.spatialthoughts.com/images/end_to_end_gee/post_classification.png)

Lost water pixels between 2019 and 2020




[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F04c_Post_Classification_Comparison_(exercise))



```
// Exercise
// Show all areas where water became other classes and display the result
// Hint1: Select class 3 pixels from before image and NOT class 3 pixels from after image
// Hint2: use the .and() operation to select pixels matching both conditions
```





# 模块 5: Earth Engine 应用


This module is focused the concepts related to client vs. server that will help you in creating web apps. We will be building an app using the Earth Engine User Interface API and publishing it to Google Cloud.



## 01. 客户端与服务器

The User Interface elements in your Code Editor - Map View, Drawing Tools etc. are ‘client-side’ elements. They run in YOUR browser. Image Collections, feature collections, calculations on Earth Engine objects etc. are ‘server-side’ elements. They run in Google’s data center. You cannot mix both these objects. To learn more, visit the [Client vs. Server](https://developers.google.com/earth-engine/guides/client_server) section of the Earth Engine User Guide.


* To convert client-side objects to server-side objects, you can use the appropriate API function. Server-side functions start with `ee.`, such `ee.Date()`, `ee.Image()` etc.
* To convert server-side objects to client-side objects, you can call `.getInfo()` on am Earth Engine object. For the Python API, this is the only way to extract information from a server-side object, but the Javascript API provides a better (and preferred) - method for bring server-side objects to client-side using the `evaluate()` method. This method asynchronously retrieves the value of the object, without blocking the user interface - meaning it will let your code continue to execute while it fetches the value.



> 
> Tip: You can use `ee.Algorithms.ObjectType()` to get the type of a server-side object
> 
> 
> 


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F01b_Client_vs_Server_(complete))



```
var date = '2020-01-01' // This is client-side
print(typeof(date))

var eedate = ee.Date('2020-01-01').format() // This is server-side
print(typeof(eedate)) 

// To bring server-side objects to client-side, you can call .getInfo()

// var clientdate = eedate.getInfo()
// print(clientdate)
// print(typeof(clientdate)) 

// getInfo() blocks the execution of your code till the value is fetched
// If the value takes time to compute, your code editor will freeze
// This is not a good user experience
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR")
var filtered = s2.filter(ee.Filter.date('2020-01-01', '2021-01-01'))

//var numImages = filtered.size().getInfo()
//print(numImages)

// A better approach is to use evaluate() function

// You need to define a 'callback' function which will be called once the 
// value has been computed and ready to be used.

var myCallback = function(object) {
 print(object)
}
print('Computing the size of the collection')
var numImages = filtered.size().evaluate(myCallback)
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F01c_Client_vs_Server_(exercise))



```
var date = ee.Date.fromYMD(2019, 1, 1)
print(date)

// We can use the format() function to create
// a string from a date object
var dateString = date.format('dd MMM, YYYY')
print(dateString)

// Exercise
// The print statement below combines a client-side string
// with a server-side string - resulting in an error.

// Fix the code so that the following message is printed
// 'The date is 01 Jan, 2019'
var message = 'The date is ' + dateString
print(message)

// Hint: 
// Convert the client-side string to a server-side string
// Use ee.String() to create a server-side string
// Use the .cat() function instead of + to combine 2 strings
```




## 02. 使用 UI 元素


Earth Engine comes with a User Interface API that allows you to build an interactive web application powered by Earth Engine.


The Earth Engine API provides a library of User Interface (UI) widgets - such as Buttons, Drop-down Menus, Sliders etc. - that can be used to create interactive apps. All the user interface functions are contained in the `ui.` package - such as `ui.Select()`, `ui.Button()`. You can create those elements by calling these functions with appropriate parameters. Learn more in the [Earth Engine User Interface API](https://developers.google.com/earth-engine/guides/ui) section of the Earth Engine User Guide.


This section shows how to build a drop-down selector using the `ui.Select()` widget.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F02b_Using_UI_Elements_(complete))



```
// You can add any widgets from the ui.\* module to the map
var years = ['2014', '2015', '2016', '2017'];

// Let's create a ui.Select() dropdown with the above values
var yearSelector = ui.Select({
 items: years,
 value: '2014',
 placeholder: 'Select a year',
 })
Map.add(yearSelector);

var loadImage = function() {
 var year = yearSelector.getValue();
 var col = ee.ImageCollection("NOAA/VIIRS/DNB/MONTHLY\_V1/VCMSLCFG");
 var startDate = ee.Date.fromYMD(
 ee.Number.parse(year), 1, 1);
 var endDate = startDate.advance(1, 'year');
 var filtered = col.filter(ee.Filter.date(startDate, endDate));
 var composite = filtered.mean().select('avg\_rad');
 var layerName = 'Night Lights ' + year;
 var nighttimeVis = {min: 0.0, max: 60.0};
 Map.addLayer(composite, nighttimeVis, layerName);
};

var button = ui.Button({
 label: 'Click to Load Image',
 onClick: loadImage,
 });
Map.add(button);
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F02c_Using_UI_Elements_(exercise))



```
// Instead of manually creating a list of years like before
// we can create a list of years using ee.List.sequence()
var years = ee.List.sequence(2014, 2020)

// Convert them to strings using format() function
var yearStrings = years.map(function(year){
 return ee.Number(year).format('%04d')
})
print(yearStrings);

// Convert the server-side object to client-side using
// evaluate() and use it with ui.Select()
yearStrings.evaluate(function(yearList) {
 var yearSelector = ui.Select({
 items: yearList,
 value: '2014',
 placeholder: 'Select a year',
 })
 Map.add(yearSelector)
});

// Exercise

// Create another dropdown with months from 1 to 12
// and add it to the map.
```




## 03. 构建和发布应用程序

Building a web mapping application typically requires the skills of a full stack developer and are out of reach for most analysts and scientists. But the Earth Engine User Interface API makes this process much more accessible by providing ready-to-use widgets and free cloud hosting to allow anyone to publish an app with just a few lines of code. The main container object is the `ui.Panel()` which can contain different types of widgets.


The code below shows how to build an app called [Night Lights Explorer](https://santhosh-m.users.earthengine.app/view/night-lights-explorer) that allows anyone to pick a year/month and load the *VIIRS Nighttime Day/Night Band Composite* for the selected month. Copy/paste the code below to your Code Editor and click *Run*.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app1.png)


You will see a panel on the right-hand side with 2 drop-down boxes and a button. These are User Interface (UI) widgets provided by the Earth Engine API that allows the user to interactively select the values. You can select the values for *year* and *month* and click *Load* button to see the image for the selected month.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F03b_Building_an_App_with_UI_Widgets_(complete))



```
// Panels are the main container widgets
var mainPanel = ui.Panel({
 style: {width: '300px'}
});


var title = ui.Label({
 value: 'Night Lights Explorer',
 style: {'fontSize': '24px'}
});
// You can add widgets to the panel
mainPanel.add(title)

// You can even add panels to other panels
var dropdownPanel = ui.Panel({
 layout: ui.Panel.Layout.flow('horizontal'),
});
mainPanel.add(dropdownPanel);

var yearSelector = ui.Select({
 placeholder: 'please wait..',
 })

var monthSelector = ui.Select({
 placeholder: 'please wait..',
 })

var button = ui.Button('Load')
dropdownPanel.add(yearSelector)
dropdownPanel.add(monthSelector)
dropdownPanel.add(button)


// Let's add a dropdown with the years
var years = ee.List.sequence(2014, 2020)
var months = ee.List.sequence(1, 12)

// Dropdown items need to be strings
var yearStrings = years.map(function(year){
 return ee.Number(year).format('%04d')
})
var monthStrings = months.map(function(month){
 return ee.Number(month).format('%02d')
})

// Evaluate the results and populate the dropdown
yearStrings.evaluate(function(yearList) {
 yearSelector.items().reset(yearList)
 yearSelector.setPlaceholder('select a year')
})

monthStrings.evaluate(function(monthList) {
 monthSelector.items().reset(monthList)
 monthSelector.setPlaceholder('select a month')

})

// Define a function that triggers when any value is changed
var loadComposite = function() {
 var col = ee.ImageCollection("NOAA/VIIRS/DNB/MONTHLY\_V1/VCMSLCFG");
 var year = yearSelector.getValue()
 var month = monthSelector.getValue()
 var startDate = ee.Date.fromYMD(
 ee.Number.parse(year), ee.Number.parse(month), 1)
 var endDate = startDate.advance(1, 'month')
 var filtered = col.filter(ee.Filter.date(startDate, endDate))

 var image = ee.Image(filtered.first()).select('avg\_rad')
 var nighttimeVis = {min: 0.0, max: 60.0}
 var layerName = 'Night Lights ' + year + '-' + month
 Map.addLayer(image, nighttimeVis, layerName)
}
button.onClick(loadComposite)

Map.setCenter(76.43, 12.41, 8)
ui.root.add(mainPanel);
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F03c_Building_an_App_with_UI_Widgets_(exercise))



```
// Exercise
// Add a button called 'Reset'
// Clicking the button should remove all loaded layers

// Hint: Use Map.clear() for removing the layers
```




## 04. 发布应用程序

We will now publish this app. Click on the *Apps* button.



![App with UI Elements](https://courses.spatialthoughts.com/images/end_to_end_gee/app2.png)

App with UI Elements




In the *Manage Apps* window, click *New App*.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app3.png)


Enter the name of your app. The app will be hosted on Google Cloud, so you will need to create and link a Google Cloud project with the app. If you don’t have a Google Cloud account, you can click the *Not Yet* button to create a new project.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app4.png)


When prompted to *Choose a Cloud Project for your apps*, you can select *Create a new Cloud Project* and enter an unique id and click *Select*.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app5.png)


You may get an error asking you to accept the terms of service. Click the *Cloud Terms of Service* link and follow the instructions. Once done, click *OK*.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app6.png)


Back in the *Publish New App* dialog, leave all other settings to default and click *Publish*.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app7.png)


The app will be hosted on Google Cloud and you can access it by clicking on the *App Name* of your app in the *Manage Apps* dialog.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app8.png)


You will see your Earth Engine powered app running in the browser. Anyone can access and interact with the app by just visiting the App URL.



> 
> The app publishing process takes a few minutes. So if you get an error that your app is not yet ready, check back in a few minutes.
> 
> 
> 


[Explore The App ↗](https://ujavalgandhi.users.earthengine.app/view/night-lights-explorer)


![](https://courses.spatialthoughts.com/images/end_to_end_gee/app9.png)



### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F04c_Publishing_the_App_(exercise))



```
// Panels are the main container widgets
var mainPanel = ui.Panel({
 style: {width: '300px'}
});


var title = ui.Label({
 value: 'Night Lights Explorer',
 style: {'fontSize': '24px'}
});
// You can add widgets to the panel
mainPanel.add(title)

// You can even add panels to other panels
var dropdownPanel = ui.Panel({
 layout: ui.Panel.Layout.flow('horizontal'),
});
mainPanel.add(dropdownPanel);

var yearSelector = ui.Select({
 placeholder: 'please wait..',
 })

var monthSelector = ui.Select({
 placeholder: 'please wait..',
 })

var button = ui.Button('Load')
dropdownPanel.add(yearSelector)
dropdownPanel.add(monthSelector)
dropdownPanel.add(button)


// Let's add a dropdown with the years
var years = ee.List.sequence(2014, 2020)
var months = ee.List.sequence(1, 12)

// Dropdown items need to be strings
var yearStrings = years.map(function(year){
 return ee.Number(year).format('%04d')
})
var monthStrings = months.map(function(month){
 return ee.Number(month).format('%02d')
})

// Evaluate the results and populate the dropdown
yearStrings.evaluate(function(yearList) {
 yearSelector.items().reset(yearList)
 yearSelector.setPlaceholder('select a year')
})

monthStrings.evaluate(function(monthList) {
 monthSelector.items().reset(monthList)
 monthSelector.setPlaceholder('select a month')

})

// Define a function that triggers when any value is changed
var loadComposite = function() {
 var col = ee.ImageCollection("NOAA/VIIRS/DNB/MONTHLY\_V1/VCMSLCFG");
 var year = yearSelector.getValue()
 var month = monthSelector.getValue()
 var startDate = ee.Date.fromYMD(
 ee.Number.parse(year), ee.Number.parse(month), 1)
 var endDate = startDate.advance(1, 'month')
 var filtered = col.filter(ee.Filter.date(startDate, endDate))

 var image = ee.Image(filtered.first()).select('avg\_rad')
 var nighttimeVis = {min: 0.0, max: 60.0}
 var layerName = 'Night Lights ' + year + '-' + month
 Map.addLayer(image, nighttimeVis, layerName)
}
button.onClick(loadComposite)

// Exercise
// Set the map center to your area of interst
// Replace the author label with your name
// Publish the app.
Map.setCenter(76.43, 12.41, 8)
var authorLabel = ui.Label('App by: Ujaval Gandhi');
mainPanel.add(authorLabel);

ui.root.add(mainPanel);
```




## 05. 创建一个拆分面板应用程序

Another useful widget that can be used in Apps is `ui.SplitPanel()`. This allows you to create an app that can display 2 different images of the same region that can be explored interactively by swiping. Here we create an app to explore the [ESA WorldCover 10m](https://developers.google.com/earth-engine/datasets/catalog/ESA_WorldCover_v100) global classification dataset.


On the left-hand panel, we will load a Sentinel-2 composite for the year 2020. On the right-hand panel, we will load the 11-class landcover classification of the same region.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F05b_Split_Panel_App_(complete))



```
var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");
var selected = admin2
 .filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))
 .filter(ee.Filter.eq('ADM2\_NAME', 'Bangalore Urban'))
var geometry = selected.geometry();
Map.centerObject(geometry)

var s2 = ee.ImageCollection("COPERNICUS/S2");

// Write a function for Cloud masking
var maskS2clouds = function(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}

// Write a function to scale the bands
var scaleImage = function(image) {
 return image
 .multiply(0.0001)
 .copyProperties(image, ["system:time\_start"])
}

var filtered = s2
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 .map(scaleImage);
 
// Create a median composite for 2020
var composite = filtered.median();

// Load ESA WorldCover 2020 Classification
var worldcover = ee.ImageCollection("ESA/WorldCover/v100")
var filtered = worldcover
 .filter(ee.Filter.date('2020-01-01', '2021-01-01'));
var classification = ee.Image(filtered.first());

// Create a Split Panel App

// Set a center and zoom level.
var center = {lon: 77.58, lat: 12.97, zoom: 12};

// Create two maps.
var leftMap = ui.Map(center);
var rightMap = ui.Map(center);

// Link them together.
var linker = new ui.Map.Linker([leftMap, rightMap]);

// Create a split panel with the two maps.
var splitPanel = ui.SplitPanel({
 firstPanel: leftMap,
 secondPanel: rightMap,
 orientation: 'horizontal',
 wipe: true
});

// Remove the default map from the root panel.
ui.root.clear();

// Add our split panel to the root panel.
ui.root.add(splitPanel);

// Add the layers to the maps
// Composite goes to the leftMap
var rgbVis = {min: 0.0, max: 0.3, bands: ['B4', 'B3', 'B2']};
leftMap.addLayer(composite.clip(geometry), rgbVis, '2020 Composite');

// Classification foes to the rightMap
rightMap.addLayer(classification.clip(geometry), {}, 'WorldCover Classification');
```


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A05-Earth-Engine-Apps%2F05c_Split_Panel_App_(exercise))



```
var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");
var selected = admin2
 .filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))
 .filter(ee.Filter.eq('ADM2\_NAME', 'Bangalore Urban'))
var geometry = selected.geometry();
Map.centerObject(geometry)

var s2 = ee.ImageCollection("COPERNICUS/S2");

// Write a function for Cloud masking
var maskS2clouds = function(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}

// Write a function to scale the bands
var scaleImage = function(image) {
 return image
 .multiply(0.0001)
 .copyProperties(image, ["system:time\_start"])
}

var filtered = s2
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 .map(scaleImage);
 
// Create a median composite for 2020
var composite = filtered.median();

// Load ESA WorldCover 2020 Classification
var worldcover = ee.ImageCollection("ESA/WorldCover/v100")
var filtered = worldcover
 .filter(ee.Filter.date('2020-01-01', '2021-01-01'));
var classification = ee.Image(filtered.first());

// Create a Split Panel App

// Set a center and zoom level.
var center = {lon: 77.58, lat: 12.97, zoom: 12};

// Create two maps.
var leftMap = ui.Map(center);
var rightMap = ui.Map(center);

// Link them together.
var linker = new ui.Map.Linker([leftMap, rightMap]);

// Create a split panel with the two maps.
var splitPanel = ui.SplitPanel({
 firstPanel: leftMap,
 secondPanel: rightMap,
 orientation: 'horizontal',
 wipe: true
});

// Remove the default map from the root panel.
ui.root.clear();

// Add our split panel to the root panel.
ui.root.add(splitPanel);

// Add the layers to the maps
// Composite goes to the leftMap
var rgbVis = {min: 0.0, max: 0.3, bands: ['B4', 'B3', 'B2']};
leftMap.addLayer(composite.clip(geometry), rgbVis, '2020 Composite');

// Classification foes to the rightMap
rightMap.addLayer(classification.clip(geometry), {}, 'WorldCover Classification');

// Adding a Legend
// The following code creates a legend with class names and colors

// Create the panel for the legend items.
var legend = ui.Panel({
 style: {
 position: 'middle-right',
 padding: '8px 15px'
 }
});

// Create and add the legend title.
var legendTitle = ui.Label({
 value: 'ESA WorldCover Classes',
 style: {
 fontWeight: 'bold',
 fontSize: '18px',
 margin: '0 0 4px 0',
 padding: '0'
 }
});
legend.add(legendTitle);

var loading = ui.Label('Loading legend...', {margin: '2px 0 4px 0'});
legend.add(loading);

// Creates and styles 1 row of the legend.
var makeRow = function(color, name) {
 // Create the label that is actually the colored box.
 var colorBox = ui.Label({
 style: {
 backgroundColor: '#' + color,
 // Use padding to give the box height and width.
 padding: '8px',
 margin: '0 0 4px 0'
 }
 });

 // Create the label filled with the description text.
 var description = ui.Label({
 value: name,
 style: {margin: '0 0 4px 6px'}
 });

 return ui.Panel({
 widgets: [colorBox, description],
 layout: ui.Panel.Layout.Flow('horizontal')
 });
};

var BAND\_NAME = 'Map';
// Get the list of palette colors and class names from the image.
classification.toDictionary().select([BAND\_NAME + ".\*"]).evaluate(function(result) {
 var palette = result[BAND\_NAME + "\_class\_palette"];
 var names = result[BAND\_NAME + "\_class\_names"];
 loading.style().set('shown', false);

 for (var i = 0; i < names.length; i++) {
 legend.add(makeRow(palette[i], names[i]));
 }
});

// Print the panel containing the legend
print(legend);

// Exercise

// The 'legend' panel contains the legend for the classification
// Add the legend to the map below

// Hint: UI Widgets can only be shown once in the app. Remove the
// print statement before adding the legend to the map.
// Hint: Load the legend in the right-hand side map.
```





# 模块 6: Google Earth Engine Python API



## GEE Python API 简介


Till this point in the course, we have used the Earth Engine Javascript API for all our analysis. Earth Engine also provides a Python API. If you are a Python programmer, you may prefer to use the Python API to integrate Earth Engine in your spatial analysis workflow. There are many options for running Python code that uses the Google Earth Engine API. We will use the following two methods in this course.


[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/python_api.png)](https://docs.google.com/presentation/d/1hPVRnxp2Vp1VHXBtu36SH_UtEOjPz70KcDV-zGIin3U/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/1hPVRnxp2Vp1VHXBtu36SH_UtEOjPz70KcDV-zGIin3U/edit?usp=sharing)



### Google Colab


An easy way to start using the Google Earth Engine Python API is via [Google Colab](https://colab.research.google.com/). Google Colaboratory provides a hosted environment to run Python notebooks without having to install Python locally. It also comes pre-installed with many useful packages - including the Google Earth Engine Python API. You can simply visit <https://colab.research.google.com/> and start a new notebook.




### 本地开发环境

An advantage of Python API is that you can use it in your own development environment - so you get a lot more flexibility to automate as well as combine other analysis and visualization libraries with Earth Engine. This requires installing Python and the Earth Engine Python API on your machine or server. You also need to do a one-time authentication and save the token on the machine. The preferred method for installing the Earth Engine Python API is via Anaconda. Please follow our [Google Earth Engine Python API Installation Guide](install-gee-python-api.html) for step-by-step instructions.





## 01. Python API 语法


[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/01_python_api_syntax.ipynb)


Coming from the programming in Earth Engine through the Code Editor, you will need to slightly adapt your scripts to be able to run in Python. For the bulk of your code, you will be using Earth Engine API’s server-side objects and functions - which will be exactly the same in Python. You only need to make a few syntactical changes.


[Here’s the full list](https://developers.google.com/earth-engine/python_install#syntax) of differences.



#### 初始化


First of all, you need to run the following cells to initialize the API and authorize your account. You will be prompted to sign-in to the account and allow access to *View and Manage your Earth Engine data*. Once you approve, you will get an a verification code that needs to be entered at the prompt. This step needs to be done just once per session.



```
import ee
```


```
ee.Authenticate()
```


```
ee.Initialize()
```



#### 变量


Python 代码并不使用 ‘var’ 关键词

javascript 代码：



```
var city = 'San Fransico'
var state = 'California'
print(city, state)

var population = 881549
print(population)
```


```
city = 'San Fransico'
state = 'California'
print(city, state)

population = 881549
print(population)
```



#### Earth Engine 对象

你可以通过相同的方式，使用 `ee` 函数创建 Earth Engine 对象。


```
s2 = ee.ImageCollection('COPERNICUS/S2')
geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]])
```



#### Line Continuation


Python doesn’t use a semi-colon for line ending. To indicate line-continuation you need to use the \ character


javascript 代码：



```
var s2 = ee.ImageCollection('COPERNICUS/S2');
var filtered = s2.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-02-01', '2019-03-01'))
  .filter(ee.Filter.bounds(geometry));
```


```
filtered = s2 \
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30)) \
 .filter(ee.Filter.date('2019-02-01', '2019-03-01')) \
 .filter(ee.Filter.bounds(geometry))
```



#### 函数


Instead of the `function` keyword, Python uses the `def` keyword. Also the in-line functions are defined using `lambda` anonymous functions.


In the example below, also now the `and` operator - which is capitalized as `And` in Python version to avoid conflict with the built-in `and` operator. The same applies to `Or` and `Not` operators. `true`, `false`, `null` in Python are also spelled as `True`, `False` and `None`.


javascript 代码：



```
function maskS2clouds(image) {
  var qa = image.select('QA60')
  var cloudBitMask = 1 << 10;
  var cirrusBitMask = 1 << 11;
  var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
             qa.bitwiseAnd(cirrusBitMask).eq(0))
  return image.updateMask(mask)//.divide(10000)
      .select("B.*")
      .copyProperties(image, ["system:time_start"])
}

function addNDVI(image) {
  var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
  return image.addBands(ndvi);
}
```


```
def maskS2clouds(image):
 qa = image.select('QA60')
 cloudBitMask = 1 << 10
 cirrusBitMask = 1 << 11
 mask = qa.bitwiseAnd(cloudBitMask).eq(0).And(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask) \
 .select("B.\*") \
 .copyProperties(image, ["system:time\_start"])

def addNDVI(image):
 ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi')
 return image.addBands(ndvi)

withNdvi = filtered \
 .map(maskS2clouds) \
 .map(addNDVI)
```



#### 函数参数

Named arguments to Earth Engine functions need to be in quotes. Also when passing the named arguments as a dictionary, it needs to be passed using the `**` keyword.


javascript 代码：



```
var composite = withNdvi.median();
var ndvi = composite.select('ndvi');

var stats = ndvi.reduceRegion({
    reducer: ee.Reducer.mean(),
    geometry: geometry,
    scale: 10,
    maxPixels: 1e10
})    
```


```
composite = withNdvi.median()
ndvi = composite.select('ndvi')

stats = ndvi.reduceRegion(\*\*{
 'reducer': ee.Reducer.mean(),
 'geometry': geometry,
 'scale': 10,
 'maxPixels': 1e10
 })
```



#### 打印值

The `print()` function syntax is the same. But you must remember that in the Code Editor when you cann `print`, the value of the server object is fetched and then printed. You must do that explicitely by calling `getInfo()` on any server-side object.


javascript 代码：



```
print(stats.get('ndvi')
```


```
print(stats.get('ndvi').getInfo())
```



#### 内联函数

The syntax for defining in-line functions is also slightly different. You need to use the `lambda` keyword.


javascript 代码：



```
var myList = ee.List.sequence(1, 10);
var newList = myList.map(function(number) {
    return ee.Number(number).pow(2);
print(newList);
```


```
myList = ee.List.sequence(1, 10)
newList = myList.map(lambda number: ee.Number(number).pow(2))
print(newList.getInfo())
```



### 练习


Take the Javascript code snippet below and write the equiavalent Python code in the cell below.


* **Hint1**: Chaining of filters require the use of line continuation character `\`
* **Hint2**: Printing of server-side objects requires calling `.getInfo()` on the object


The correct code should print the value **30**.




---



```
var geometry = ee.Geometry.Point([77.60412933051538, 12.952912912328241]);

var s2 = ee.ImageCollection('COPERNICUS/S2');

var filtered = s2.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(geometry));
  
print(filtered.size());
```



---



```
import ee
ee.Authenticate()
ee.Initialize()
```




## 02. Javascript 代码到 Python 到自动转换


[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/02_automatic_conversion_of_scripts.ipynb)



![Interactive leaflet map created by geemap](https://courses.spatialthoughts.com/images/end_to_end_gee/automatic_conversion.png)

Interactive leaflet map created by geemap




[geemap](https://github.com/giswqs/geemap) is an open-source Python package that comes with many helpful features that help you use Earth Engine effectively in Python.


It comes with a function that can help you translate your javascript earth engine code to Python automatically.


Google Colab doesn’t come pre-installed with the package, so we install it via pip.



```
try:
 import geemap
except ModuleNotFoundError:
 if 'google.colab' in str(get\_ipython()):
 print('geemap not found, installing via pip in Google Colab...')
 !pip install geemap --quiet
 import geemap
 else:
 print('geemap not found, please install via conda in your environment')
```

The automatic conversion of code is done by calling the `geemap.js_snippet_to_py()` function. We first create a string with the javascript code.



```
javascript\_code = """
var geometry = ee.Geometry.Point([107.61303468448624, 12.130969369851766]);
Map.centerObject(geometry, 12)
var s2 = ee.ImageCollection("COPERNICUS/S2")
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}
 
var filtered = s2
 .filter(ee.Filter.date('2019-01-01', '2019-12-31'))
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 

// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B5', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

var withNdvi = filtered.map(addNDVI);

var composite = withNdvi.median()
palette = [
 'FFFFFF', 'CE7E45', 'DF923D', 'F1B555', 'FCD163', '99B718',
 '74A901', '66A000', '529400', '3E8601', '207401', '056201',
 '004C00', '023B01', '012E01', '011D01', '011301'];

ndviVis = {min:0, max:0.5, palette: palette }
Map.addLayer(withNdvi.select('ndvi'), ndviVis, 'NDVI Composite')

"""
```


```
lines = geemap.js\_snippet\_to\_py(
 javascript\_code, add\_new\_cell=False,
 import\_ee=True, import\_geemap=True, show\_map=True)
for line in lines:
 print(line.rstrip())
```

The automatic conversion works great. Review it and paste it to the cell below.



```
import ee
import geemap
Map = geemap.Map()

geometry = ee.Geometry.Point([107.61303468448624, 12.130969369851766])
Map.centerObject(geometry, 12)
s2 = ee.ImageCollection("COPERNICUS/S2")
rgbVis = {
 'min': 0.0,
 'max': 3000,
 'bands': ['B4', 'B3', 'B2'],
}

# Write a function for Cloud masking
def maskS2clouds(image):
 qa = image.select('QA60')
 cloudBitMask = 1 << 10
 cirrusBitMask = 1 << 11
 mask = qa.bitwiseAnd(cloudBitMask).eq(0).And(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask) \
 .select("B.\*") \
 .copyProperties(image, ["system:time\_start"])

filtered = s2 \
 .filter(ee.Filter.date('2019-01-01', '2019-12-31')) \
 .filter(ee.Filter.bounds(geometry)) \
 .map(maskS2clouds)

# Write a function that computes NDVI for an image and adds it as a band
def addNDVI(image):
 ndvi = image.normalizedDifference(['B5', 'B4']).rename('ndvi')
 return image.addBands(ndvi)

withNdvi = filtered.map(addNDVI)

composite = withNdvi.median()
palette = [
 'FFFFFF', 'CE7E45', 'DF923D', 'F1B555', 'FCD163', '99B718',
 '74A901', '66A000', '529400', '3E8601', '207401', '056201',
 '004C00', '023B01', '012E01', '011D01', '011301']

ndviVis = {'min':0, 'max':0.5, 'palette': palette }
Map.addLayer(withNdvi.select('ndvi'), ndviVis, 'NDVI Composite')
Map
```


### 练习


Take the Javascript code snippet below and use `geemap` to automatically convert it to Python.




---



```
var admin2 = ee.FeatureCollection("FAO/GAUL_SIMPLIFIED_500m/2015/level2");

var karnataka = admin2.filter(ee.Filter.eq('ADM1_NAME', 'Karnataka'))

var visParams = {color: 'red'}
Map.centerObject(karnataka)
Map.addLayer(karnataka, visParams, 'Karnataka Districts')
```



---





## 03. 批量导出

[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/03_export_a_collection.ipynb)


One of the most commonly asked questions by Earth Engine users is - *How do I download all images in a collection*? The Earth Engine Python API comes with a `ee.batch` module that allows you to launch batch exports and manage tasks. The recommended way to do batch exports like this is to use the Python API’s `ee.batch.Export` functions and use a Python for-loop to iterate and export each image. The `ee.batch` module also gives you ability to control *Tasks* - allowing you to automate exports.



```
import ee
```


```
ee.Authenticate()
```


```
ee.Initialize()
```


#### 创建一个 Collection



```
geometry = ee.Geometry.Point([107.61303468448624, 12.130969369851766])
s2 = ee.ImageCollection("COPERNICUS/S2")
rgbVis = {
 'min': 0.0,
 'max': 3000,
 'bands': ['B4', 'B3', 'B2'],
}

# Write a function for Cloud masking
def maskS2clouds(image):
 qa = image.select('QA60')
 cloudBitMask = 1 << 10
 cirrusBitMask = 1 << 11
 mask = qa.bitwiseAnd(cloudBitMask).eq(0).And(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask) \
 .select("B.\*") \
 .copyProperties(image, ["system:time\_start"])

filtered = s2 \
 .filter(ee.Filter.date('2019-01-01', '2020-01-01')) \
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30)) \
 .filter(ee.Filter.bounds(geometry)) \
 .map(maskS2clouds)

# Write a function that computes NDVI for an image and adds it as a band
def addNDVI(image):
 ndvi = image.normalizedDifference(['B5', 'B4']).rename('ndvi')
 return image.addBands(ndvi)

withNdvi = filtered.map(addNDVI)
```



#### 导出所有图像

Exports are done via the `ee.batch` module. A key difference between javascript and Python version is that the `region` parameter needs to be supplied with actual geometry coordinates.



```
image\_ids = withNdvi.aggregate\_array('system:index').getInfo()
print('Total images: ', len(image\_ids))
```


```
# Export with 100m resolution for this demo
for i, image\_id in enumerate(image\_ids):
 image = ee.Image(withNdvi.filter(ee.Filter.eq('system:index', image\_id)).first())
 task = ee.batch.Export.image.toDrive(\*\*{
 'image': image.select('ndvi'),
 'description': 'Image Export {}'.format(i+1),
 'fileNamePrefix': image.id().getInfo(),
 'folder':'earthengine',
 'scale': 100,
 'region': image.geometry().bounds().getInfo()['coordinates'],
 'maxPixels': 1e10
 })
 task.start()
 print('Started Task: ', i+1)
```



#### 管理 Running/Waiting 任务


You can manage tasks as well. Get a list of tasks and get state information on them



```
tasks = ee.batch.Task.list()
for task in tasks:
 task\_id = task.status()['id']
 task\_state = task.status()['state']
 print(task\_id, task\_state)
```

你也可以取消任务


```
tasks = ee.batch.Task.list()
for task in tasks:
 task\_id = task.status()['id']
 task\_state = task.status()['state']
 if task\_state == 'RUNNING' or task\_state == 'READY':
 task.cancel()
 print('Task {} canceled'.format(task\_id))
 else:
 print('Task {} state is {}'.format(task\_id, task\_state))
```



### 练习


The code below uses the TerraClimate data and creates an ImageCollection with 12 monthly images of maximum temperature. It also extract the geometry for Australia from the LSIB collection. Add the code to start an export task for each image in the collection for australia.


* **Hint1**: TerraClimate images have a scale of 4638.3m
* **Hint2**: You need to export the image contained in the clippedImage variable



```
import ee

lsib = ee.FeatureCollection('USDOS/LSIB\_SIMPLE/2017')
australia = lsib.filter(ee.Filter.eq('country\_na', 'Australia'))
geometry = australia.geometry()

terraclimate = ee.ImageCollection('IDAHO\_EPSCOR/TERRACLIMATE')
tmax = terraclimate.select('tmmx')

def scale(image):
 return image.multiply(0.1) \
 .copyProperties(image,['system:time\_start'])

tmaxScaled = tmax.map(scale)

filtered = tmaxScaled \
 .filter(ee.Filter.date('2020-01-01', '2021-01-01')) \
 .filter(ee.Filter.bounds(geometry))

image\_ids = filtered.aggregate\_array('system:index').getInfo()
print('Total images: ', len(image\_ids))
```

Replace the comments with your code.



```
for i, image\_id in enumerate(image\_ids):
 exportImage = ee.Image(filtered.filter(ee.Filter.eq('system:index', image\_id)).first())
 # Clip the image to the region geometry
 clippedImage = exportImage.clip(geometry)
 
 ## Create the export task using ee.batch.Export.image.toDrive()
 
 ## Start the task
```


![Launching multiple tasks using the  Python API](https://courses.spatialthoughts.com/images/end_to_end_gee/exporting_a_collection.png)

Launching multiple tasks using the Python API







## 04. 使用 Python 创建图像


[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/04_creating_charts.ipynb)


The Google Earth Engine Python API does not come with a charting module. But you can use third-party modules to create interactive charts. You may also convert the Earth Engine objects to a Pandas dataframe and plot it using Python libraries like Matplotlib


This notebook shows how to use the `geemap` package to create a Time-Series Chart from a ImageCollection.

参考：

* geemap [Chart module](https://geemap.org/chart/)
* geemap [Example notebook](https://geemap.org/notebooks/63_charts/)



```
import ee
```


```
try:
 import geemap
except ModuleNotFoundError:
 if 'google.colab' in str(get\_ipython()):
 print('geemap not found, installing via pip in Google Colab...')
 !pip install geemap --quiet
 import geemap
 else:
 print('geemap not found, please install via conda in your environment')
```


```
ee.Authenticate()
```


```
ee.Initialize()
```

Load the TerraClimate collection and select the ‘tmmx’ band.



```
terraclimate = ee.ImageCollection("IDAHO\_EPSCOR/TERRACLIMATE")
tmax = terraclimate.select('tmmx')
```

Define a point location for the chart.



```
geometry = ee.Geometry.Point([77.57738128916243, 12.964758918835752])
```

Scale the band values so they are in Degree Celcius.



```
def scale\_image(image):
 return ee.Image(image).multiply(0.1)\
 .copyProperties(image, ['system:time\_start'])

tmaxScaled = tmax.map(scale\_image)
```

Filter the collection.



```
filtered = tmaxScaled.filter(ee.Filter.date('2019-01-01', '2020-01-01')) \
 .filter(ee.Filter.bounds(geometry))
```

To chart an image series in Python, we must first extract the values from each image and create a FeatureCollection.



```
def extract\_data(image):
 stats = image.reduceRegion(\*\*{ 
 'reducer':ee.Reducer.mean(),
 'geometry':geometry,
 'scale':5000
 })
 properties = {
 'month': image.get('system:index'),
 'tmmx': stats.get('tmmx')
 }
 return ee.Feature(None, properties)

data = ee.FeatureCollection(filtered.map(extract\_data))
```


```
print(data.first().getInfo())
```


### 使用 geemap 创建交互式图表



```
from geemap import chart
```


```
options = {
 'title': 'Max Monthly Temperature at Bangalore', 
 'legend\_location': 'top-right',
 'height': '500px',
 'ylabel': 'Temperature (C)',
 'xlabel': 'Date',
 'colors': ['blue']
}
```


```
chart.feature\_byFeature(data, 'month', ['tmmx'], \*\*options)
```



### 使用 Matplotlib 创建图表


We can convert a FeatureCollection to a DataFrame using `geemap` helper function `ee_to_pandas`.



```
import geemap
df = geemap.ee\_to\_pandas(data)
```


```
df
```

Now we have a regular Pandas dataframe that can be plotted with `matplotlib`.



```
%matplotlib inline
import matplotlib.pyplot as plt
```


```
fig, ax = plt.subplots()
fig.set\_size\_inches(20,10)


df.plot(ax=ax,
 title='Max Monthly Temperature at Bangalore',
 x='month',
 ylabel='Temperature (C)',
 kind='line')
plt.tight\_layout()
```



### 练习


Customize the above chart by plotting it as a Line Chart in red color.


* **Hint1**: Use `kind='line'` along with a `color` option.





## 05. 自动下载

Another common use of the GEE Python API is to automate data processing and export. You can create a Python script that can be called from a server or launched on a schedule using tools such as [Windows Scheduler](https://medium.com/@roddyjaques/how-to-run-anaconda-programs-with-a-bat-file-5f6dd7675508) or [crontab](https://donny-son.github.io/posts/cronjob-with-conda/).


This script below provides a complete example of automating a download using Google Earth Engine API. It uses the Google Earth Engine API to compute the average soil moisture for the past 2 weeks over all districts in a state. The result is then downloaded as a JSON file and saved locally.



> 
> Make sure you have completed the [one-time authentication flow](install-gee-python-api.html#authentication) before running the script.
> 
> 
> 


Follow the steps below to create a script to download data from GEE.


1. Create a new file named `download_data.py` with the content shown below.



```
import datetime
import ee
import csv
import os

ee.Initialize()

# Get current date and convert to milliseconds 
end\_date = ee.Date(datetime.datetime.now().timestamp()\*1000)
start\_date = end\_date.advance(-2, 'week')

date\_string = end\_date.format('YYYY\_MM\_dd')
filename = 'ssm\_{}.csv'.format(date\_string.getInfo())

# Saving to current directory. You can change the path to appropriate location
output\_path = os.path.join(filename)

# Datasets
soilmoisture = ee.ImageCollection("NASA\_USDA/HSL/SMAP10KM\_soil\_moisture")
admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2")

# Filter to a state
karnataka = admin2.filter(ee.Filter.eq('ADM1\_NAME', 'Karnataka'))

# Select the ssm band
ssm = soilmoisture.select('ssm')

filtered = ssm .filter(ee.Filter.date(start\_date, end\_date))

mean = filtered.mean()

stats = mean.reduceRegions(\*\*{
 'collection': karnataka,
 'reducer': ee.Reducer.mean().setOutputs(['meanssm']),
 'scale': 10000,
 'crs': 'EPSG:32643'
 })

# Select columns to keep and remove geometry to make the result lightweight
# Change column names to match your uploaded shapefile
columns = ['ADM2\_NAME', 'meanssm']
exportCollection = stats.select(\*\*{
 'propertySelectors': columns,
 'retainGeometry': False})

features = exportCollection.getInfo()['features']

data = []

for f in features:
 data.append(f['properties'])

field\_names = ['ADM2\_NAME', 'meanssm']

with open(output\_path, 'w') as csvfile:
 writer = csv.DictWriter(csvfile, fieldnames = field\_names)
 writer.writeheader()
 writer.writerows(data)
 print('Success: File written at', output\_path)
```

2. From the terminal, navigate to the directory where you have created the file and type the command below to run the script.



```
python download_data.py
```

![](https://courses.spatialthoughts.com/images/end_to_end_gee/download2.png)


3. The script will download the data from GEE and save a file to your current directory.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/download3.png)






# 补充


This section contains useful scripts and code snippets that can be adapted for your projects.



## 高级有监督分类技术


### 超参数调优

A recommended best practice for improving the accuracy of your machine learning model is to tune different parameters. For example, when using the `ee.Classifier.smileRandomForest()` classifier, we must specify the *Number of Trees*. We know that higher number of trees result in more computation requirement, but it doesn’t necessarily result in better results. Instead of guessing, we programmatically try a range of values and choose the smallest value possible that results in the highest accuracy.



![Supervised Classification Output](https://courses.spatialthoughts.com/images/end_to_end_gee/hyperparameter_tuning.png)

Supervised Classification Output




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FHyperparameter_Tuning)



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_gcps");
var alos = ee.Image("JAXA/ALOS/AW3D30/V2\_2");


var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
// Function to remove cloud and snow pixels from Sentinel-2 SR image

function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(10);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 10% or cloud shadow classification
 var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask);
}


var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .map(maskCloudAndShadowsSR)
 .select('B.\*')

var composite = filtered.median().clip(boundary) 

var visParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 3000, gamma: 1.2};
Map.centerObject(boundary)
Map.addLayer(composite, visParams, 'RGB');

var addIndices = function(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
 var bsi = image.expression(
 '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
 'X': image.select('B11'), //swir1
 'Y': image.select('B4'), //red
 'A': image.select('B8'), // nir
 'B': image.select('B2'), // blue
 }).rename('bsi');
 return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

var composite = addIndices(composite);


// Calculate Slope and Elevation
var elev = alos.select('AVE\_DSM').rename('elev');
var slope = ee.Terrain.slope(alos.select('AVE\_DSM')).rename('slope');

var composite = composite.addBands(elev).addBands(slope);



// Normalize the image 

// Machine learning algorithms work best on images when all features have
// the same range

// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function normalize(image){
 var bandNames = image.bandNames();
 // Compute min and max of the image
 var minDict = image.reduceRegion({
 reducer: ee.Reducer.min(),
 geometry: boundary,
 scale: 20,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var maxDict = image.reduceRegion({
 reducer: ee.Reducer.max(),
 geometry: boundary,
 scale: 20,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var mins = ee.Image.constant(minDict.values(bandNames));
 var maxs = ee.Image.constant(maxDict.values(bandNames));

 var normalized = image.subtract(mins).divide(maxs.subtract(mins))
 return normalized
}

var composite = normalize(composite);
// Add a random column and split the GCPs into training and validation set
var gcp = gcp.randomColumn()

// This being a simpler classification, we take 60% points
// for validation. Normal recommended ratio is
// 70% training, 30% validation
var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));
Map.addLayer(validationGcp)
// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: trainingGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});
print(training)
// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50)
.train({
 features: training, 
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
});

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Feature Importance
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Run .explain() to see what the classifer looks like
print(classifier.explain())

// Calculate variable importance
var importance = ee.Dictionary(classifier.explain().get('importance'))

// Calculate relative importance
var sum = importance.values().reduce(ee.Reducer.sum())

var relativeImportance = importance.map(function(key, val) {
 return (ee.Number(val).multiply(100)).divide(sum)
 })
print(relativeImportance)

// Create a FeatureCollection so we can chart it
var importanceFc = ee.FeatureCollection([
 ee.Feature(null, relativeImportance)
])

var chart = ui.Chart.feature.byProperty({
 features: importanceFc
}).setOptions({
 title: 'Feature Importance',
 vAxis: {title: 'Importance'},
 hAxis: {title: 'Feature'}
 })
print(chart)

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Hyperparameter Tuning
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

var test = composite.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16
});


// Tune the numberOfTrees parameter.
var numTreesList = ee.List.sequence(10, 150, 10);

var accuracies = numTreesList.map(function(numTrees) {
 var classifier = ee.Classifier.smileRandomForest(numTrees)
 .train({
 features: training,
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
 });

 // Here we are classifying a table instead of an image
 // Classifiers work on both images and tables
 return test
 .classify(classifier)
 .errorMatrix('landcover', 'classification')
 .accuracy();
});

var chart = ui.Chart.array.values({
 array: ee.Array(accuracies),
 axis: 0,
 xLabels: numTreesList
 }).setOptions({
 title: 'Hyperparameter Tuning for the numberOfTrees Parameters',
 vAxis: {title: 'Validation Accuracy'},
 hAxis: {title: 'Number of Tress', gridlines: {count: 15}}
 });
print(chart)

// Tuning Multiple Parameters
// We can tune many parameters together using
// nested map() functions
// Let's tune 2 parameters
// numTrees and bagFraction 
var numTreesList = ee.List.sequence(10, 150, 10);
var bagFractionList = ee.List.sequence(0.1, 0.9, 0.1);

var accuracies = numTreesList.map(function(numTrees) {
 return bagFractionList.map(function(bagFraction) {
 var classifier = ee.Classifier.smileRandomForest({
 numberOfTrees: numTrees,
 bagFraction: bagFraction
 })
 .train({
 features: training,
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
 });

 // Here we are classifying a table instead of an image
 // Classifiers work on both images and tables
 var accuracy = test
 .classify(classifier)
 .errorMatrix('landcover', 'classification')
 .accuracy();
 return ee.Feature(null, {'accuracy': accuracy,
 'numberOfTrees': numTrees,
 'bagFraction': bagFraction})
 })
}).flatten()
var resultFc = ee.FeatureCollection(accuracies)

// Export the result as CSV
Export.table.toDrive({
 collection: resultFc,
 description: 'Multiple\_Parameter\_Tuning\_Results',
 folder: 'earthengine',
 fileNamePrefix: 'numtrees\_bagfraction',
 fileFormat: 'CSV'}) 
 
```



### Post-Processing Classification Results


Supervised classification results often contain salt-and-pepper noise caused by mis-classified pixels. It is usually preferable to apply some post-processing techniques to remove such noise. The following script contains the code for two popular techniques for post-processing classification results.


* Using un-supervised clustering to replacing classified value by majority value in each cluster.
* Replacing isolated pixels with surrounding value with a majority filter.



> 
> Remember that the neighborhood methods are scale-dependent so the results will change as you zoom in/out. Export the results at the desired scale to see the effect of post-processing.
> 
> 
> 


![](https://courses.spatialthoughts.com/images/end_to_end_gee/post_processing.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FPost_Processing_Classification_Results)



```
// Sentinel-2 Median Composite
var composite = ee.Image("users/ujavalgandhi/e2e/arkavathy\_2019\_composite");
Map.addLayer(composite, {min: 0, max: 0.3, bands: ['B4', 'B3', 'B2']}, 'RGB Composite');

// Raw Supervised Classification Results
var classified = ee.Image("users/ujavalgandhi/e2e/arkavathy\_final\_classification");
Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, 'Original');
Map.centerObject(classified, 10)


//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Post process by clustering
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// Cluster using Unsupervised Clustering methods
var seeds = ee.Algorithms.Image.Segmentation.seedGrid(5);

var snic = ee.Algorithms.Image.Segmentation.SNIC({
 image: composite.select('B.\*'), 
 compactness: 0,
 connectivity: 4,
 neighborhoodSize: 10,
 size: 2,
 seeds: seeds
})
var clusters = snic.select('clusters')

// Assign class to each cluster based on 'majority' voting (using ee.Reducer.mode()
var smoothed = classified.addBands(clusters);

var clusterMajority = smoothed.reduceConnectedComponents({
 reducer: ee.Reducer.mode(),
 labelBand: 'clusters'
});
Map.addLayer(clusterMajority, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']},
 'Processed using Clusters');


//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Post process by replacing isolated pixels with surrounding value
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 

// count patch sizes
var patchsize = classified.connectedPixelCount(40, false);

// run a majority filter
var filtered = classified.focal\_mode({
 radius: 10,
 kernelType: 'square',
 units: 'meters',
}); 
 
// updated image with majority filter where patch size is small
var connectedClassified = classified.where(patchsize.lt(25),filtered);
Map.addLayer(connectedClassified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']},
 'Processed using Connected Pixels');
```



### 主成分分析（PCA）

PCA is a very useful technique in improving your supervised classification results. This is a statistical technique that compresses data from a large number of bands into fewer uncorrelated bands. You can run PCA on your image and add the first few (typically 3) principal component bands to the original composite before sampling training points. In the example below, you will notice that 97% of the variance from the 13-band original image is captured in the 3-band PCA image. This sends a stronger signal to the classifier and improves accuracy by allowing it to distinguish different classes better.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/pca.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FPrincipal_Components_Analysis)



```
// Script showing how to do Principal Component Analysis on images
var composite = ee.Image("users/ujavalgandhi/e2e/arkavathy\_2019\_composite");
var boundary = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_boundary");

Map.centerObject(composite)
Map.addLayer(composite, {bands: ['B4', 'B3', 'B2'], min: 0, max: 0.3, gamma: 1.2}, 'RGB');

// Define the geometry and scale parameters
var geometry = boundary.geometry();
var scale = 20;

// Run the PCA function
var pca = PCA(composite)

// Extract the properties of the pca image
var variance = pca.toDictionary()
print('Variance of Principal Components', variance)

// As you see from the printed results, ~97% of the variance
// from the original image is captured in the first 3 principal components
// We select those and discard others
var pca = PCA(composite).select(['pc1', 'pc2', 'pc3'])

// PCA computation is expensive and can time out when displaying on the map
// Export the results and import them back
Export.image.toAsset({
 image: pca,
 description: 'Principal\_Components\_Image',
 assetId: 'users/ujavalgandhi/e2e/arkavathy\_pca',
 region: geometry,
 scale: scale,
 maxPixels: 1e10})
// Once the export finishes, import the asset and display
var pcaImported = ee.Image('users/ujavalgandhi/e2e/arkavathy\_pca')
var pcaVisParams = {bands: ['pc1', 'pc2', 'pc3'], min: -2, max: 2};

Map.addLayer(pcaImported, pcaVisParams, 'Principal Components');


//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Function to calculate Principal Components
// Code adapted from https://developers.google.com/earth-engine/guides/arrays\_eigen\_analysis
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function PCA(maskedImage){
 var image = maskedImage.unmask()
 var scale = scale;
 var region = geometry;
 var bandNames = image.bandNames();
 // Mean center the data to enable a faster covariance reducer
 // and an SD stretch of the principal components.
 var meanDict = image.reduceRegion({
 reducer: ee.Reducer.mean(),
 geometry: region,
 scale: scale,
 maxPixels: 1e13,
 tileScale: 16
 });
 var means = ee.Image.constant(meanDict.values(bandNames));
 var centered = image.subtract(means);
 // This helper function returns a list of new band names.
 var getNewBandNames = function(prefix) {
 var seq = ee.List.sequence(1, bandNames.length());
 return seq.map(function(b) {
 return ee.String(prefix).cat(ee.Number(b).int());
 });
 };
 // This function accepts mean centered imagery, a scale and
 // a region in which to perform the analysis. It returns the
 // Principal Components (PC) in the region as a new image.
 var getPrincipalComponents = function(centered, scale, region) {
 // Collapse the bands of the image into a 1D array per pixel.
 var arrays = centered.toArray();
 
 // Compute the covariance of the bands within the region.
 var covar = arrays.reduceRegion({
 reducer: ee.Reducer.centeredCovariance(),
 geometry: region,
 scale: scale,
 maxPixels: 1e13,
 tileScale: 16
 });

 // Get the 'array' covariance result and cast to an array.
 // This represents the band-to-band covariance within the region.
 var covarArray = ee.Array(covar.get('array'));

 // Perform an eigen analysis and slice apart the values and vectors.
 var eigens = covarArray.eigen();

 // This is a P-length vector of Eigenvalues.
 var eigenValues = eigens.slice(1, 0, 1);
 
 // Compute Percentage Variance of each component
 // This will allow us to decide how many components capture
 // most of the variance in the input
 var eigenValuesList = eigenValues.toList().flatten()
 var total = eigenValuesList.reduce(ee.Reducer.sum())

 var percentageVariance = eigenValuesList.map(function(item) {
 var component = eigenValuesList.indexOf(item).add(1).format('%02d')
 var variance = ee.Number(item).divide(total).multiply(100).format('%.2f')
 return ee.List([component, variance])
 })
 // Create a dictionary that will be used to set properties on final image
 var varianceDict = ee.Dictionary(percentageVariance.flatten())
 // This is a PxP matrix with eigenvectors in rows.
 var eigenVectors = eigens.slice(1, 1);
 // Convert the array image to 2D arrays for matrix computations.
 var arrayImage = arrays.toArray(1);

 // Left multiply the image array by the matrix of eigenvectors.
 var principalComponents = ee.Image(eigenVectors).matrixMultiply(arrayImage);

 // Turn the square roots of the Eigenvalues into a P-band image.
 // Call abs() to turn negative eigenvalues to positive before
 // taking the square root
 var sdImage = ee.Image(eigenValues.abs().sqrt())
 .arrayProject([0]).arrayFlatten([getNewBandNames('sd')]);

 // Turn the PCs into a P-band image, normalized by SD.
 return principalComponents
 // Throw out an an unneeded dimension, [[]] -> [].
 .arrayProject([0])
 // Make the one band array image a multi-band image, [] -> image.
 .arrayFlatten([getNewBandNames('pc')])
 // Normalize the PCs by their SDs.
 .divide(sdImage)
 .set(varianceDict);
 };
 var pcImage = getPrincipalComponents(centered, scale, region);
 return pcImage.mask(maskedImage.mask());
}
```



### Multi-temporal Composites for Crop Classification


Crop classification is a difficult problem. A useful technique that aids in clear distinction of crops is to account for crop phenology. This technique can be applied to detect a specific type of crop or distinguish crops from other forms of vegetation. You can create composite images for different periods of the cropping cycle and create a stacked image to be used for classification. This allows the classifier to learn the temporal pattern and detect pixels that exhibit similar patterns.



![Capturing Crop Phenology through Seasonal Composites](https://courses.spatialthoughts.com/images/end_to_end_gee/seasonal_composite.png)

Capturing Crop Phenology through Seasonal Composites




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FSeasonal_Composites_for_Crop_Classification)



```
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR")
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7")
var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
Map.centerObject(boundary, 11)

// Function to remove cloud pixels from Sentinel-2 SR image 
function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(10);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 10% or cloud shadow classification
 var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask).divide(10000)
 .copyProperties(image, ['system:time\_start']);
}


var filtered = s2
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .map(maskCloudAndShadowsSR)
// There are 3 distinct crop seasons in the area of interest
// Jan-March = Winter (Rabi) Crops
// April-June = Summer Crops / Harvest
// July-December = Monsoon (Kharif) Crops
var cropCalendar = ee.List([[1,3], [4,6], [7,12]])

// We create different composites for each season
var createSeasonComposites = function(months) {
 var startMonth = ee.List(months).get(0)
 var endMonth = ee.List(months).get(1)
 var monthFilter = ee.Filter.calendarRange(startMonth, endMonth, 'month')
 var seasonFiltered = filtered.filter(monthFilter)
 var composite = seasonFiltered.median()
 return composite.select('B.\*').clip(boundary)
}

var compositeList = cropCalendar.map(createSeasonComposites)

var rabi = ee.Image(compositeList.get(0))
var harvest = ee.Image(compositeList.get(1))
var kharif = ee.Image(compositeList.get(2))

var visParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 0.3, gamma: 1.2};
Map.addLayer(rabi, visParams, 'Rabi')
Map.addLayer(harvest, visParams, 'Harvest')
Map.addLayer(kharif, visParams, 'Kharif')

// Create a stacked image with composites from all seasons
// This multi-temporal image is able capture the crop phenology
// Classifier will be able to detect crop-pixels from non-crop pixels
var composite = rabi.addBands(harvest).addBands(kharif)

// This is a 36-band image
// Use this image for sampling training points for
// to train a crop classifier 
print(composite)
```



### 计算相关性

A useful technique to aid crop classification is to model the correlation between precipitation and changes in vegetation. This allows the model to capture differentiated responses to rainfall (i.e. raid-fed crops vs permanent forests). We first prepare an image collection where each image consists of 2 bands - cumulative rainfall for each month and average NDVI for the next month. This will create 11 images per year which show precipitation and 1-month lagged NDVI at each pixels. The collection is then reduced using the `ee.Reducer.pearsonsCorrelation()` which outputs a `correlation` band. Positive values will show regions where precipitation caused an increase in NDVI. Adding this band to your input image for classification will greatly aid the classifier in separating different types of vegetations.


[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FRainfall_NDVI_Correlation)



```
// Calculate Rainfall-NDVI Correlation
var geometry = ee.Geometry.Point([75.71168046831512, 13.30751919691132]);
Map.centerObject(geometry, 10)
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");

var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};


// Function to remove cloud and snow pixels from Sentinel-2 SR image
function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(5);
 var snow = snowProb.lt(5);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 5% or cloud shadow classification
 var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask);
}


// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

var s2Filtered = s2
 .filter(ee.Filter.date('2020-01-01', '2021-01-01'))
 .filter(ee.Filter.bounds(geometry))
 .map(maskCloudAndShadowsSR)
 .map(addNDVI)


var composite = s2Filtered.median()
Map.addLayer(composite, rgbVis, 'Composite') 



// Rainfall
var chirps = ee.ImageCollection("UCSB-CHG/CHIRPS/PENTAD");
var chirpsFiltered = chirps
 .filter(ee.Filter.date('2020-01-01', '2021-01-01'))


// Monsoon months
var months = ee.List.sequence(1, 11)

// Monthly Images
var byMonth = months.map(function(month) {
 var monthlyRain = chirpsFiltered
 .filter(ee.Filter.calendarRange(month, month, 'month'))
 var totalRain = monthlyRain.sum()

 var nextMonth = ee.Number(month).add(1)
 var monthly = s2Filtered
 .filter(ee.Filter.calendarRange(nextMonth, nextMonth, 'month'))
 var medianComposite = monthly.median()
 

 return totalRain.addBands(medianComposite).set({'month': month})
})
var monthlyCol = ee.ImageCollection.fromImages(byMonth)

// Display Composites
var julImage = ee.Image(monthlyCol.filter(ee.Filter.eq('month', 7)).first())
var augImage = ee.Image(monthlyCol.filter(ee.Filter.eq('month', 8)).first())
var sepImage = ee.Image(monthlyCol.filter(ee.Filter.eq('month', 9)).first())

Map.addLayer(julImage, rgbVis, 'July', false)
Map.addLayer(augImage, rgbVis, 'August', false)
Map.addLayer(sepImage, rgbVis, 'September', false)


var correlationCol = monthlyCol.select(['precipitation', 'ndvi'])

var correlation = correlationCol.reduce(ee.Reducer.pearsonsCorrelation());

var positive = correlation.select('correlation').gt(0.5)

Map.addLayer(correlation.select('correlation'), 
 {min:-1, max:1, palette: ['red', 'white', 'green']}, 'Correlation');
Map.addLayer(positive.selfMask(), 
 {palette: ['yellow']}, 'Positive Correlation', false); 
```



### Calculating Area by Class


This code snippet shows how to use a [Grouped Reducer](https://developers.google.com/earth-engine/guides/reducers_grouping) to calculate area covered by each class in a classified image. It also shows how to use the `ui.Chart.image.byClass()` function to create a chart showing the area for each class.


![](https://courses.spatialthoughts.com/images/end_to_end_gee/area_by_class.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FCalculating_Area_by_Class)



```
var classified = ee.Image("users/ujavalgandhi/e2e/bangalore\_classified");
var bangalore = ee.FeatureCollection("users/ujavalgandhi/public/bangalore\_boundary");

Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

// Create a 2 band image with the area image and the classified image
// Divide the area image by 1e6 so area results are in Sq Km
var areaImage = ee.Image.pixelArea().divide(1e6).addBands(classified);

// Calculate Area by Class
// Using a Grouped Reducer
var areas = areaImage.reduceRegion({
 reducer: ee.Reducer.sum().group({
 groupField: 1,
 groupName: 'classification',
 }),
 geometry: bangalore,
 scale: 100,
 tileScale: 4,
 maxPixels: 1e10
 }); 

var classAreas = ee.List(areas.get('groups'))
print(classAreas)

var areaChart = ui.Chart.image.byClass({
 image: areaImage,
 classBand: 'classification', 
 region: bangalore,
 scale: 100,
 reducer: ee.Reducer.sum(),
 classLabels: ['urban', 'bare', 'water', 'vegetation'],
}).setOptions({
 hAxis: {title: 'Classes'},
 vAxis: {title: 'Area Km^2'},
 title: 'Area by class',
 series: {
 0: { color: 'gray' },
 1: { color: 'brown' },
 2: { color: 'blue' },
 3: { color: 'green' }
 }
});
print(areaChart); 
```



### Spectral Signature Plots


For supervised classification, it is useful to visualize average spectral responses for each band for each class. Such charts are called *Spectral Response Curves* or *Spectral Signatures*. Such charts helps determine separability of classes. If classes have very different signatures, a classifier will be able to separate them well.


We can also plot spectral signatures of all training samples for a class and check the quality of the training dataset. If all training samples show similar signatures - it indicates that you have done a good job of collecting appropriate samples. You can also catch potential outliers from these plots.


These charts provide a qualitative and visual methods for checking separability of classes. For quantitative methods, one can apply measures such as Spectral Distance, Mahalanobis distance, Bhattacharyya distance , Jeffreys-Matusita (JM) distance etc. You can find the code for these in [this Stack Exchange answer](https://gis.stackexchange.com/a/323778/5160).



![Mean Signatures for All Classes](https://courses.spatialthoughts.com/images/end_to_end_gee/mean_signatures.png)

Mean Signatures for All Classes





![Spectral Signatures for All Training Points by Class](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_signatures.png)

Spectral Signatures for All Training Points by Class




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FSpectral_Signatures)



```
var gcps = ee.FeatureCollection("users/ujavalgandhi/e2e/bangalore\_gcps");
var composite = ee.Image('users/ujavalgandhi/e2e/bangalore\_composite');

// Overlay the point on the image to get bands data.
var training = composite.sampleRegions({
 collection: gcps, 
 properties: ['landcover'], 
 scale: 10
});


// We will create a chart of spectral signature for all classes

// We have multiple GCPs for each class
// Use a grouped reducer to calculate the average reflectance
// for each band for each class

// We have 12 bands so need to repeat the reducer 12 times
// We also need to group the results by class
// So we find the index of the landcover property and use it
// to group the results
var bands = composite.bandNames()
var numBands = bands.length()
var bandsWithClass = bands.add('landcover')
var classIndex = bandsWithClass.indexOf('landcover')

// Use .combine() to get a reducer capable of 
// computing multiple stats on the input
var combinedReducer = ee.Reducer.mean().combine({
 reducer2: ee.Reducer.stdDev(),
 sharedInputs: true})

// Use .repeat() to get a reducer for each band
// We then use .group() to get stats by class
var repeatedReducer = combinedReducer.repeat(numBands).group(classIndex)

var gcpStats = training.reduceColumns({
 selectors: bands.add('landcover'),
 reducer: repeatedReducer,
})

// Result is a dictionary, we do some post-processing to
// extract the results
var groups = ee.List(gcpStats.get('groups'))

var classNames = ee.List(['urban', 'bare', 'water', 'vegetation'])

var fc = ee.FeatureCollection(groups.map(function(item) {
 // Extract the means
 var values = ee.Dictionary(item).get('mean')
 var groupNumber = ee.Dictionary(item).get('group')
 var properties = ee.Dictionary.fromLists(bands, values)
 var withClass = properties.set('class', classNames.get(groupNumber))
 return ee.Feature(null, withClass)
}))

// Chart spectral signatures of training data
var options = {
 title: 'Average Spectral Signatures',
 hAxis: {title: 'Bands'},
 vAxis: {title: 'Reflectance', 
 viewWindowMode:'explicit',
 viewWindow: {
 max:0.6,
 min:0
 }},
 lineWidth: 1,
 pointSize: 4,
 series: {
 0: {color: 'grey'}, 
 1: {color: 'brown'}, 
 2: {color: 'blue'}, 
 3: {color: 'green'},
}};

// Default band names don't sort propertly
// Instead, we can give a dictionary with
// labels for each band in the X-Axis
var bandDescriptions = {
 'B2': 'B02/Blue',
 'B3': 'B03/Green',
 'B4': 'B04/Red',
 'B8': 'B08/NIR',
 'B11': 'B11/SWIR-1',
 'B12': 'B12/SWIR-2'
}
// Create the chart and set options.
var chart = ui.Chart.feature.byProperty({
 features: fc,
 xProperties: bandDescriptions,
 seriesProperty: 'class'
})
.setChartType('ScatterChart')
.setOptions(options);

print(chart)

var classChart = function(landcover, label, color) {
 var options = {
 title: 'Spectral Signatures for ' + label + ' Class',
 hAxis: {title: 'Bands'},
 vAxis: {title: 'Reflectance', 
 viewWindowMode:'explicit',
 viewWindow: {
 max:0.6,
 min:0
 }},
 lineWidth: 1,
 pointSize: 4,
 };

 var fc = training.filter(ee.Filter.eq('landcover', landcover))
 var chart = ui.Chart.feature.byProperty({
 features: fc,
 xProperties: bandDescriptions,
 })
.setChartType('ScatterChart')
.setOptions(options);

print(chart)
}
classChart(0, 'Urban')
classChart(1, 'Bare')
classChart(2, 'Water')
classChart(3, 'Vegetation')
```



### 识别错误分类的 GCP

While doing accuracy assessment, you will see the validation features that were not classified correctly. It is useful to visually see the points that were misclassified. We can use `ee.Filter.eq()` and `ee.Filter.neq()` filters to filter the features where the actual and predicted classes were different. The code below shows how to implement this and also use the `style()` function visualize them effectively.


[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FIdentify_Misclassified_Data)



```
// Script that shows how to apply filters to identify
// validation points that were misclassified
var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas\_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_gcps");

Map.centerObject(gcp)
var arkavathy = basin.filter(ee.Filter.eq('HYBAS\_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
 
var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(boundary))
 .select('B.\*')

var composite = filtered.median().clip(boundary) 

// Display the input composite.
Map.addLayer(composite, rgbVis, 'image');


// Add a random column and split the GCPs into training and validation set
var gcp = gcp.randomColumn()
var trainingGcp = gcp.filter(ee.Filter.lt('random', 0.6));
var validationGcp = gcp.filter(ee.Filter.gte('random', 0.6));

// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: trainingGcp,
 properties: ['landcover'],
 scale: 10,
 tileScale: 16,
 geometries:true
});
// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50)
.train({
 features: training, 
 classProperty: 'landcover',
 inputProperties: composite.bandNames()
});

// Classify the image.
var classified = composite.classify(classifier);

Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

var test = classified.sampleRegions({
 collection: validationGcp,
 properties: ['landcover'],
 tileScale: 16,
 scale: 10,
 geometries:true
});

var testConfusionMatrix = test.errorMatrix('landcover', 'classification')
print('Confusion Matrix', testConfusionMatrix);

// Let's apply filters to find misclassified points
// We can find all points which are labeled landcover=0 (urban) 
// but were not classified correctly

// We use ee.Filter.and() function to create a combined filter
var combinedFilter = ee.Filter.and(
 ee.Filter.eq('landcover', 0), ee.Filter.neq('classification', 0))
var urbanMisclassified = test.filter(combinedFilter)
print('Urban Misclassified Points', urbanMisclassified)

// We can also apply a filter to select all misclassified points
// Since we are comparing 2 properties agaist each-other,
// we need to use a binary filter
var misClassified = test.filter(ee.Filter.notEquals({
 leftField:'classification', rightField:'landcover'}))
 
print('All Misclassified Points', misClassified)

// Display the misclassified points by styling them
var landcover = ee.List([0, 1, 2, 3])
var palette = ee.List(['gray','brown','blue','green'])
var misclassStyled = ee.FeatureCollection(
 landcover.map(function(lc){
 var feature = misClassified.filter(ee.Filter.eq('landcover', lc))
 var color = palette.get(landcover.indexOf(lc));
 var markerStyle = {color:color}
 return feature.map(function(point){
 return point.set('style', markerStyle)
 })
 })).flatten();
 
Map.addLayer(misclassStyled.style({styleProperty:"style"}), {}, 'Misclassified Points')
```



### 图像归一化和标准化

For machine learning, it is a recommended practice to either normalize or standardize your features. The code below shows how to implement these feature scaling techniques.


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FImage_Normalization_and_Standardization)



```
var image = ee.Image("users/ujavalgandhi/e2e/arkavathy\_2019\_composite");
var boundary = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy\_boundary")
var geometry = boundary.geometry()

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function normalize(image){
 var bandNames = image.bandNames();
 // Compute min and max of the image
 var minDict = image.reduceRegion({
 reducer: ee.Reducer.min(),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var maxDict = image.reduceRegion({
 reducer: ee.Reducer.max(),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var mins = ee.Image.constant(minDict.values(bandNames));
 var maxs = ee.Image.constant(maxDict.values(bandNames));

 var normalized = image.subtract(mins).divide(maxs.subtract(mins))
 return normalized
}

//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Function to Standardize Image
// (Mean Centered Imagery with Unit Standard Deviation)
// https://365datascience.com/tutorials/statistics-tutorials/standardization/
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
function standardize(image){
 var bandNames = image.bandNames();
 // Mean center the data to enable a faster covariance reducer
 // and an SD stretch of the principal components.
 var meanDict = image.reduceRegion({
 reducer: ee.Reducer.mean(),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var means = ee.Image.constant(meanDict.values(bandNames));
 var centered = image.subtract(means)
 
 var stdDevDict = image.reduceRegion({
 reducer: ee.Reducer.stdDev(),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
 });
 var stddevs = ee.Image.constant(stdDevDict.values(bandNames));

 var standardized = centered.divide(stddevs);
 
 return standardized
}

var standardizedImage = standardize(image)
var normalizedImage = normalize(image)


Map.addLayer(image, 
 {bands: ['B4', 'B3', 'B2'], min: 0, max: 0.3, gamma: 1.2}, 'Original Image');
Map.addLayer(normalizedImage,
 {bands: ['B4', 'B3', 'B2'], min: 0, max: 1, gamma: 1.2}, 'Normalized Image');
Map.addLayer(standardizedImage,
 {bands: ['B4', 'B3', 'B2'], min: -1, max: 2, gamma: 1.2}, 'Standarized Image');
Map.centerObject(geometry)

// Verify Normalization

var beforeDict = image.reduceRegion({
 reducer: ee.Reducer.minMax(),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
});

var afterDict = normalizedImage.reduceRegion({
 reducer: ee.Reducer.minMax(),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
});

print('Original Image Min/Max', beforeDict)
print('Normalized Image Min/Max', afterDict)

// Verify Standadization
// Verify that the means are 0 and standard deviations are 1
var beforeDict = image.reduceRegion({
 reducer: ee.Reducer.mean().combine({
 reducer2: ee.Reducer.stdDev(), sharedInputs: true}),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
});

var resultDict = standardizedImage.reduceRegion({
 reducer: ee.Reducer.mean().combine({
 reducer2: ee.Reducer.stdDev(), sharedInputs: true}),
 geometry: geometry,
 scale: 10,
 maxPixels: 1e9,
 bestEffort: true,
 tileScale: 16
});
// Means are very small franctions close to 0
// Round them off to 2 decimals
var afterDict = resultDict.map(function(key, value) {
 return ee.Number(value).format('%.2f')
})

print('Original Image Mean/StdDev', beforeDict)
print('Standadized Image Mean/StdDev', afterDict)
```



### 计算特征重要性

Many classifiers in GEE have a `explain()` method that calculates feature importances. The classifier will assign a score to each input variable on how useful they were at predicting the correct value. The script below shows how to extract the feature importance and create a chart to visualize it.



![Relative Feature Importance](https://courses.spatialthoughts.com/images/end_to_end_gee/feature_importance.png)

Relative Feature Importance




[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FFeature_Importance)



```
var bangalore = ee.FeatureCollection('users/ujavalgandhi/public/bangalore\_boundary')
var s2 = ee.ImageCollection('COPERNICUS/S2\_SR')
var gcps = ee.FeatureCollection('users/ujavalgandhi/e2e/bangalore\_gcps')

var filtered = s2
.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(bangalore))
 .select('B.\*')

var composite = filtered.median().clip(bangalore) 


var addIndices = function(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
 var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
 var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
 var bsi = image.expression(
 '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
 'X': image.select('B11'), //swir1
 'Y': image.select('B4'), //red
 'A': image.select('B8'), // nir
 'B': image.select('B2'), // blue
 }).rename('bsi');
 return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

composite = addIndices(composite)


// Display the input composite.
var rgbVis = {
 min: 0.0,
 max: 3000,
 bands: ['B4', 'B3', 'B2'],
};
Map.addLayer(composite, rgbVis, 'image');


// Overlay the point on the image to get training data.
var training = composite.sampleRegions({
 collection: gcps, 
 properties: ['landcover'], 
 scale: 10
});


// Train a classifier.
var classifier = ee.Classifier.smileRandomForest(50).train({
 features: training, 
 classProperty: 'landcover', 
 inputProperties: composite.bandNames()
});
// // Classify the image.
var classified = composite.classify(classifier);
Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019'); 


//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
// Calculate Feature Importance
//\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\*\* 
 
// Run .explain() to see what the classifer looks like
print(classifier.explain())

// Calculate variable importance
var importance = ee.Dictionary(classifier.explain().get('importance'))


// Calculate relative importance
var sum = importance.values().reduce(ee.Reducer.sum())

var relativeImportance = importance.map(function(key, val) {
 return (ee.Number(val).multiply(100)).divide(sum)
 })
print(relativeImportance)

// Create a FeatureCollection so we can chart it
var importanceFc = ee.FeatureCollection([
 ee.Feature(null, relativeImportance)
])

var chart = ui.Chart.feature.byProperty({
 features: importanceFc
}).setOptions({
 title: 'Feature Importance',
 vAxis: {title: 'Importance'},
 hAxis: {title: 'Feature'},
 legend: {position: 'none'}
 })
print(chart)
```




## 时序平滑和间隙填充


### 移动窗口平滑

A technique applied to a time series for removal of the fine-grained variation between time steps is known as Smoothing. This example shows how a moving-window smoothing algorithm can be applied in Earth Engine. Using a [Save-all Join](https://developers.google.com/earth-engine/guides/joins_save_all), the collection is joined with itself and all images that fall within the temporal-window are added as a property of each image. Next, a *mean* reducer is applied on all the images, resulting in the average value of the pixel within the time-frame. The resulting time-series reduces the sharp peaks and valleys - and is more robust against outliers (such as cloudy pixels)



![Moving Window Average Smoothing](https://courses.spatialthoughts.com/images/end_to_end_gee/Moving_Window_Smoothing.png)

Moving Window Average Smoothing




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FTime_Series_Smoothing%2FMoving_Window_Smoothing)



```
// Moving-Window Temporal Smoothing 
var s2 = ee.ImageCollection("COPERNICUS/S2");
var geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]]);
Map.addLayer(geometry, {color: 'red'}, 'Farm')
Map.centerObject(geometry)
var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};

var filtered = s2
 .filter(ee.Filter.date('2017-01-01', '2018-01-01'))
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask).divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}

var filtered = filtered.map(maskS2clouds)
// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

// Map the function over the collection
var withNdvi = filtered.map(addNDVI);

// Moving-Window Smoothing

// Specify the time-window
var days = 30

// We use a 'join' to find all images that are within
// the time-window
// The join will add all matching images into a
// new property called 'images'
var join = ee.Join.saveAll({
 matchesKey: 'images'
});

// This filter will match all images that are captured
// within the specified day of the source image
var diffFilter = ee.Filter.maxDifference({
 difference: 1000 \* 60 \* 60 \* 24 \* days,
 leftField: 'system:time\_start', 
 rightField: 'system:time\_start'
});

// Select the 'ndvi' band
var ndviCol = withNdvi.select('ndvi')

var joinedCollection = join.apply({
 primary: ndviCol, 
 secondary: ndviCol, 
 condition: diffFilter
});

// Each image in the joined collection will contain
// matching images in the 'images' property
// Extract and return the mean of matched images
var smoothedCollection = ee.ImageCollection(joinedCollection.map(function(image) {
 var collection = ee.ImageCollection.fromImages(image.get('images'));
 return ee.Image(image).addBands(collection.mean().rename('moving\_average'));
}))
 
// Display a time-series chart
var chart = ui.Chart.image.series({
 imageCollection: smoothedCollection.select(['ndvi', 'moving\_average']),
 region: geometry,
 reducer: ee.Reducer.mean(),
 scale: 20
}).setOptions({
 lineWidth: 1,
 title: 'NDVI Time Series',
 interpolateNulls: true,
 vAxis: {title: 'NDVI'},
 hAxis: {title: '', format: 'YYYY-MMM'},
 series: {
 1: {color: 'gray', lineDashStyle: [1, 1]}, // Original NDVI
 0: {color: 'red', lineWidth: 2 }, // Smoothed NDVI
 },

 })
print(chart);
```



### 时间插值

The code below shows how to do temporal gap-filling of time-series data. A detailed explanation of the code and other examples are described in our blog post [Temporal Gap-Filling with Linear Interpolation in GEE](https://spatialthoughts.com/2021/11/08/temporal-interpolation-gee/).


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FTime_Series_Smoothing%2FTemporal_Interpolation)



```
// Temporal Interpolation (Gap-Filling Masked Pixels)
var geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]]);

Map.addLayer(geometry, {color: 'red'}, 'Farm')
Map.centerObject(geometry)

var s2 = ee.ImageCollection("COPERNICUS/S2\_SR");

var filtered = s2
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
function maskCloudAndShadowsSR(image) {
 var cloudProb = image.select('MSK\_CLDPRB');
 var snowProb = image.select('MSK\_SNWPRB');
 var cloud = cloudProb.lt(5);
 var snow = snowProb.lt(5);
 var scl = image.select('SCL'); 
 var shadow = scl.eq(3); // 3 = cloud shadow
 var cirrus = scl.eq(10); // 10 = cirrus
 // Cloud probability less than 5% or cloud shadow classification
 var mask = (cloud.and(snow)).and(cirrus.neq(1)).and(shadow.neq(1));
 return image.updateMask(mask).divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"]);
}

var filtered = filtered.map(maskCloudAndShadowsSR)

// Add a band containing timestamp to each image
// This will be used to do pixel-wise interpolation later
var filtered = filtered.map(function(image) {
 var timeImage = image.metadata('system:time\_start').rename('timestamp')
 // The time image doesn't have a mask. 
 // We set the mask of the time band to be the same as the first band of the image
 var timeImageMasked = timeImage.updateMask(image.mask().select(0))
 return image.addBands(timeImageMasked)
})

// Specify the time-window
// This will determine how much backward and forward are we willing to
// look for an unmasked pixel in the time-series
var days = 30

// For each image in the collection, we need to find all images
// before and after the specified time-window

// This is accomplished using Joins
// We need to do 2 joins
// Join 1: Join the collection with itself to find all images before each image
// Join 2: Join the collection with itself to find all images after each image

// We first define the filters needed for the join

// Define a maxDifference filter to find all images within the specified days
// The filter needs the time difference in milliseconds
// Convert days to milliseconds
var millis = ee.Number(days).multiply(1000\*60\*60\*24)
var maxDiffFilter = ee.Filter.maxDifference({
 difference: millis,
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})

// We need a lessThanOrEquals filter to find all images after a given image
// This will compare the given image's timestamp against other images' timestamps
var lessEqFilter = ee.Filter.lessThanOrEquals({
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})

// We need a greaterThanOrEquals filter to find all images before a given image
// This will compare the given image's timestamp against other images' timestamps
var greaterEqFilter = ee.Filter.greaterThanOrEquals({
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})

// Apply the joins

// For the first join, we need to match all images that are after the given image.
// To do this we need to match 2 conditions
// 1. The resulting images must be within the specified time-window of target image
// 2. The target image's timestamp must be lesser than the timestamp of resulting images
// Combine two filters to match both these conditions
var filter1 = ee.Filter.and(maxDiffFilter, lessEqFilter)
// This join will find all images after, sorted in descending order
// This will gives us images so that closest is last
var join1 = ee.Join.saveAll({
 matchesKey: 'after',
 ordering: 'system:time\_start',
 ascending: false})
 
var join1Result = join1.apply({
 primary: filtered,
 secondary: filtered,
 condition: filter1
})
// Each image now as a property called 'after' containing
// all images that come after it within the time-window
print(join1Result.first())

// Do the second join now to match all images within the time-window
// that come before each image
var filter2 = ee.Filter.and(maxDiffFilter, greaterEqFilter)
// This join will find all images before, sorted in ascending order
// This will gives us images so that closest is last
var join2 = ee.Join.saveAll({
 matchesKey: 'before',
 ordering: 'system:time\_start',
 ascending: true})
 
var join2Result = join2.apply({
 primary: join1Result,
 secondary: join1Result,
 condition: filter2
})

// Each image now as a property called 'before' containing
// all images that come after it within the time-window
print(join2Result.first())


// Do the interpolation

// We now write a function that will be used to interpolate all images
// This function takes an image and replaces the masked pixels
// with the interpolated value from before and after images.

var interpolateImages = function(image) {
 var image = ee.Image(image)
 // We get the list of before and after images from the image property
 // Mosaic the images so we a before and after image with the closest unmasked pixel
 var beforeImages = ee.List(image.get('before'))
 var beforeMosaic = ee.ImageCollection.fromImages(beforeImages).mosaic()
 var afterImages = ee.List(image.get('after'))
 var afterMosaic = ee.ImageCollection.fromImages(afterImages).mosaic()

 // Interpolation formula
 // y = y1 + (y2-y1)\*((t – t1) / (t2 – t1))
 // y = interpolated image
 // y1 = before image
 // y2 = after image
 // t = interpolation timestamp
 // t1 = before image timestamp
 // t2 = after image timestamp
 
 // We first compute the ratio (t – t1) / (t2 – t1)

 // Get image with before and after times
 var t1 = beforeMosaic.select('timestamp').rename('t1')
 var t2 = afterMosaic.select('timestamp').rename('t2')

 var t = image.metadata('system:time\_start').rename('t')

 var timeImage = ee.Image.cat([t1, t2, t])

 var timeRatio = timeImage.expression('(t - t1) / (t2 - t1)', {
 't': timeImage.select('t'),
 't1': timeImage.select('t1'),
 't2': timeImage.select('t2'),
 })
 // You can replace timeRatio with a constant value 0.5
 // if you wanted a simple average
 
 // Compute an image with the interpolated image y
 var interpolated = beforeMosaic
 .add((afterMosaic.subtract(beforeMosaic).multiply(timeRatio)))
 // Replace the masked pixels in the current image with the average value
 var result = image.unmask(interpolated)
 return result.copyProperties(image, ['system:time\_start'])
}

// map() the function to interpolate all images in the collection
var interpolatedCol = ee.ImageCollection(join2Result.map(interpolateImages))

// interpolatedCol is the gap-filled collection that can be used
// for further analysis.

// Let's visualize the NDVI time-series
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

var ndviVis = {min:0, max: 0.9, palette: [
 'FFFFFF', 'CE7E45', 'DF923D', 'F1B555', 'FCD163', '99B718', '74A901',
 '66A000', '529400', '3E8601', '207401', '056201', '004C00', '023B01',
 '012E01', '011D01', '011301'
 ]}

var visualizeImage = function(image) {
 return image.select('ndvi').visualize(ndviVis).clip(geometry)
}

var visCollectionOriginal = filtered
 .map(addNDVI)
 .map(visualizeImage)
var visCollectionInterpolated = interpolatedCol
 .map(addNDVI)
 .map(visualizeImage)

var videoArgs = {
 dimensions: 400,
 region: geometry,
 framesPerSecond: 1,
 crs: 'EPSG:3857',
};

print('Original NDVI Images', visCollectionOriginal.getVideoThumbURL(videoArgs))
print('Gap Filled NDVI Images', visCollectionInterpolated.getVideoThumbURL(videoArgs))
```



### Savitzky-Golay 平滑

The Savitzky–Golay filter fits a polynomial to a set of data points in a time-series. The [Open Earth Engine Library (OEEL)](https://www.open-geocomputing.org/OpenEarthEngineLibrary/) provides an efficient implementation of this filter that can be applied on an ImageCollection. However, the time-series must be pre-processed so there are images at a regular interval. We use the [interpolation technique](#temporal-interpolation) described in the previous section and prepare a continous time-series without any masked pixels. The result is a new ImageCollection containing images at a regular interval (5-day) and with pixel values smoothed using the Savitzky–Golay filter.



![Savitzky-Golay Smoothing](https://courses.spatialthoughts.com/images/end_to_end_gee/Savitzky_Golay_Smoothing.png)

Savitzky-Golay Smoothing




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FTime_Series_Smoothing%2FSavitzky_Golay_Smoothing)



```
// Aplying Savitzky-Golay Filter on a NDVI Time-Series
// This script uses the OEEL library to apply a 
// Savitzky-Golay filter on a imagecollection

// We require a regularly-spaced time-series without
// any masked pixels. So this script applies
// linear interpolation to created regularly spaced images
// from the original time-series

// Step-1: Prepare a NDVI Time-Series
// Step-2: Create an empty Time-Series with images at n days
// Step-3: Use Joins to find before/after images
// Step-4: Apply linear interpolation to fill each image
// Step-5: Apply Savitzky-Golay filter
// Step-6: Visualize the results

//##############################################################
// Step-1: Prepare a NDVI time-series
//##############################################################

var s2 = ee.ImageCollection("COPERNICUS/S2"); 
var geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]]);
Map.addLayer(geometry, {color: 'red'}, 'Farm')
Map.centerObject(geometry)

var startDate = ee.Date('2017-01-01')
var endDate = startDate.advance(1, 'year')

var filtered = s2
 .filter(ee.Filter.date(startDate, endDate))
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask)//.divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}

var filtered = filtered.map(maskS2clouds)


// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).toFloat().rename('ndvi');
 return image.addBands(ndvi);
}


// Map the function over the collection
var withNdvi = filtered.map(addNDVI);

// Select 'ndvi' band
var ndviCol = withNdvi.select('ndvi')
print('Original Collection', ndviCol)
//##############################################################
// Step-2: Create an empty Time-Series with images at n days
//##############################################################

// Select the interval. We will have 1 image every n days
var n = 5;
var totalDays = endDate.difference(startDate, 'day');
var daysToInterpolate = ee.List.sequence(1, totalDays, n)

var initImages = daysToInterpolate.map(function(day) {
 var image = ee.Image().rename('ndvi').toFloat().set({
 'system:index': ee.Number(day).format('%d'),
 'system:time\_start': startDate.advance(day, 'day').millis(),
 // Set a property so we can identify interpolated images
 'type': 'interpolated'
 })
 return image
})

var initCol = ee.ImageCollection.fromImages(initImages)
print('Empty Collection', initCol)

//##############################################################
// Step-3: Use Joins to find before/after images
//##############################################################

// Merge empty collection with the original collection so we can
// find images to interpolate from
var mergedCol = ndviCol.merge(initCol)

var mergedCol = mergedCol.map(function(image) {
 var timeImage = image.metadata('system:time\_start').rename('timestamp')
 var timeImageMasked = timeImage.updateMask(image.mask().select(0))
 return image.addBands(timeImageMasked)
})

// Specify the time-window
// Set it so that we have at least 1 non-cloudy image in the period
var days = 60
var millis = ee.Number(days).multiply(1000\*60\*60\*24)

var maxDiffFilter = ee.Filter.maxDifference({
 difference: millis,
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})

var lessEqFilter = ee.Filter.lessThanOrEquals({
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})


var greaterEqFilter = ee.Filter.greaterThanOrEquals({
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})


var filter1 = ee.Filter.and(maxDiffFilter, lessEqFilter)
var join1 = ee.Join.saveAll({
 matchesKey: 'after',
 ordering: 'system:time\_start',
 ascending: false})
 
var join1Result = join1.apply({
 primary: mergedCol,
 secondary: mergedCol,
 condition: filter1
})

var filter2 = ee.Filter.and(maxDiffFilter, greaterEqFilter)

var join2 = ee.Join.saveAll({
 matchesKey: 'before',
 ordering: 'system:time\_start',
 ascending: true})
 
var join2Result = join2.apply({
 primary: join1Result,
 secondary: join1Result,
 condition: filter2
})

//##############################################################
// Step-4: Apply linear interpolation to fill each image
//##############################################################

// Once the joins are done, we don't need original NDVI images
// We keep only the blank images which now have matching NDVI images
// as properties
var filtered = join2Result.filter(ee.Filter.eq('type', 'interpolated'))

// Interpolatinon function
function interpolateImages(image) {
 var image = ee.Image(image)

 var beforeImages = ee.List(image.get('before'))
 var beforeMosaic = ee.ImageCollection.fromImages(beforeImages).mosaic()
 var afterImages = ee.List(image.get('after'))
 var afterMosaic = ee.ImageCollection.fromImages(afterImages).mosaic()

 var t1 = beforeMosaic.select('timestamp').rename('t1')
 var t2 = afterMosaic.select('timestamp').rename('t2')

 var t = image.metadata('system:time\_start').rename('t')

 var timeImage = ee.Image.cat([t1, t2, t])

 var timeRatio = timeImage.expression('(t - t1) / (t2 - t1)', {
 't': timeImage.select('t'),
 't1': timeImage.select('t1'),
 't2': timeImage.select('t2'),
 })

 var interpolated = beforeMosaic
 .add((afterMosaic.subtract(beforeMosaic).multiply(timeRatio)))
 var result = image.unmask(interpolated)
 return result.copyProperties(image, ['system:time\_start'])
}

var interpolatedCol = ee.ImageCollection(
 filtered.map(interpolateImages)).select('ndvi')
print('Interpolated Collection', interpolatedCol)


//##############################################################
// Step-5: Apply Savitzky-Golay filter
//##############################################################


var oeel=require('users/OEEL/lib:loadAll');
// https://www.open-geocomputing.org/OpenEarthEngineLibrary/#.ImageCollection.SavatskyGolayFilter

// Use the same maxDiffFilter we used earlier
var maxDiffFilter = ee.Filter.maxDifference({
 difference: millis,
 leftField: 'system:time\_start',
 rightField: 'system:time\_start'
})

// Use the default distanceFunction
var distanceFunction = function(infromedImage, estimationImage) {
 return ee.Image.constant(
 ee.Number(infromedImage.get('system:time\_start'))
 .subtract(
 ee.Number(estimationImage.get('system:time\_start')))
 );
 }

// Apply smoothing of order=3
var order = 3;
var smoothed = oeel.ImageCollection.SavatskyGolayFilter(
 interpolatedCol, 
 maxDiffFilter,
 distanceFunction,
 order)

// Select the d\_0\_ndvi band and rename it
var smoothed = smoothed.select(['d\_0\_ndvi'], ['smoothed'])

//##############################################################
// Step-6: Visualize the results
//##############################################################

// Chart the time-series at a single location
var title = 'Savitsky-Golay smoothing' +
 '(order = '+ order + ', window\_size = ' + days + ')'

// Plot the original and fitted NDVI time-series
var chart = ui.Chart.image.series({
 imageCollection: ndviCol.merge(smoothed),
 region: geometry,
 reducer: ee.Reducer.mean(),
 scale: 20
}).setOptions({
 lineWidth: 1,
 title: title,
 interpolateNulls: true,
 vAxis: {title: 'NDVI'},
 hAxis: {title: '', format: 'YYYY-MMM'},
 series: {
 0: {color: 'blue', lineWidth: 1, 
 lineDashStyle: [1, 1], pointSize: 1,
 }, // Original NDVI
 1: {color: 'red', lineWidth: 2 }, // Smoothed NDVI
 },

 })
print(chart)

// Create an animation to visualize the smoothed collection
var ndviVis = {min:0, max: 0.7, palette: [
 '#fdae61','#fee08b','#d9ef8b',
 '#a6d96a','#66bd63','#1a9850','#006837']
 }

var visualizeImage = function(image) {
 return image.visualize(ndviVis).clip(geometry)
}

var visCollectionOriginal = ndviCol
 .map(visualizeImage)
var visCollectionInterpolated = smoothed
 .map(visualizeImage)
 
var videoArgs = {
 dimensions: 400,
 region: geometry,
 framesPerSecond: 2,
 crs: 'EPSG:3857',
};

print('Original NDVI Images', visCollectionOriginal.getVideoThumbURL(videoArgs))

var videoArgs = {
 dimensions: 400,
 region: geometry,
 framesPerSecond: 5,
 crs: 'EPSG:3857',
};

print('SG Filtered NDVI Images', visCollectionInterpolated.getVideoThumbURL(videoArgs))
```




## 用户界面模版


### 添加离散图例

You may want to add a legend for a classified image to your map visualization in your App. Here’s a code snippet that shows how you can build it using the UI Widgets.



![Creating a Discrete Map Legend](https://courses.spatialthoughts.com/images/end_to_end_gee/map_legend.png)

Creating a Discrete Map Legend




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FMap_Legend)



```
var classified = ee.Image("users/ujavalgandhi/e2e/bangalore\_classified")
Map.centerObject(classified)
Map.addLayer(classified,
 {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, '2019');

var legend = ui.Panel({style: {position: 'middle-right', padding: '8px 15px'}});

var makeRow = function(color, name) {
 var colorBox = ui.Label({
 style: {color: '#ffffff',
 backgroundColor: color,
 padding: '10px',
 margin: '0 0 4px 0',
 }
 });
 var description = ui.Label({
 value: name,
 style: {
 margin: '0px 0 4px 6px',
 }
 }); 
 return ui.Panel({
 widgets: [colorBox, description],
 layout: ui.Panel.Layout.Flow('horizontal')}
)};

var title = ui.Label({
 value: 'Legend',
 style: {fontWeight: 'bold',
 fontSize: '16px',
 margin: '0px 0 4px 0px'}});
 
legend.add(title);
legend.add(makeRow('gray','Built-up'))
legend.add(makeRow('brown','Bare Earth'))
legend.add(makeRow('blue','Water'))
legend.add(makeRow('green','Vegetation'))

Map.add(legend);
```



### Adding a Continous Legend


If you are displaying a raster layer in your app with a color palette, you can use the following technique to add a colorbar using the snipet below.



![Creating a Continuous Raster Legend](https://courses.spatialthoughts.com/images/end_to_end_gee/colorbar.png)

Creating a Continuous Raster Legend




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FColorbar_Legend)



```
var s2 = ee.ImageCollection("COPERNICUS/S2");
var admin2 = ee.FeatureCollection("FAO/GAUL\_SIMPLIFIED\_500m/2015/level2");

var bangalore = admin2.filter(ee.Filter.eq('ADM2\_NAME', 'Bangalore Urban'))
var geometry = bangalore.geometry()

var filtered = s2.filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
 .filter(ee.Filter.bounds(geometry))

var image = filtered.median(); 

// Calculate Normalized Difference Vegetation Index (NDVI)
// 'NIR' (B8) and 'RED' (B4)
var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);

var palette = ['#d7191c','#fdae61','#ffffbf','#a6d96a','#1a9641']
var ndviVis = {min:0, max:0.5, palette: palette}
Map.centerObject(geometry, 12)
Map.addLayer(ndvi.clip(geometry), ndviVis, 'ndvi')


function createColorBar(titleText, palette, min, max) {
 // Legend Title
 var title = ui.Label({
 value: titleText, 
 style: {fontWeight: 'bold', textAlign: 'center', stretch: 'horizontal'}});

 // Colorbar
 var legend = ui.Thumbnail({
 image: ee.Image.pixelLonLat().select(0),
 params: {
 bbox: [0, 0, 1, 0.1],
 dimensions: '200x20',
 format: 'png', 
 min: 0, max: 1,
 palette: palette},
 style: {stretch: 'horizontal', margin: '8px 8px', maxHeight: '40px'},
 });
 
 // Legend Labels
 var labels = ui.Panel({
 widgets: [
 ui.Label(min, {margin: '4px 10px',textAlign: 'left', stretch: 'horizontal'}),
 ui.Label((min+max)/2, {margin: '4px 20px', textAlign: 'center', stretch: 'horizontal'}),
 ui.Label(max, {margin: '4px 10px',textAlign: 'right', stretch: 'horizontal'})],
 layout: ui.Panel.Layout.flow('horizontal')});
 
 // Create a panel with all 3 widgets
 var legendPanel = ui.Panel({
 widgets: [title, legend, labels],
 style: {position: 'bottom-center', padding: '8px 15px'}
 })
 return legendPanel
}
// Call the function to create a colorbar legend 
var colorBar = createColorBar('NDVI Values', palette, 0, 0.5)

Map.add(colorBar)
```



### 更改可视化 UI 应用程序

A common use-case for Earth Engine Apps is to display 2 images in a split panel app. Below script contains a simple template that you can use to create an interactive split panel app. Here we have 2 map objects - `leftMap` and `rightMap`. You can add different images to each of the maps and users will be able to explore them side-by-side. [[View Animated GIF ↗](https://courses.spatialthoughts.com/images/end_to_end_gee/dust_storm_app.gif)]



![A Split Panel App that displays Pre- and Post-Storm Images](https://courses.spatialthoughts.com/images/end_to_end_gee/dust_storm_app.png)

A Split Panel App that displays Pre- and Post-Storm Images




[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FChange_Visualization_UI_App)



```
// On June 9, 2018 - A massive dust storm hit North India
// This example shows before and after imagery from Sentinel-2

// Display two visualizations of a map.

// Set a center and zoom level.
var center = {lon: 77.47, lat: 28.41, zoom: 12};

// Create two maps.
var leftMap = ui.Map(center);
var rightMap = ui.Map(center);

// Remove UI controls from both maps, but leave zoom control on the left map.
leftMap.setControlVisibility(false);
rightMap.setControlVisibility(false);
leftMap.setControlVisibility({zoomControl: true});

// Link them together.
var linker = new ui.Map.Linker([leftMap, rightMap]);

// Create a split panel with the two maps.
var splitPanel = ui.SplitPanel({
 firstPanel: leftMap,
 secondPanel: rightMap,
 orientation: 'horizontal',
 wipe: true
});

// Remove the default map from the root panel.
ui.root.clear();

// Add our split panel to the root panel.
ui.root.add(splitPanel);

var rgb\_vis = {min: 0, max: 3200, bands: ['B4', 'B3', 'B2']};

var preStorm = ee.Image('COPERNICUS/S2/20180604T052651\_20180604T053435\_T43RGM')
var postStorm = ee.Image('COPERNICUS/S2/20180614T052651\_20180614T053611\_T43RGM')

// Add a RGB Landsat 8 layer to the left map.
leftMap.addLayer(preStorm, rgb\_vis);
rightMap.addLayer(postStorm, rgb\_vis);
```



### NDVI Explorer UI 应用程序


Earth Engine Apps allow you to display interactive charts in response to user action. This app shows the common design pattern to build an app that allows the user to click anywhere on the map and obtain a chart using the clicked-location.



![Global NDVI Explorer App](https://courses.spatialthoughts.com/images/end_to_end_gee/global_ndvi_explorer.png)

Global NDVI Explorer App




[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FNDVI%20Explorer%20UI%20App)



```
var geometry = ee.Geometry.Point([77.5979, 13.00896]);
Map.centerObject(geometry, 10)

var s2 = ee.ImageCollection("COPERNICUS/S2")
var rgbVis = {
 min: 0.0,
 max: 0.3,
 bands: ['B4', 'B3', 'B2'],
};

var palette = [
 'FFFFFF', 'CE7E45', 'DF923D', 'F1B555', 'FCD163', '99B718',
 '74A901', '66A000', '529400', '3E8601', '207401', '056201',
 '004C00', '023B01', '012E01', '011D01', '011301'];

var ndviVis = {min:0, max:0.5, palette: palette }


// Write a function for Cloud masking
function maskS2clouds(image) {
 var qa = image.select('QA60')
 var cloudBitMask = 1 << 10;
 var cirrusBitMask = 1 << 11;
 var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
 qa.bitwiseAnd(cirrusBitMask).eq(0))
 return image.updateMask(mask).divide(10000)
 .select("B.\*")
 .copyProperties(image, ["system:time\_start"])
}


// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
 var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
 return image.addBands(ndvi);
}

function getComposite(geometry) {
 var filtered = s2
 .filter(ee.Filter.date('2019-01-01', '2019-12-31'))
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30))
 .filter(ee.Filter.bounds(geometry))
 .map(maskS2clouds)
 // Map the function over the collection
 var withNdvi = filtered.map(addNDVI);

 var composite = withNdvi.median()
 return composite
}


// Create UI Elements
var title = ui.Label('Global NDVI Explorer');
title.style().set({
 'position': 'top-center',
 'fontSize': '24px'
 });
var resultsPanel = ui.Panel();
var chartPanel = ui.Panel();
var selectionPanel = ui.Panel({
 layout: ui.Panel.Layout.flow('horizontal'),
});

resultsPanel.style().set({
 width: '400px',
 position: 'bottom-right'
});

var resetPanel = ui.Panel();


resultsPanel.add(selectionPanel)
resultsPanel.add(chartPanel)
resultsPanel.add(resetPanel)

// Function to reset the app to initial state
var resetEverything = function() {
 chartPanel.clear()
 selectionPanel.clear()
 resetPanel.clear()

 Map.clear()

 Map.add(title);
 Map.add(resultsPanel)
 Map.onClick(displayChart)
 // Use the current viewport
 var bounds = ee.Geometry.Rectangle(Map.getBounds())
 var composite = getComposite(bounds)
 Map.addLayer(composite, rgbVis, 'Sentinel-2 Composite')
 var label = ui.Label('Click anywhere to see the chart')
 resetPanel.add(label)

}

// Function to create and display NDVI time-series chart
var displayChart = function(point) {
 resetPanel.clear()
 var button = ui.Button({
 label: 'Reset',
 onClick: resetEverything})
 resetPanel.add(button)
 var geometry = ee.Geometry.Point(point['lon'], point['lat']);
 
 var filtered = s2
 .filter(ee.Filter.date('2019-01-01', '2019-12-31'))
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 50))
 .map(maskS2clouds)
 .map(addNDVI)
 .filter(ee.Filter.bounds(geometry))
 
 var chart = ui.Chart.image.series({
 imageCollection: filtered.select('ndvi'),
 region: geometry,
 reducer: ee.Reducer.mean(),
 scale: 20}).setOptions({
 title: 'NDVI Time Series',
 vAxis: {title: 'NDVI'},
 hAxis: {title: 'Date', gridlines: {count: 12}}
 })
 
 chartPanel.clear()
 selectionPanel.clear()
 selectionPanel.add(ui.Label('Choose an image to display:'))
 chartPanel.add(chart)
 
 
 var addNdviLayer = function(dateString) {
 var date = ee.Date.parse('YYYY-MM-dd', dateString)
 var image = ee.Image(filtered.filter(ee.Filter.date(date, date.advance(1, 'day'))).mosaic())
 Map.addLayer(image.select('ndvi'), ndviVis, 'NDVI Image -' + dateString)
 }


 filtered.aggregate\_array('system:time\_start').evaluate(function(ids) {
 var dates = ee.List(ids).distinct().map(function(timestamp) {
 return ee.Date(timestamp).format('YYYY-MM-dd')
 })
 dates.evaluate(function(dateList){
 selectionPanel.add(ui.Select({
 items: dateList,
 onChange: addNdviLayer,
 placeholder: 'Select a date'
 }))
 })

});

}
// Call the function to build the initial UI state.
resetEverything();
```




## 代码共享和脚本模块

As your Earth Engine project grows, you need a way to organize and share your code to collaborate with others. We will learn some best practices on how best to set-up your project in Earth Engine.



### 分享单个脚本

To share your code from a single script, you need to use the **Get Link** button in the code editor. As you click the button, the contents of your code editor is captured and encoded into a URL. When you share this URL with someone, they will be able see same content as your code editor. This is a great way to send a snapshot of your code so others can reproduce your output. Remember that the script links are just snapshots, if you change your code after sending the link to someone, they will not see the updates.



> 
> When trying to send someone a link, do NOT click the *Copy Script Path* button. Sending this path to someone will NOT give them access to your code. The script path only works only on public or shared repositories.
> 
> 
> 



![Code Sharing using Get Link button](https://courses.spatialthoughts.com/images/end_to_end_gee/get_link.png)

Code Sharing using Get Link button




While sharing the script using *Get Link*, you should also share any private **Assets** that you may have uploaded and are using in the script. You can share the asset with a specific email address, or check the *Anyone can read* box if you want anyone with the script link to be able to access it. Failing to do so will prevent others from running your script.



![Sharing Uploaded Assets](https://courses.spatialthoughts.com/images/end_to_end_gee/sharing_assets.png)

Sharing Uploaded Assets




Learn more in the [Script links](https://developers.google.com/earth-engine/guides/playground#get-link) section of the Google Earth Engine User Guide.




### 分享多个脚本

If you want to share a collection of scripts with other users or your collaborators, the best way is to create a new **Repository**.



![Creating New Repository](https://courses.spatialthoughts.com/images/end_to_end_gee/new_repository.png)

Creating New Repository




You can put multiple scripts within the repository and share the repository with other users. You can grant them **Reader** or **Writer** access so they can view/add/modify/delete scripts in that repository. If you want to make it readable by **Public**, you can check the *Anyone can read* option. You will see a URL in the form of `https://code.earthengine.google.co.in/?accept_repo=...`. When you share this URL with other users and they visit that link, your repository will be added to their Code Editor under the *Reader* or *Writer* folder depending on their access.



![Creating New Repository](https://courses.spatialthoughts.com/images/end_to_end_gee/sharing_repository.png)

Creating New Repository




Learn more in the [Script Manager](https://developers.google.com/earth-engine/guides/playground#script-manager-scripts-tab) section of the Google Earth Engine User Guide.




### 在脚本间共享代码

For a large project, it is preferable to share commonly used functions between scripts. That way, each script doesn’t have to re-implement the same code. Earth Engine enables this using **Script Modules**. Using a special object called `exports`, you can expose a function to other scripts. Learn more in the [Script modules](https://developers.google.com/earth-engine/guides/playground#script-modules) section of the Google Earth Engine User Guide.


There are many Earth Engine users who have shared their repositories publicly and written script modules to perform a variety of tasks. Here’s an example of using the `grid` module from the `users/gena/packages` repository to create regularly spaced grids in Earth Engine.



![Using a function from a script module](https://courses.spatialthoughts.com/images/end_to_end_gee/script_modules.png)

Using a function from a script module




[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FMiscellaneous%2FCode_Sharing_and_Script_Modules)



```
var karnataka = ee.FeatureCollection("users/ujavalgandhi/public/karnataka");
Map.addLayer(karnataka, {color: 'gray'}, 'State Boundary')
var bounds = karnataka.geometry().bounds()
var coords = ee.List(bounds.coordinates().get(0))
var xmin = ee.List(coords.get(0)).get(0)
var ymin = ee.List(coords.get(0)).get(1)
var xmax = ee.List(coords.get(2)).get(0)
var ymax = ee.List(coords.get(2)).get(1)
// source code for the grid package:
// https://code.earthengine.google.com/?accept\_repo=users/gena/packages

// Import the module to our script using 'require'
var gridModule = require('users/gena/packages:grid')

// Now we can run any function from the module
// We try running the generateGrid function to create regularly spaced vector grid
// generateGrid(xmin, ymin, xmax, ymax, dx, dy, marginx, marginy, opt\_proj)

var spacing = 0.5
var gridVector = gridModule.generateGrid(xmin, ymin, xmax, ymax, spacing, spacing, 0, 0)
Map.centerObject(gridVector)
Map.addLayer(gridVector, {color: 'blue'}, 'Grids')
```



### 有用的公共存储库

Please visit [Awesome Earth Engine](https://github.com/giswqs/Awesome-GEE) to see a curated list of Google Earth Engine resources.


We also have a few recommendations of a few selected packages, which have very useful functions to make you productive in Earth Engine.


**General Purpose Packages**


* [eepackages](https://github.com/gee-community/ee-packages-py): A set of Google Earth Engine utilities by maintained by Gennadii Donchyts for both Javascript and Python API.
* [geetools](https://github.com/fitoprincipe/geetools-code-editor/wiki): Tools for cloud masking, batch processing, and more
* [ee-palettes](https://github.com/gee-community/ee-palettes): Module for generating color palettes
* [spectral](https://github.com/awesome-spectral-indices/spectral): A javascript module that provides ready-to-use curated list of spectral indices for GEE.
* [eemont](https://github.com/davemlz/eemont): Python package that provides utility methods to create a more fluid code by being friendly with the Python method chaining.


**Application Specific Packages**


* [LEAF-Toolbox](https://github.com/rfernand387/LEAF-Toolbox/wiki): Google Earth Engine application that produces various Vegetation Biophysical Products, including Leaf Area Index (LAI).
* [RivWidthCloud](https://github.com/seanyx/RivWidthCloudPaper): Package to automate extracting river centerline and width for both Javascript and Python API.







# 指导项目

Below are step-by-step video-based walkthrough of implementing real-world projects using Earth Engine. You can continue their learning journey by implementing these projects for their region of interest after the class.



## 获取代码

1. [Click this link](https://code.earthengine.google.co.in/?accept_repo=users/ujavalgandhi/End-to-End-%20Projects) to open Google Earth Engine code editor and add the repository to your account.
2. If successful, you will have a new repository named `users/ujavalgandhi/End-to-End-Projects` in the *Scripts* tab in the *Reader* section.



> 
> If you do not see the repository in the *Reader* section, refresh your browser tab and it will show up.
> 
> 
> 



![Code Editor After Adding the Projects Repository](https://courses.spatialthoughts.com/images/end_to_end_gee/projects.png)

Code Editor After Adding the Projects Repository






## 项目 1：干旱监测


Calculating Rainfall Deviation from the 30-year mean using CHIRPS Gridded Rainfall Data


[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_drought.png)](https://www.youtube.com/watch?v=zHUCM3XLc6k&list=PLppGmFLhQ1HJ5VhW6BZfhPX6spUcTY7SR)


[Start Guided Project](https://www.youtube.com/watch?v=zHUCM3XLc6k&list=PLppGmFLhQ1HJ5VhW6BZfhPX6spUcTY7SR)




## 项目 2：洪水测绘

Rapid mapping of a flood using Sentinel-1 SAR Data.


[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_flood.png)](https://www.youtube.com/watch?v=jYsK9Y4ICrY&list=PLppGmFLhQ1HJzzKVS_4v8nBiXLYxAu100)


[Start Guided Project](https://www.youtube.com/watch?v=jYsK9Y4ICrY&list=PLppGmFLhQ1HJzzKVS_4v8nBiXLYxAu100)




## 项目 3：提取时间序列

Extracting a 10-year NDVI time-series over multiple polygons using MODIS data.


[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_ndvi.png)](https://www.youtube.com/watch?v=LqSClCXrMl4&list=PLppGmFLhQ1HJV1CctqanQvXQI1JmqGDDD)


[Start Guided Project](https://www.youtube.com/watch?v=LqSClCXrMl4&list=PLppGmFLhQ1HJV1CctqanQvXQI1JmqGDDD)




## 项目 4：土地覆盖分析

Use existing land cover products to extract specific classes and compute statistics across many regions.


[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_landcover.png)](https://youtube.com/playlist?list=PLppGmFLhQ1HLl0St2wiOPePr58sKu0Vh1)


[Start Guided Project](https://youtube.com/playlist?list=PLppGmFLhQ1HLl0St2wiOPePr58sKu0Vh1)






# 学习资源

* [Awesome Earth Engine](https://github.com/giswqs/Awesome-GEE): A curated list of Google Earth Engine resources.




# Data Credits


* **Sentinel-2 Level-1C, Level-2A** and **Sentinel-1 SAR GRD**: Contains Copernicus Sentinel data.
* **TerraClimate: Monthly Climate and Climatic Water Balance for Global Terrestrial Surfaces, University of Idaho**: Abatzoglou, J.T., S.Z. Dobrowski, S.A. Parks, K.C. Hegewisch, 2018, Terraclimate, a high-resolution global dataset of monthly climate and climatic water balance from 1958-2015, Scientific Data 5:170191, <doi:10.1038/sdata.2017.191>
* **VIIRS Stray Light Corrected Nighttime Day/Night Band Composites Version 1**: C. D. Elvidge, K. E. Baugh, M. Zhizhin, and F.-C. Hsu, “Why VIIRS data are superior to DMSP for mapping nighttime lights,” Asia-Pacific Advanced Network 35, vol. 35, p. 62, 2013.
* **FAO GAUL 500m: Global Administrative Unit Layers 2015, Second-Level Administrative Units**: Source of Administrative boundaries: The Global Administrative Unit Layers (GAUL) dataset, implemented by FAO within the CountrySTAT and Agricultural Market Information System (AMIS) projects.
* **CHIRPS Pentad: Climate Hazards Group InfraRed Precipitation with Station Data (version 2.0 final)**: Funk, Chris, Pete Peterson, Martin Landsfeld, Diego Pedreros, James Verdin, Shraddhanand Shukla, Gregory Husak, James Rowland, Laura Harrison, Andrew Hoell & Joel Michaelsen. “The climate hazards infrared precipitation with stations—a new environmental record for monitoring extremes”. Scientific Data 2, 150066. <doi:10.1038/sdata.2015.66> 2015.
* **MOD13Q1.006 Terra Vegetation Indices 16-Day Global 250m**: Didan, K. (2015). *MOD13Q1 MODIS/Terra Vegetation Indices 16-Day L3 Global 250m SIN Grid V006* [Data set]. NASA EOSDIS Land Processes DAAC. Accessed 2021-05-06 from <https://doi.org/10.5067/MODIS/MOD13Q1.006>
* **Natural Earth Urban Areas**: Urban Areas Shapefile. Downloaded from Natural Earth. Free vector and raster map data @ naturalearthdata.com.




# License


The course material (text, images, presentation, videos) is licensed under a [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/).


The code (scripts, Jupyter notebooks) is licensed under the MIT License. For a copy, see <https://opensource.org/licenses/MIT>


Kindly give appropriate credit to the original author as below:


Copyright © 2021 Ujaval Gandhi [www.spatialthoughts.com](https://spatialthoughts.com)




# 引用和参考

你可以这样应用该课程资料
* Gandhi, Ujaval, 2021. *End-to-End Google Earth Engine* Course. Spatial Thoughts. <https://courses.spatialthoughts.com/end-to-end-gee.html>

---

**This course is offered as an instructor-led online class. Visit [Spatial Thoughts](https://spatialthoughts.com/events/) to know details of upcoming sessions.**