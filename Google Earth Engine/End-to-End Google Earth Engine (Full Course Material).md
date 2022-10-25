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
	- [02. 计算指数](#02-计算指数)
		- [练习](#练习-9)
	- [03. 在图像集合上进行计算](#03-在图像集合上进行计算)
		- [练习](#练习-10)
	- [04. 云遮蔽（Cloud Masking）](#04-云遮蔽cloud-masking)
		- [练习](#练习-11)
	- [05. 规约器（Reducer）](#05-规约器reducer)
		- [练习](#练习-12)
	- [06. 时间序列图](#06-时间序列图)
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
			- [续行](#续行)
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
	- [04. 使用 Python 创建图表](#04-使用-python-创建图表)
		- [使用 geemap 创建交互式图表](#使用-geemap-创建交互式图表)
		- [使用 Matplotlib 创建图表](#使用-matplotlib-创建图表)
		- [练习](#练习-31)
	- [05. 自动下载](#05-自动下载)
- [补充](#补充)
	- [高级有监督分类技术](#高级有监督分类技术)
		- [超参数调优](#超参数调优)
		- [后处理分类结果](#后处理分类结果)
		- [主成分分析（PCA）](#主成分分析pca)
		- [作物分类的多时复合](#作物分类的多时复合)
		- [计算相关性](#计算相关性)
		- [计算每个类别的面积](#计算每个类别的面积)
		- [光谱特征图](#光谱特征图)
		- [识别错误分类的 GCP](#识别错误分类的-gcp)
		- [图像归一化和标准化](#图像归一化和标准化)
		- [计算特征重要性](#计算特征重要性)
	- [时序平滑和间隙填充](#时序平滑和间隙填充)
		- [移动窗口平滑](#移动窗口平滑)
		- [时间插值](#时间插值)
		- [Savitzky-Golay 平滑](#savitzky-golay-平滑)
	- [用户界面模版](#用户界面模版)
		- [添加离散图例](#添加离散图例)
		- [添加连续图例](#添加连续图例)
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


模块 2 基于 Earth Engine 基本知识。该模块介绍了使用 Map/Reduce 进行并行编程的概念，这是有效使用 Earth Engine 分析大量数据的关键。你将学习到如何使用 Earth Engine API 计算各种光谱指数，进行云遮罩（cloud masking），然后使用 map/reduce 将这些计算应用于图像集合。你还将学习如何获取长时间序列数据并创建图表。

[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/map_reduce.png)](https://docs.google.com/presentation/d/10qOyxhubkwnsAVjniW54ETgwUHq3DXYKo3HGb6Gemi0/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/10qOyxhubkwnsAVjniW54ETgwUHq3DXYKo3HGb6Gemi0/edit?usp=sharing)


## 01. Earth Engine 对象

该脚本介绍了 Earth Engine API 的基础知识。当在 Earth Engine 中编程时，你必须使用 Earth Engine API，以便你的计算可以使用 Google Earth Engine 服务器。要了解更多信息，请访问 Earth Engine 用户指南中的 [Earth Engine 对象和方法](https://developers.google.com/earth-engine/tutorial_js_02) 部分。

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F01b_Earth_Engine_Objects_(complete))


```js
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
> 一般来说，你应该始终在代码中使用 Earth Engine API 方法，但有一个例外，就是当你需要使用客户端 Javascript 方法的时候。如果你想获取当前时间，但服务器并不知道你的时间。此时，你需要使用 javascript 方法，并将其转换为 Earth Engine 对象。
> 
> 
> 
> ```js
> var now = Date.now()
> print(now)
> var now = ee.Date(now)
> print(now)
> ```
> 
> 


### 练习


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F01c_Earth_Engine_Objects_(exercise))


```js
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




## 02. 计算指数

光谱指数是遥感许多方面的核心。无论是研究植被还是追踪火灾，你都需要计算两个或者更多个波段的像素比率。计算指数最常用的公式是两个波段之间的*归一化差值*。Earth Engine 提供了一个辅助函数 `normalizedDifference()` 来帮助计算归一化指数，例如归一化差异植被指数（NDVI）。对于更复杂的公式，还可以使用 `expression()` 函数来描述计算。

![MNDWI, SAVI 和 NDVI 图像](https://courses.spatialthoughts.com/images/end_to_end_gee/indices.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F02b_Calculating_Indices_(complete))


```js
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

```js
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


## 03. 在图像集合上进行计算

目前，我们已经学习了如何在单个图像进行计算。如果想要对多个图像应用某些计算（例如计算指数），则需要使用 `map()`。首先，定义一个函数，该函数将一个图像作为输入并返回该图像的计算结果。然后，你可以 `map()` 那个函数到数据集上，这会产生一个由计算结果组成的新的 ImageCollection。这类似于你可能熟悉的 *for-loop*，但`map()` 允许计算并行运行。想了解更多，请看[在 ImageCollection 上进行映射](https://developers.google.com/earth-engine/guides/ic_mapping)。


![NDVI computation on an ImageCollection](https://courses.spatialthoughts.com/images/end_to_end_gee/imagecollection_computation.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F03b_Computation_on_Image_Collections_(complete))



```js
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

```js
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

遮蔽图像中的像素会使得这些像素透明，从而将它们排除在分析和可视化之外。要遮蔽图像，我们可以使用 `updateMask()` 函数，其参数是一个只有 0 和 1 值的图像。蒙版图像为 0 的所有像素都会被遮蔽。

大部分的遥感数据集都带有一个 QA 或者 Cloud Mask 波段，其中包含像素是否是云的信息。在*代码编辑器*的 *Scripts Tab → Examples → Cloud Masking* 下，包含了一些适用于流行数据集的云遮蔽预定义函数.

下面的脚本采用了 Sentinel-2 遮蔽函数，并展示了如何将其应用在图像上。

![Applying pixel-wise QA bitmask](https://courses.spatialthoughts.com/images/end_to_end_gee/cloud_masking.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F04b_Cloud_Masking_(complete))


```js
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


```js
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
> 如果使用的是 Sentinel-2 数据，请查看使用 *S2 Cloudless* 数据集的替代云遮蔽技术。[学到更多](https://medium.com/google-earth/more-accurate-and-flexible-cloud-masking-for-sentinel-2-images-766897a9ba5f)
> 
> 
> 
> ```js
> var imageSR = ee.Image('COPERNICUS/S2_SR/20190703T050701_20190703T052312_T43PGP')
> var s2Cloudless = ee.Image('COPERNICUS/S2_CLOUD_PROBABILITY/20190703T050701_20190703T052312_T43PGP')
> var clouds = s2Cloudless.lt(50)
> var cloudlessMasked = imageSR.mask(clouds)
> var rgbVis = {min: 0.0, max: 3000, bands: ['B4', 'B3', 'B2']};
> Map.addLayer(cloudlessMasked, rgbVis, 'S2 Cloudless Masked Image')
> ```
> 
> 

## 05. 规约器（Reducer）

在写并行计算代码时， *Reduce* 操作允许你计算大量输入数据的统计信息。在 Earth Engine 中，你需要在创建组合、计算统计数据、进行回归分析等操作时运行规约操作。Earth Engine API 带有大量的内置规约函数（例如 `ee.Reducer.sum()`, `ee.Reducer.histogram()`, `ee.Reducer.linearFit()`等），可以对输入数据执行各种统计操作。你可以使用 `reduce()` 函数来运行规约器。Earth Engine 支持在任意可以保存多个值的数据结构上运行规约器，例如 Images（规约器在不同波段上运行）、ImageCollection、FeatureCollection、List、Dictionary 等。下面的脚本介绍了与规约器相关的概念。


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F05b_Reducers_(complete))



```js
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



```js
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

## 06. 时间序列图

现在，我们可以将迄今为止所学的所有技能（过滤、映射、规约和云遮蔽）组合在一起，来创建给定农场一年内的平均 NDVI 值图表。Earth Engine API 支持基于 Google Chart API 的图表功能。这里，我们使用 `ui.Chart.image.series()` 函数来创建时间序列图。

![Computing NDVI Time-series for a Farm](https://courses.spatialthoughts.com/images/end_to_end_gee/charts1.png)


![NDVI Time-series showing Dual-Cropping Cycle](https://courses.spatialthoughts.com/images/end_to_end_gee/charts2.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2F06b_Time_Series_Charts_(complete))



```js
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



```js
// Delete the farm boundary from the previous script 
// and add another farm at a location of your choice

// Print the chart.
```


## 作业 2



![Assignment2 Expected Output](https://courses.spatialthoughts.com/images/end_to_end_gee/assignment2.png)


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A02-Earth-Engine-Intermediate%2FAssignment2)



```js
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


有监督分类可以说是遥感中最重要的经典机器学习技术。其应用从生成土地利用/土地覆盖地图到变化检测。Google Earth Engine 非常适合进行大规模的有监督分类。Earth Engine 开发的交互特性允许我们通过将许多不同的数据集组合到模型中，从而进行有监督分类工作流的迭代开发。该模块涵盖了基本的监督分类工作流、准确度评估、超参数调优和变化检测。

[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/supervised_classification.png)](https://docs.google.com/presentation/d/19L1b5vsxb38xS8GlHNKOjvPZ0IGqDhv93681btMEL5w/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/19L1b5vsxb38xS8GlHNKOjvPZ0IGqDhv93681btMEL5w/edit?usp=sharing)


## 01. 有监督分类基础知识

我们将学习如何使用从代码编辑器收集的训练样本（使用谷歌地图提供的高分辨率底图）来进行基本的土地覆盖分类。这种方法不要求先前的训练数据，因此能非常有效地生成世界上任何地方的高质量分类样本。我们的目标是将每个源像素分类为以下类别之一：城市、裸露、水或者植被。使用代码编辑器提供的绘图工具，你可以创建 4 个新的特征集合，每个集合中的像素代表一个类。每个特征集合都有一个名为 `landcover` 的属性，值 0, 1, 2 或者 3 分别代表城市、裸露、水或者植被。然后，我们使用这些训练集来训练一个*随机森林（Random Forest）*分类器，得到一个模型，并将此模型应用于图像中的所有像素以创建一个包含 4 个类的图像。

> 
> 有趣的事实：Earth Engine API 中的分类器的名称以 **smile** 开头，例如 `ee.Classifier.smileRandomForest()`。*smile* 这部分指的是 Google Earth Engine 用来实现这些算法的 [Statistical Machine Intelligence and Learning Engine (SMILE)](https://haifengl.github.io/index.html) JAVA 库。
> 

![有监督分类输出](https://courses.spatialthoughts.com/images/end_to_end_gee/classified.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F01d_Basic_Supervised_Classification_(noimport))



```js
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

```js
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

对分类的准确性进行定量评估是很重要的。为此，常见的策略是将你的训练样本随机分为两个部分：一个用于*训练*模型，而另一个用于*验证*预测。一旦训练出了分类器，就可以将其用于分类整个图像。然后，我们可以将分类值与验证集进行比较。我们可以使用 `ee.Classifier.confusionMatrix()` 方法来计算表示预期准确度的*混淆矩阵（Confusion Matrix）*。

根据以下指标对分类结果进行评估

* **总体准确度（Overall Accuracy）**：有多少样本被正确分类。
* **生产者精度（Producer’s Accuracy）**：分类器对每个类别的预测效果如何。
* **Consumer’s Accuracy (Reliability)**：每个类别的预测有多可靠。
* **Kappa 系数**：与随机分配相比，分类性能如何。


![准确度评估](https://courses.spatialthoughts.com/images/end_to_end_gee/accuracy_assessment.png)

> 
> 不要一味为了追求最高验证准确度而肆意调整模型。你必须同时使用定性衡量（例如结果的可视检查）以及定量衡量来评估结果。
> 
> 

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F02b_Accuracy_Assessment_(complete))



```js
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



```js
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

Earth Engine 数据模型特别适合机器学习任务，因为它能够轻松地将具有不同空间分辨率、投影和数据类型的数据源合并在一起。通过向分类器提供额外的信息，它能够轻松地分开不同的类别。这里，我们采用相同的例子，但使用以下技术对其进行改进。

* *应用云遮蔽（Cloud Masking）*
* *添加光谱指数*：添加不同光谱指数（例如 NDVI、NDBI、MNDWI 和 BSI）作为波段信息。
* *添加高程和坡度*：我们还添加来自 ALOS DEM 的高程和坡度波段.
* *归一化输入数据*：当所有的输入具有相同的规模的时候，机器学习模型效果最好。我们将把所有的波段都除以相应的最大值。这样就保证了所有的输入值都处于 0-1 之间。课程的补充部分提供了一个更[完整和健壮的图像归一化技术](#image-normalization-and-standardization)。


我们的训练特征拥有更多的参数并包含具有相同规模的值。结果大大改进了分类。

![Improved Classification Accuracy with use of Spectral Indices and Elevation Data](https://courses.spatialthoughts.com/images/end_to_end_gee/improving_classification.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F03b_Improving_the_Classification_(complete))


```js
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



```js
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

当在大区域上使用复杂分类器的时候，代码编辑器可能会给你一个 *User memory limit exceeded* 或者 *Computation timed out* 错误。其原因在于，使用 *On-Demand Computation* 模式运行的代码被分配了固定的（运行）时间和较小的内存。对于更大的计算，你可以使用 *Batch* 模式和 `Export` 函数导出在后台进行，并且可以运行超过 5 分钟（这是分配给代码编辑器运行代码的时间）。这允许你处理非常大且复杂的数据集。下面的示例显示了如何将分类结果导出到 Google Drive。

> 
> 我们只能导出 Image 或者 FeatureCollection。那要是你想导出一个长时间计算的结果，而这个结果是一个数值，该怎么办呢？一个有用的*技巧*就是创建一个 FeatureCollection，它包含一个含有 `null` 几何的特征以及一个包含要导出数值的属性。
> 


![导出分类结果](https://courses.spatialthoughts.com/images/end_to_end_gee/export_classification.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F04b_Exporting_Classification_Results_(complete))



```js
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

将已分类的图像作为资产导出也是个好主意。这将允许你在另一个脚本中导入该已分类图像，而无需运行整个分类工作流程。使用 Export.image.toAsset() 函数将已分类图像作为资产导出。

[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F04c_Exporting_Classification_Results_(exercise))


```js
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

现在，我们有了分类结果，我们将学习如何计算每个类的像素面积。对于特征，使用 `area()` 函数来计算面积，而对于图像，则使用 `ee.Image.pixelArea()` 函数。`ee.Image.pixelArea()` 函数创建一个图像，该图像的每个像素值是这个图像的面积。我们将该像素面积图像与我们的图像相乘，然后使用 `reduceRegion()` 函数对结果求和。


> 
> `ee.Image.pixelArea()` 函数使用自定义的等面积投影进行面积计算。无论输入图像的投影是什么，结果都是以平方米为单位的面积。[学习更多](https://groups.google.com/g/google-earth-engine-developers/c/Ccaorx-obVw/m/_ZQdP2wVAgAJ)
> 


![Calculating Green Cover from Classified Image](https://courses.spatialthoughts.com/images/end_to_end_gee/area_calculation.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F05b_Calculating_Area_(complete))


```js
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
> 如果想要计算每个类别覆盖的面积，可以使用 [Grouped Reducer](https://developers.google.com/earth-engine/reducers_grouping)。请参阅[补充](#calculating-area-by-class)以查看代码片段。
> 


### 练习

[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A03-Supervised-Classification%2F05c_Calculating_Area_(exercise))



```js
// Exercise
// Compute and print the percentage green cover of the city
```





# 模块 4: 变化检测


## 变化检测简介

许多地球观测数据集是会在很长一段时间内定期提供的。这让我们可以检测到地球表面的变化。遥感中的的变化检测技术分为以下几类

* **单波段变化**：通过阈值，测量单波段图像或者光谱指数的变化
* **多波段变化**：测量两个多波段图像之间的光谱距离和光谱角度
* **变化分类**：使用包含事件前后波段的堆叠图像进行单次分类
* **分类后比较**：比较两个已分类图像并计算类转换

在以下部分中，我们将应用有监督分类技术，使用多时相图像进行变化检测。

[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/change_detection.png)](https://docs.google.com/presentation/d/1vdFTWJ61yDuVfbfhpnumQ8zuMPGwGcHpHsBTRgo_o5I/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/1vdFTWJ61yDuVfbfhpnumQ8zuMPGwGcHpHsBTRgo_o5I/edit?usp=sharing)



## 01. 光谱指数变化

许多类型的变化都可以通过测量光谱指数的变化并应用阈值来检测。当对于你有兴趣检测的变化类型，存在合适的光谱指数的时候，就可以应用这项技术。

这里，我们使用这项技术来绘制森林火灾的范围和严重程度。**Normalized Burn Ratio (NBR)** 是一种指数，旨在突出显示被毁植被区域。我们可以计算前后图像的 NBR 值。然后应用一个合适的阈值来找到烧焦的区域。

![Spectral Index Change Detection](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_index_change.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01b_Spectral_Index_Change_(complete))



```js
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


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01c_Spectral_Index_Change_(exercise))


```js
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

当你想要检测多波段图像的变化的时候，一项有用的技术是计算两个图像之间的光谱距离和光谱角度。与那些未发生变化的像素相比，发生较大变化的像素具有更大的距离。当没有合适的指数来检测变化的时候，这项技术特别有用。它可用于检测自然灾害或者人为冲突造成的变化。

这里，我们使用这项技术在前后复合图像上检测滑坡。在 [Craig D’Souza 的变化检测](https://goo.gl/xotYhk)演示文稿中，你可以了解有关这项技术的更多信息。

![Spectral Distance Change Detection](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_distance.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F01b_Spectral_Distance_Change_(complete))



```js
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



```js
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

这种变化检测技术也称为 *One-pass Classification* 或者 *Direct Multi-date Classification*。这里，我们创建一个包含前后图像波段的堆叠图像。我们使用从堆叠图像采样得到的训练数据来训练分类器，并将其应用在该堆叠图像上，以查找所有变化像素。


![All pixels that changed from bare ground to built-up](https://courses.spatialthoughts.com/images/end_to_end_gee/change_classification.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F03b_Classifying_Change_(complete))



```js
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

```js
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

在处理多类图像的过程中，一个用于变化检测的有用的指数是指导有多少像素从类 X 变成类 Y。这可以使用 `ee.Reducer.frequencyHistogram()` reducer 来实现，如下所示。

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F04b_Post_Classification_Comparison_(complete))

```js
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


[在代码编辑器中试一试 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3A04-Change-Detection%2F04c_Post_Classification_Comparison_(exercise))


```js
// Exercise
// Show all areas where water became other classes and display the result
// Hint1: Select class 3 pixels from before image and NOT class 3 pixels from after image
// Hint2: use the .and() operation to select pixels matching both conditions
```


# 模块 5: Earth Engine 应用

This module is focused the concepts related to client vs. server that will help you in creating web apps. We will be building an app using the Earth Engine User Interface API and publishing it to Google Cloud.



## 01. 客户端与服务器

The User Interface elements in your Code Editor - Map View, Drawing Tools etc. are ‘client-side’ elements. They run in YOUR browser. Image Collections, feature collections, calculations on Earth Engine objects etc. are ‘server-side’ elements. They run in Google’s data center. You cannot mix both these objects. 要了解更多信息，visit the [Client vs. Server](https://developers.google.com/earth-engine/guides/client_server) section of the Earth Engine User Guide.


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



```js
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

目前为止，我们已经将 Earth Engine Javascript API 用于所有的分析中。Earth Engine 还提供了 Python API。如果你是 Python 开发者，那么你可能更喜欢使用 Python API 来将 Earth Engine 整合到你的空间分析工作流中。运行使用 Google Earth Engine API 的  Python 代码有多种方法。在本课程中，我们将使用以下两种方法。

[![View Presentation](https://courses.spatialthoughts.com/images/end_to_end_gee/python_api.png)](https://docs.google.com/presentation/d/1hPVRnxp2Vp1VHXBtu36SH_UtEOjPz70KcDV-zGIin3U/edit?usp=sharing)


[查看演示文档 ↗](https://docs.google.com/presentation/d/1hPVRnxp2Vp1VHXBtu36SH_UtEOjPz70KcDV-zGIin3U/edit?usp=sharing)



### Google Colab

开始使用 Google Earth Engine Python API 的一种简单方法是通过 [Google Colab](https://colab.research.google.com/)。Google Colaboratory 提供了一个托管环境来运行 Python 笔记本，无需在本地安装 Python。它还预安装了许多有用的包，包括 Google Earth Engine Python API。你可以简单访问 <https://colab.research.google.com/>，然后开始一个新的笔记本。


### 本地开发环境

Python API 的一个优点是你可以在自己的开发环境中使用它，因此，你可以更灵活地实现自动化，还可以将其他分析和可视化库与 Earth Engine 结合在一起。这就要求你在自己的机器或者服务器上安装 Python 和 Earth Engine Python API 了。你还需要进行一次身份验证，然后将令牌保存在自己的机器上。安装 Earth Engine Python API 的首选方式是通过 Anaconda。请跟着我们的 [Google Earth Engine Python API 安装指南](install-gee-python-api.html)一步一步进行操作。

## 01. Python API 语法


[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/01_python_api_syntax.ipynb)

通过代码编辑器在 Earth Engine 中进行编程后，你需要稍微调整脚本才能在 Python 中运行。对于大部分代码，你将使用 Earth Engine API 的服务端对象和函数，这在 Python 中完全相同。你只需要进行一些语法更改。

[这是完整的差异列表](https://developers.google.com/earth-engine/python_install#syntax)。



#### 初始化

首先，你需要运行以下单元来初始化 API 并授权账户。系统将提示你登录账户，并且允许访问 *View and Manage your Earth Engine data*。一旦接受后，你将获得一个验证码，并且需要在提示下输入此验证码。每个会话只需要执行此步骤一次。

```py
import ee
```

```py
ee.Authenticate()
```


```py
ee.Initialize()
```



#### 变量


Python 代码并不使用 ‘var’ 关键词

javascript 代码：


```js
var city = 'San Fransico'
var state = 'California'
print(city, state)

var population = 881549
print(population)
```


```py
city = 'San Fransico'
state = 'California'
print(city, state)

population = 881549
print(population)
```



#### Earth Engine 对象

你可以通过相同的方式，使用 `ee` 函数创建 Earth Engine 对象。


```py
s2 = ee.ImageCollection('COPERNICUS/S2')
geometry = ee.Geometry.Polygon([[
 [82.60642647743225, 27.16350437805251],
 [82.60984897613525, 27.1618529901377],
 [82.61088967323303, 27.163695288375266],
 [82.60757446289062, 27.16517483230927]
]])
```



#### 续行

Python 不使用分号作为结尾。要表示行继续，你需要使用 \ 字符。

javascript 代码：

```js
var s2 = ee.ImageCollection('COPERNICUS/S2');
var filtered = s2.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-02-01', '2019-03-01'))
  .filter(ee.Filter.bounds(geometry));
```


```py
filtered = s2 \
 .filter(ee.Filter.lt('CLOUDY\_PIXEL\_PERCENTAGE', 30)) \
 .filter(ee.Filter.date('2019-02-01', '2019-03-01')) \
 .filter(ee.Filter.bounds(geometry))
```



#### 函数

Python 使用 `def` 关键字而不是 `function` 关键字。此外，内联函数是使用 `lambda` 匿名函数来定义的。

在下面的例子中，现在 `and` 操作符（Python 版本是首字母大写的 `And`）也被更改以避免与内建的 `and` 操作符冲突。`Or` 和 `Not` 操作符同理。Python 中的 `true`, `false`, `null` 分别对应 `True`, `False` 和 `None`。


javascript 代码：

```js
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


```py
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

Earth Engine 函数的命名参数需要使用引号将其包起来。此外，当命名参数作为字典传递时，还需要 `**` 关键字。

javascript 代码：

```js
var composite = withNdvi.median();
var ndvi = composite.select('ndvi');

var stats = ndvi.reduceRegion({
    reducer: ee.Reducer.mean(),
    geometry: geometry,
    scale: 10,
    maxPixels: 1e10
})    
```


```py
composite = withNdvi.median()
ndvi = composite.select('ndvi')

stats = ndvi.reduceRegion(**{
 'reducer': ee.Reducer.mean(),
 'geometry': geometry,
 'scale': 10,
 'maxPixels': 1e10
 })
```



#### 打印值

`print()` 函数的语法相同。但必须记住，在代码编辑器中，当你使用 `print` 的时候，服务器对象的值会先被提取再被打印。因此，你必须通过对任何服务端对象调用 `getInfo()` 方法来明确做到这一点。


javascript 代码：

```js
print(stats.get('ndvi')
```


```py
print(stats.get('ndvi').getInfo())
```



#### 内联函数

定义内联函数的语法也略有不同。需要使用 `lambda` 关键字。


javascript 代码：

```js
var myList = ee.List.sequence(1, 10);
var newList = myList.map(function(number) {
    return ee.Number(number).pow(2);
print(newList);
```


```py
myList = ee.List.sequence(1, 10)
newList = myList.map(lambda number: ee.Number(number).pow(2))
print(newList.getInfo())
```



### 练习

获取下面的 Javascript 代码片段，然后在下面的单元中写出等效的 Python 代码。


* **提示1**：链接过滤器需要使用换行符 `\`
* **提示2**：打印服务端对象需要在对象上调用 `.getInfo()`

正确的代码应该打印值 **30**。




---



```js
var geometry = ee.Geometry.Point([77.60412933051538, 12.952912912328241]);

var s2 = ee.ImageCollection('COPERNICUS/S2');

var filtered = s2.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(geometry));
  
print(filtered.size());
```



---



```py
import ee
ee.Authenticate()
ee.Initialize()
```




## 02. Javascript 代码到 Python 到自动转换


[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/02_automatic_conversion_of_scripts.ipynb)



![Interactive leaflet map created by geemap](https://courses.spatialthoughts.com/images/end_to_end_gee/automatic_conversion.png)

[geemap](https://github.com/giswqs/geemap) 是一个开业 Python 包，它有许多有用的功能，能帮你在 Python 中有效使用 Earth Engine。

它有一个函数，可以帮你将javascript earth engine 代码自动转换为 Python。

Google Colab 没有预安装这个包，所以我们需要通过 pip 进行安装。


```py
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

代码的自动转换时通过调用 `geemap.js_snippet_to_py()` 函数来完成的。首先，我们使用javascript 代码创建一个字符串。


```js
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


```py
lines = geemap.js_snippet_to_py(
    javascript_code, add_new_cell=False,
    import_ee=True, import_geemap=True, show_map=True)
for line in lines:
    print(line.rstrip())
```

自动转换的效果很好。查看并将其粘贴到下面的单元格中。


```py
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
      .select("B.*") \
      .copyProperties(image, ["system:time_start"])

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

获取下面的 Javascript 代码片段并使用 `geemap` 来自动将其转换成 Python 代码。


---



```js
var admin2 = ee.FeatureCollection("FAO/GAUL_SIMPLIFIED_500m/2015/level2");

var karnataka = admin2.filter(ee.Filter.eq('ADM1_NAME', 'Karnataka'))

var visParams = {color: 'red'}
Map.centerObject(karnataka)
Map.addLayer(karnataka, visParams, 'Karnataka Districts')
```



---





## 03. 批量导出

[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/03_export_a_collection.ipynb)

Earth Engine 用户最常问的问题之一是 *如何下载集合中的所有图像*？Earth Engine Python API 有一个 `ee.batch` 模块，它允许我们启动批量导出和管理任务。像这样进行批量导出的推荐方式是使用 Python API 的 `ee.batch.Export` 函数，并使用 Python 的 for 循环来迭代导出每个图像。`ee.batch` 模块还让你可以控制*任务*，允许你自动导出。



```py
import ee
```


```py
ee.Authenticate()
```


```py
ee.Initialize()
```


#### 创建一个 Collection



```py
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
      .select("B.*") \
      .copyProperties(image, ["system:time_start"])

filtered = s2 \
  .filter(ee.Filter.date('2019-01-01', '2020-01-01')) \
  .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30)) \
  .filter(ee.Filter.bounds(geometry)) \
  .map(maskS2clouds)

# Write a function that computes NDVI for an image and adds it as a band
def addNDVI(image):
  ndvi = image.normalizedDifference(['B5', 'B4']).rename('ndvi')
  return image.addBands(ndvi)

withNdvi = filtered.map(addNDVI)

```



#### 导出所有图像

导出是通过 `ee.batch` 模块来完成的。javascript 和 Python 版本之间的一个关键区别是 `region` 参数需要提供实际的几何坐标。



```py
image_ids = withNdvi.aggregate_array('system:index').getInfo()
print('Total images: ', len(image_ids))
```


```py
# Export with 100m resolution for this demo
for i, image_id in enumerate(image_ids):
  image = ee.Image(withNdvi.filter(ee.Filter.eq('system:index', image_id)).first())
  task = ee.batch.Export.image.toDrive(**{
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

你也可以管理任务。获取任务列表并获取这些任务的状态信息。


```py
tasks = ee.batch.Task.list()
for task in tasks:
 task_id = task.status()['id']
 task_state = task.status()['state']
 print(task_id, task_state)
```

你也可以取消任务


```py
tasks = ee.batch.Task.list()
for task in tasks:
    task_id = task.status()['id']
    task_state = task.status()['state']
    if task_state == 'RUNNING' or task_state == 'READY':
        task.cancel()
        print('Task {} canceled'.format(task_id))
    else:
        print('Task {} state is {}'.format(task_id, task_state))
```



### 练习

下面的代码使用 TerraClimate 数据并创建一个包含 12 个月最高温度的图像的 ImageCollection。它还从 LSIB 集合中抽取澳大利亚的几何图形。添加代码以启动导出任务，导出澳大利亚集合中的每个图像。

* **提示1**：TerraClimate 图像的比例尺为 4638.3m
* **提示2**：你需要导出 clippedImage 变量中包含的图像。

```py
import ee

lsib = ee.FeatureCollection('USDOS/LSIB_SIMPLE/2017')
australia = lsib.filter(ee.Filter.eq('country_na', 'Australia'))
geometry = australia.geometry()

terraclimate = ee.ImageCollection('IDAHO_EPSCOR/TERRACLIMATE')
tmax = terraclimate.select('tmmx')

def scale(image):
  return image.multiply(0.1) \
    .copyProperties(image,['system:time_start'])

tmaxScaled = tmax.map(scale)

filtered = tmaxScaled \
  .filter(ee.Filter.date('2020-01-01', '2021-01-01')) \
  .filter(ee.Filter.bounds(geometry))

image_ids = filtered.aggregate_array('system:index').getInfo()
print('Total images: ', len(image_ids))
```

将注释替换成你的代码。

```py
for i, image_id in enumerate(image_ids):
    exportImage = ee.Image(filtered.filter(ee.Filter.eq('system:index', image_id)).first())
    # Clip the image to the region geometry
    clippedImage = exportImage.clip(geometry)
    
    ## Create the export task using ee.batch.Export.image.toDrive()
    
    ## Start the task
```


![Launching multiple tasks using the  Python API](https://courses.spatialthoughts.com/images/end_to_end_gee/exporting_a_collection.png)


## 04. 使用 Python 创建图表


[在 Google Colab 中打开 ↗](https://colab.research.google.com/github/spatialthoughts/courses/blob/master/code/end_to_end_gee/04_creating_charts.ipynb)


Google Earth Engine Python API 不包含图表模块。但你可以使用第三方模块来创建交互式图表。你还可以将 Earth Engine 对象转换成 Pandas dataframe，然后使用像 Matplotlib 这样的 Python 库对其进行绘制

本笔记本展示了如何使用 `geemap` 包，从 ImageCollection 创建时间序列图表。

参考：

* geemap [Chart 模块](https://geemap.org/chart/)
* geemap [示例笔记本](https://geemap.org/notebooks/63_charts/)



```py
import ee
```


```py
try:
 import geemap
except ModuleNotFoundError:
 if 'google.colab' in str(get_ipython()):
 print('geemap not found, installing via pip in Google Colab...')
 !pip install geemap --quiet
 import geemap
 else:
 print('geemap not found, please install via conda in your environment')
```


```py
ee.Authenticate()
```


```py
ee.Initialize()
```

加载 TerraClimate 集合并选择 ‘tmmx’ 波段。

```py
terraclimate = ee.ImageCollection("IDAHO_EPSCOR/TERRACLIMATE")
tmax = terraclimate.select('tmmx')
```

定义图表的点位置。


```py
geometry = ee.Geometry.Point([77.57738128916243, 12.964758918835752])
```

缩放波段值，使其以摄氏度为单位。


```py
def scale_image(image):
 return ee.Image(image).multiply(0.1)\
 .copyProperties(image, ['system:time_start'])

tmaxScaled = tmax.map(scale_image)
```

过滤集合。


```py
filtered = tmaxScaled.filter(ee.Filter.date('2019-01-01', '2020-01-01')) \
 .filter(ee.Filter.bounds(geometry))
```

要在 Python 中绘制图像序列，首先我们必须从每个图像中提取值，然后创建 FeatureCollection。



```py
def extract_data(image):
    stats = image.reduceRegion(**{ 
        'reducer':ee.Reducer.mean(),
        'geometry':geometry,
        'scale':5000
    })
    properties = {
        'month': image.get('system:index'),
        'tmmx': stats.get('tmmx')
    }
    return ee.Feature(None, properties)

data = ee.FeatureCollection(filtered.map(extract_data))
```


```py
print(data.first().getInfo())
```


### 使用 geemap 创建交互式图表



```py
from geemap import chart
```


```py
options = {
 'title': 'Max Monthly Temperature at Bangalore', 
 'legend_location': 'top-right',
 'height': '500px',
 'ylabel': 'Temperature (C)',
 'xlabel': 'Date',
 'colors': ['blue']
}
```


```py
chart.feature_byFeature(data, 'month', ['tmmx'], **options)
```



### 使用 Matplotlib 创建图表


使用 `geemap` 提供的辅助函数 `ee_to_pandas`，我们可以将 FeatureCollection 转换为 DataFrame。



```py
import geemap
df = geemap.ee_to_pandas(data)
```


```py
df
```

现在，我们有了一个常规的 Pandas dataframe，就可以使用 `matplotlib` 来绘制了。


```py
%matplotlib inline
import matplotlib.pyplot as plt
```


```py
fig, ax = plt.subplots()
fig.set_size_inches(20,10)


df.plot(ax=ax,
 title='Max Monthly Temperature at Bangalore',
 x='month',
 ylabel='Temperature (C)',
 kind='line')
plt.tight_layout()
```



### 练习

将上面的图表绘制为红色的折线图。

* **提示1**：使用 `kind='line'` 和 `color` 选项。



## 05. 自动下载

GEE Python API 的另一个常见用途是自动化数据处理和导出。你可以创建一个 Python 脚本，然后通过服务器调用，或者使用像 [Windows Scheduler](https://medium.com/@roddyjaques/how-to-run-anaconda-programs-with-a-bat-file-5f6dd7675508) 或者 [crontab](https://donny-son.github.io/posts/cronjob-with-conda/) 这样的工具来调度。

下面的脚本提供了一个使用 Google Earth Engine API 进行自动下载的完整示例。它使用 Google Earth Engine API 计算过去 2 周内一个州所有地区的平均土壤湿度。然后将结果以 JSON 文件的形式下载并保存在本地。

> 
> 在运行脚本之前，请确保你已经完成了[一次身份验证流程](install-gee-python-api.html#authentication)。
> 
> 

按照以下步骤创建脚本来从 GEE 下载数据。

1. 新建一个名为 `download_data.py` 的文件，其内容如下所示。

```py
import datetime
import ee
import csv
import os

ee.Initialize()

# Get current date and convert to milliseconds 
end_date = ee.Date(datetime.datetime.now().timestamp()*1000)
start_date = end_date.advance(-2, 'week')

date_string = end_date.format('YYYY_MM_dd')
filename = 'ssm_{}.csv'.format(date_string.getInfo())

# Saving to current directory. You can change the path to appropriate location
output_path = os.path.join(filename)

# Datasets
soilmoisture = ee.ImageCollection("NASA_USDA/HSL/SMAP10KM_soil_moisture")
admin2 = ee.FeatureCollection("FAO/GAUL_SIMPLIFIED_500m/2015/level2")

# Filter to a state
karnataka = admin2.filter(ee.Filter.eq('ADM1_NAME', 'Karnataka'))

# Select the ssm band
ssm  = soilmoisture.select('ssm')

filtered = ssm .filter(ee.Filter.date(start_date, end_date))

mean = filtered.mean()

stats = mean.reduceRegions(**{
  'collection': karnataka,
  'reducer': ee.Reducer.mean().setOutputs(['meanssm']),
  'scale': 10000,
  'crs': 'EPSG:32643'
  })

# Select columns to keep and remove geometry to make the result lightweight
# Change column names to match your uploaded shapefile
columns = ['ADM2_NAME', 'meanssm']
exportCollection = stats.select(**{
    'propertySelectors': columns,
    'retainGeometry': False})

features = exportCollection.getInfo()['features']

data = []

for f in features:
    data.append(f['properties'])

field_names = ['ADM2_NAME', 'meanssm']

with open(output_path, 'w') as csvfile:
    writer = csv.DictWriter(csvfile, fieldnames = field_names)
    writer.writeheader()
    writer.writerows(data)
    print('Success: File written at', output_path)
```

1. 在终端，导航到该文件所在目录，然后输入以下命令运行脚本。

```sh
python download_data.py
```

![](https://courses.spatialthoughts.com/images/end_to_end_gee/download2.png)


3. 该脚本将从 GEE 下载数据并将文件保存在当前目录。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/download3.png)




# 补充

本部分包含可用于你的项目都有用脚本和代码片段。


## 高级有监督分类技术


### 超参数调优

提高机器学习准确性推荐的最佳实践是调整不同的参数。例如，当使用 `ee.Classifier.smileRandomForest()` 分类器时，必须指定  *Number of Trees*。我们知道，树越多，计算需求也越多，但这却不一定会有更好的效果。除了猜测，我们可以以编程的方式尝试一系列值，然后选择具有最高准确度的最小的值。

![Supervised Classification Output](https://courses.spatialthoughts.com/images/end_to_end_gee/hyperparameter_tuning.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FHyperparameter_Tuning)



```js
var s2 = ee.ImageCollection("COPERNICUS/S2_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy_gcps");
var alos = ee.Image("JAXA/ALOS/AW3D30/V2_2");


var arkavathy = basin.filter(ee.Filter.eq('HYBAS_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
  min: 0.0,
  max: 3000,
  bands: ['B4', 'B3', 'B2'],
};
// Function to remove cloud and snow pixels from Sentinel-2 SR image

function maskCloudAndShadowsSR(image) {
  var cloudProb = image.select('MSK_CLDPRB');
  var snowProb = image.select('MSK_SNWPRB');
  var cloud = cloudProb.lt(10);
  var scl = image.select('SCL'); 
  var shadow = scl.eq(3); // 3 = cloud shadow
  var cirrus = scl.eq(10); // 10 = cirrus
  // Cloud probability less than 10% or cloud shadow classification
  var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
  return image.updateMask(mask);
}


var filtered = s2
.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(boundary))
  .map(maskCloudAndShadowsSR)
  .select('B.*')

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
        'Y': image.select('B4'),  //red
        'A': image.select('B8'), // nir
        'B': image.select('B2'), // blue
  }).rename('bsi');
  return image.addBands(ndvi).addBands(ndbi).addBands(mndwi).addBands(bsi)
}

var composite = addIndices(composite);


// Calculate Slope and Elevation
var elev = alos.select('AVE_DSM').rename('elev');
var slope = ee.Terrain.slope(alos.select('AVE_DSM')).rename('slope');

var composite = composite.addBands(elev).addBands(slope);



// Normalize the image 

// Machine learning algorithms work best on images when all features have
// the same range

// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//************************************************************************** 
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

//************************************************************************** 
// Feature Importance
//************************************************************************** 

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

//************************************************************************** 
// Hyperparameter Tuning
//************************************************************************** 

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
  description: 'Multiple_Parameter_Tuning_Results',
  folder: 'earthengine',
  fileNamePrefix: 'numtrees_bagfraction',
  fileFormat: 'CSV'}) 

 
```



### 后处理分类结果

有监督分类结果通常包含由错误分类的像素引起的椒盐噪声。通常最好应用一些后处理技术来消除这种噪声。下面的脚本包含了用于后处理分类结果的两种流行技术。

* 使用无监督聚类将分类值替换为每个聚类中的多数值。
* 使用众数滤波，将孤立像素的值替换为周围像素的值。

> 
> 请记住，领域方法是和比例相关的，因此，结果会随着你放大或缩小而改变。以所需比例导出结果，看看后处理的效果。
> 


![](https://courses.spatialthoughts.com/images/end_to_end_gee/post_processing.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FPost_Processing_Classification_Results)



```js
// Sentinel-2 Median Composite
var composite = ee.Image("users/ujavalgandhi/e2e/arkavathy_2019_composite");
Map.addLayer(composite, {min: 0, max: 0.3,   bands: ['B4', 'B3', 'B2']}, 'RGB Composite');

// Raw Supervised Classification Results
var classified = ee.Image("users/ujavalgandhi/e2e/arkavathy_final_classification");
Map.addLayer(classified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']}, 'Original');
Map.centerObject(classified, 10)


//************************************************************************** 
// Post process by clustering
//************************************************************************** 

// Cluster using Unsupervised Clustering methods
var seeds = ee.Algorithms.Image.Segmentation.seedGrid(5);

var snic = ee.Algorithms.Image.Segmentation.SNIC({
  image: composite.select('B.*'), 
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


//************************************************************************** 
// Post process by replacing isolated pixels with surrounding value
//************************************************************************** 

// count patch sizes
var patchsize = classified.connectedPixelCount(40, false);

// run a majority filter
var filtered = classified.focal_mode({
    radius: 10,
    kernelType: 'square',
    units: 'meters',
}); 
  
// updated image with majority filter where patch size is small
var connectedClassified =  classified.where(patchsize.lt(25),filtered);
Map.addLayer(connectedClassified, {min: 0, max: 3, palette: ['gray', 'brown', 'blue', 'green']},
  'Processed using Connected Pixels');

```



### 主成分分析（PCA）

PCA 是一种非常有用的技术，可以用来改善你的有监督分类结果。它是一种统计技术，可以将大量波段中的数据压缩成较少的不相关波段。你可以在你的图像上运行 PCA，然后在进行训练点采样之前将前几个（通常是 3 个）主成分波段添加到原始的合成图像中。在下面的例子中，你会注意到具有 13 个波段的原始图像的 97% 的方差是从具有 3 个波段的 PCA 图像中捕获的。这会向分类器发送更强的信号，并通过更好地区分不同的类别来提高准确度。

![](https://courses.spatialthoughts.com/images/end_to_end_gee/pca.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FPrincipal_Components_Analysis)



```js
// Script showing how to do Principal Component Analysis on images
var composite = ee.Image("users/ujavalgandhi/e2e/arkavathy_2019_composite");
var boundary = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy_boundary");

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
  description: 'Principal_Components_Image',
  assetId: 'users/ujavalgandhi/e2e/arkavathy_pca',
  region: geometry,
  scale: scale,
  maxPixels: 1e10})
// Once the export finishes, import the asset and display
var pcaImported = ee.Image('users/ujavalgandhi/e2e/arkavathy_pca')
var pcaVisParams = {bands: ['pc1', 'pc2', 'pc3'], min: -2, max: 2};

Map.addLayer(pcaImported, pcaVisParams, 'Principal Components');


//************************************************************************** 
// Function to calculate Principal Components
// Code adapted from https://developers.google.com/earth-engine/guides/arrays_eigen_analysis
//************************************************************************** 
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
  // a region in which to perform the analysis.  It returns the
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



### 作物分类的多时复合

作物分类是一个难题。有助于清楚区分作物的一项有用技术是解释作物物候。该技术可用于检测特定类型的作物，或者将作物从其他形式的植被中区分开来。你可以为不同时期的作物周期创建复合图像，然后创建堆叠图像以用于分类。这允许分类器学习时间模式以及检测表现出相似模式的像素。


![Capturing Crop Phenology through Seasonal Composites](https://courses.spatialthoughts.com/images/end_to_end_gee/seasonal_composite.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FSeasonal_Composites_for_Crop_Classification)



```js
var s2 = ee.ImageCollection("COPERNICUS/S2_SR")
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas_7")
var arkavathy = basin.filter(ee.Filter.eq('HYBAS_ID', 4071139640))
var boundary = arkavathy.geometry()
Map.centerObject(boundary, 11)

// Function to remove cloud pixels from Sentinel-2 SR image 
function maskCloudAndShadowsSR(image) {
  var cloudProb = image.select('MSK_CLDPRB');
  var snowProb = image.select('MSK_SNWPRB');
  var cloud = cloudProb.lt(10);
  var scl = image.select('SCL'); 
  var shadow = scl.eq(3); // 3 = cloud shadow
  var cirrus = scl.eq(10); // 10 = cirrus
  // Cloud probability less than 10% or cloud shadow classification
  var mask = cloud.and(cirrus.neq(1)).and(shadow.neq(1));
  return image.updateMask(mask).divide(10000)
    .copyProperties(image, ['system:time_start']);
}


var filtered = s2
  .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(boundary))
  .map(maskCloudAndShadowsSR)
// There are 3 distinct crop seasons in the area of interest
// Jan-March = Winter (Rabi) Crops
// April-June  = Summer Crops / Harvest
// July-December = Monsoon (Kharif) Crops
var cropCalendar = ee.List([[1,3], [4,6], [7,12]])

// We create different composites for each season
var createSeasonComposites = function(months) {
  var startMonth = ee.List(months).get(0)
  var endMonth = ee.List(months).get(1)
  var monthFilter = ee.Filter.calendarRange(startMonth, endMonth, 'month')
  var seasonFiltered = filtered.filter(monthFilter)
  var composite = seasonFiltered.median()
  return composite.select('B.*').clip(boundary)
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

帮助作物分类的一种有用技术是对降水和植被变化之间的相关性进行建模。这使得模型能够捕获对降雨对不同反应（即雨水灌溉作物 vs 永久森林）。首先，准备一个图像集，其中每个图像都由 2 个波段组成—— 每个月都累积降雨量和下个月的平均 NDVI。这将为每年创建 11 张图像，其中，图像的每个像素显示降水和滞后一个月的 NDVI。然后，使用 `ee.Reducer.pearsonsCorrelation()` 缩减集合，输出一个 `correlation` 波段。正值表示将水导致 NDVI 增加的区域。将这个波段添加到用于分类的输入图像将极大地帮助分类器分离不同类型的植被。

[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FRainfall_NDVI_Correlation)



```js
// Calculate Rainfall-NDVI Correlation
var geometry = ee.Geometry.Point([75.71168046831512, 13.30751919691132]);
Map.centerObject(geometry, 10)
var s2 = ee.ImageCollection("COPERNICUS/S2_SR");

var rgbVis = {
  min: 0.0,
  max: 3000,
  bands: ['B4', 'B3', 'B2'],
};


// Function to remove cloud and snow pixels from Sentinel-2 SR image
function maskCloudAndShadowsSR(image) {
  var cloudProb = image.select('MSK_CLDPRB');
  var snowProb = image.select('MSK_SNWPRB');
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



### 计算每个类别的面积

该代码片段显示了如何使用 [Grouped Reducer](https://developers.google.com/earth-engine/guides/reducers_grouping) 来计算已分类图像中每个类别覆盖的面积。它还展示了如何使用 `ui.Chart.image.byClass()` 函数创建一个显示每个类别面积的图表。


![](https://courses.spatialthoughts.com/images/end_to_end_gee/area_by_class.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FCalculating_Area_by_Class)



```js
var classified = ee.Image("users/ujavalgandhi/e2e/bangalore_classified");
var bangalore = ee.FeatureCollection("users/ujavalgandhi/public/bangalore_boundary");

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



### 光谱特征图

对于有监督分类，可视化每个类别的每个波段的平均光谱响应很有用。这种图称为 *Spectral Response Curves* 或者 *Spectral Signatures*。这样的图表有助于确定类的可分离性。如果类具有非常不同的签名，那么分类器将能够很好地分离它们。

我们还可以绘制一个类的所有训练样本的光谱特征，并检查训练数据集的质量。如果所有训练样本都显示出相似的特征，这就表明你在收集适当样本方面做得很好。你还可以从这些图中捕获潜在的异常值。

这些图表提供了用于检查类可分离性的定性和可视化方法。对于定量方法，可以应用诸如光谱距离、马氏距离、Bhattacharyya 距离、Jeffreys-Matusita (JM) 距离等度量方法。你可以在[这个 Stack Exchange 回答](https://gis.stackexchange.com/a/323778/5160)中找到对应的代码。

![Mean Signatures for All Classes](https://courses.spatialthoughts.com/images/end_to_end_gee/mean_signatures.png)



![Spectral Signatures for All Training Points by Class](https://courses.spatialthoughts.com/images/end_to_end_gee/spectral_signatures.png)



[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FSpectral_Signatures)



```js
var gcps = ee.FeatureCollection("users/ujavalgandhi/e2e/bangalore_gcps");
var composite = ee.Image('users/ujavalgandhi/e2e/bangalore_composite');

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

在进行准确性评估的时候，你会看到未正确分类的验证特征。直观地查看被错误分类的点很有用。我们可以使用 `ee.Filter.eq()` 和 `ee.Filter.neq()` 过滤器来过滤那些实际类别和预测类别不同的特征。下面的代码显示了如何实现这一点，并使用 `style()` 函数有效地进行可视化。


[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FIdentify_Misclassified_Data)



```js
// Script that shows how to apply filters to identify
// validation points that were misclassified
var s2 = ee.ImageCollection("COPERNICUS/S2_SR");
var basin = ee.FeatureCollection("WWF/HydroSHEDS/v1/Basins/hybas_7");
var gcp = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy_gcps");

Map.centerObject(gcp)
var arkavathy = basin.filter(ee.Filter.eq('HYBAS_ID', 4071139640))
var boundary = arkavathy.geometry()
var rgbVis = {
  min: 0.0,
  max: 3000,
  bands: ['B4', 'B3', 'B2'],
};
 
var filtered = s2
.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(boundary))
  .select('B.*')

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

对于机器学习，推荐归一化或者标准化特征。下面的代码展示了如何实现这些特征缩放技术。


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FImage_Normalization_and_Standardization)



```js
var image = ee.Image("users/ujavalgandhi/e2e/arkavathy_2019_composite");
var boundary = ee.FeatureCollection("users/ujavalgandhi/e2e/arkavathy_boundary")
var geometry = boundary.geometry()

//************************************************************************** 
// Function to Normalize Image
// Pixel Values should be between 0 and 1
// Formula is (x - xmin) / (xmax - xmin)
//************************************************************************** 
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

//************************************************************************** 
// Function to Standardize Image
// (Mean Centered Imagery with Unit Standard Deviation)
// https://365datascience.com/tutorials/statistics-tutorials/standardization/
//************************************************************************** 
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

GEE 中的许多分类器都有一个 `explain()` 方法，用来计算特征重要性。分类器会给每个输入变量分配一个分数，用以说明它们在预测正确值的有用程度。下面的脚本展示了如何提取特征重要性并创建图表来可视化。

![Relative Feature Importance](https://courses.spatialthoughts.com/images/end_to_end_gee/feature_importance.png)



[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FSupervised_Classification%2FFeature_Importance)



```js
var bangalore = ee.FeatureCollection('users/ujavalgandhi/public/bangalore_boundary')
var s2 = ee.ImageCollection('COPERNICUS/S2_SR')
var gcps = ee.FeatureCollection('users/ujavalgandhi/e2e/bangalore_gcps')

var filtered = s2
.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(bangalore))
  .select('B.*')

var composite = filtered.median().clip(bangalore) 


var addIndices = function(image) {
  var ndvi = image.normalizedDifference(['B8', 'B4']).rename(['ndvi']);
  var ndbi = image.normalizedDifference(['B11', 'B8']).rename(['ndbi']);
  var mndwi = image.normalizedDifference(['B3', 'B11']).rename(['mndwi']); 
  var bsi = image.expression(
      '(( X + Y ) - (A + B)) /(( X + Y ) + (A + B)) ', {
        'X': image.select('B11'), //swir1
        'Y': image.select('B4'),  //red
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


//************************************************************************** 
// Calculate Feature Importance
//************************************************************************** 
    
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

平滑（Smoothing）是一项用于时间序列以消除时间步长之间细粒度变化的技术。下面的例子展示了如何在 Earth Engine 中应用移动窗口平滑算法。使用 [Save-all Join](https://developers.google.com/earth-engine/guides/joins_save_all)，集合会与自身连接，而所有落在时间窗口内的图像都会作为每个图像的属性被添加进去。接下来，会在所有图像上应用 *mean* 缩减器，从而得到时间帧内像素的平均值。由此产生的时间序列减少了尖峰和尖谷，并且对于异常值（例如多云像素）更健壮。

![Moving Window Average Smoothing](https://courses.spatialthoughts.com/images/end_to_end_gee/Moving_Window_Smoothing.png)



[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FTime_Series_Smoothing%2FMoving_Window_Smoothing)



```js
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
  .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
function maskS2clouds(image) {
  var qa = image.select('QA60')
  var cloudBitMask = 1 << 10;
  var cirrusBitMask = 1 << 11;
  var mask = qa.bitwiseAnd(cloudBitMask).eq(0).and(
             qa.bitwiseAnd(cirrusBitMask).eq(0))
  return image.updateMask(mask).divide(10000)
      .select("B.*")
      .copyProperties(image, ["system:time_start"])
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
  difference: 1000 * 60 * 60 * 24 * days,
  leftField: 'system:time_start', 
  rightField: 'system:time_start'
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
  return ee.Image(image).addBands(collection.mean().rename('moving_average'));
}))
  
// Display a time-series chart
var chart = ui.Chart.image.series({
  imageCollection: smoothedCollection.select(['ndvi', 'moving_average']),
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

下面的代码显示了如何时间序列数据进行时间间隙填充。我们的博文 [Temporal Gap-Filling with Linear Interpolation in GEE](https://spatialthoughts.com/2021/11/08/temporal-interpolation-gee/) 中对代码和其他示例进行了详细的说明。


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FTime_Series_Smoothing%2FTemporal_Interpolation)



```js
// Temporal Interpolation (Gap-Filling Masked Pixels)
var geometry = ee.Geometry.Polygon([[
  [82.60642647743225, 27.16350437805251],
  [82.60984897613525, 27.1618529901377],
  [82.61088967323303, 27.163695288375266],
  [82.60757446289062, 27.16517483230927]
]]);

Map.addLayer(geometry, {color: 'red'}, 'Farm')
Map.centerObject(geometry)

var s2 = ee.ImageCollection("COPERNICUS/S2_SR");

var filtered = s2
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
function maskCloudAndShadowsSR(image) {
  var cloudProb = image.select('MSK_CLDPRB');
  var snowProb = image.select('MSK_SNWPRB');
  var cloud = cloudProb.lt(5);
  var snow = snowProb.lt(5);
  var scl = image.select('SCL'); 
  var shadow = scl.eq(3); // 3 = cloud shadow
  var cirrus = scl.eq(10); // 10 = cirrus
  // Cloud probability less than 5% or cloud shadow classification
  var mask = (cloud.and(snow)).and(cirrus.neq(1)).and(shadow.neq(1));
  return image.updateMask(mask).divide(10000)
      .select("B.*")
      .copyProperties(image, ["system:time_start"]);
}

var filtered = filtered.map(maskCloudAndShadowsSR)

// Add a band containing timestamp to each image
// This will be used to do pixel-wise interpolation later
var filtered = filtered.map(function(image) {
  var timeImage = image.metadata('system:time_start').rename('timestamp')
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
var millis = ee.Number(days).multiply(1000*60*60*24)
var maxDiffFilter = ee.Filter.maxDifference({
  difference: millis,
  leftField: 'system:time_start',
  rightField: 'system:time_start'
})

// We need a lessThanOrEquals filter to find all images after a given image
// This will compare the given image's timestamp against other images' timestamps
var lessEqFilter = ee.Filter.lessThanOrEquals({
  leftField: 'system:time_start',
  rightField: 'system:time_start'
})

// We need a greaterThanOrEquals filter to find all images before a given image
// This will compare the given image's timestamp against other images' timestamps
var greaterEqFilter = ee.Filter.greaterThanOrEquals({
  leftField: 'system:time_start',
  rightField: 'system:time_start'
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
  ordering: 'system:time_start',
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
  ordering: 'system:time_start',
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
  // y = y1 + (y2-y1)*((t – t1) / (t2 – t1))
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

  var t = image.metadata('system:time_start').rename('t')

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
  return result.copyProperties(image, ['system:time_start'])
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

var ndviVis = {min:0, max: 0.9,  palette: [
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

Savitzky–Golay 过滤器对时间序列中的一组数据点进行多项式拟合。[Open Earth Engine Library (OEEL)](https://www.open-geocomputing.org/OpenEarthEngineLibrary/) 提供了这种过滤器的有效实现，可应用于 ImageCollection。但是，必须对时间序列进行预处理，使得每隔一定时间就有图像。我们使用前面描述的[插值技术](#temporal-interpolation)，并且准备一个没有任何掩码像素的连续时间序列。所得的结果是一个新的 ImageCollection，包含定期（5 天）图像，以及使用 Savitzky–Golay 过滤器进行平滑处理的值。


![Savitzky-Golay Smoothing](https://courses.spatialthoughts.com/images/end_to_end_gee/Savitzky_Golay_Smoothing.png)

[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FTime_Series_Smoothing%2FSavitzky_Golay_Smoothing)



```js
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
  .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.bounds(geometry))

// Write a function for Cloud masking
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
    'system:time_start': startDate.advance(day, 'day').millis(),
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
  var timeImage = image.metadata('system:time_start').rename('timestamp')
  var timeImageMasked = timeImage.updateMask(image.mask().select(0))
  return image.addBands(timeImageMasked)
})

// Specify the time-window
// Set it so that we have at least 1 non-cloudy image in the period
var days = 60
var millis = ee.Number(days).multiply(1000*60*60*24)

var maxDiffFilter = ee.Filter.maxDifference({
  difference: millis,
  leftField: 'system:time_start',
  rightField: 'system:time_start'
})

var lessEqFilter = ee.Filter.lessThanOrEquals({
  leftField: 'system:time_start',
  rightField: 'system:time_start'
})


var greaterEqFilter = ee.Filter.greaterThanOrEquals({
  leftField: 'system:time_start',
  rightField: 'system:time_start'
})


var filter1 = ee.Filter.and(maxDiffFilter, lessEqFilter)
var join1 = ee.Join.saveAll({
  matchesKey: 'after',
  ordering: 'system:time_start',
  ascending: false})
  
var join1Result = join1.apply({
  primary: mergedCol,
  secondary: mergedCol,
  condition: filter1
})

var filter2 = ee.Filter.and(maxDiffFilter, greaterEqFilter)

var join2 = ee.Join.saveAll({
  matchesKey: 'before',
  ordering: 'system:time_start',
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

  var t = image.metadata('system:time_start').rename('t')

  var timeImage = ee.Image.cat([t1, t2, t])

  var timeRatio = timeImage.expression('(t - t1) / (t2 - t1)', {
    't': timeImage.select('t'),
    't1': timeImage.select('t1'),
    't2': timeImage.select('t2'),
  })

  var interpolated = beforeMosaic
    .add((afterMosaic.subtract(beforeMosaic).multiply(timeRatio)))
  var result = image.unmask(interpolated)
  return result.copyProperties(image, ['system:time_start'])
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
  leftField: 'system:time_start',
  rightField: 'system:time_start'
})

// Use the default distanceFunction
var distanceFunction = function(infromedImage, estimationImage) {
  return ee.Image.constant(
      ee.Number(infromedImage.get('system:time_start'))
      .subtract(
        ee.Number(estimationImage.get('system:time_start')))
        );
  }

// Apply smoothing of order=3
var order = 3;
var smoothed = oeel.ImageCollection.SavatskyGolayFilter(
  interpolatedCol, 
  maxDiffFilter,
  distanceFunction,
  order)

// Select the d_0_ndvi band and rename it
var smoothed = smoothed.select(['d_0_ndvi'], ['smoothed'])

//##############################################################
// Step-6: Visualize the results
//##############################################################

// Chart the time-series at a single location
var title = 'Savitsky-Golay smoothing' +
  '(order = '+ order + ', window_size = ' + days + ')'

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
var ndviVis = {min:0, max: 0.7,  palette: [
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

你可能想在应用中可视化的地图上添加已分类图像的图例。下面的代码片段展示了如何使用 UI 小部件来构建它。

![Creating a Discrete Map Legend](https://courses.spatialthoughts.com/images/end_to_end_gee/map_legend.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FMap_Legend)



```js
var classified = ee.Image("users/ujavalgandhi/e2e/bangalore_classified")
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



### 添加连续图例

如果在你的应用中，栅格图层使用调色板显示的，那么可以使用下面代码片段中使用的技术，来添加颜色条。

![Creating a Continuous Raster Legend](https://courses.spatialthoughts.com/images/end_to_end_gee/colorbar.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FColorbar_Legend)



```js
var s2 = ee.ImageCollection("COPERNICUS/S2");
var admin2 = ee.FeatureCollection("FAO/GAUL_SIMPLIFIED_500m/2015/level2");

var bangalore = admin2.filter(ee.Filter.eq('ADM2_NAME', 'Bangalore Urban'))
var geometry = bangalore.geometry()

var filtered = s2.filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
  .filter(ee.Filter.date('2019-01-01', '2020-01-01'))
  .filter(ee.Filter.bounds(geometry))

var image = filtered.median(); 

// Calculate  Normalized Difference Vegetation Index (NDVI)
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

Earth Engine 应用程序的一个常见用法是在拆分面板应用中显示 2 个图像。下面的脚本包含了一个简单的模版，你可以使用它来创建交互式拆分面板应用。这里，我们有 2 个地图对象：`leftMap` 和 `rightMap`。你可以给每个地图添加不同的图像，这样，用户就能够并排探索它们。[查看动画 GIF ↗](https://courses.spatialthoughts.com/images/end_to_end_gee/dust_storm_app.gif)]



![A Split Panel App that displays Pre- and Post-Storm Images](https://courses.spatialthoughts.com/images/end_to_end_gee/dust_storm_app.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FChange_Visualization_UI_App)



```js
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

var rgb_vis = {min: 0, max: 3200, bands: ['B4', 'B3', 'B2']};

var preStorm = ee.Image('COPERNICUS/S2/20180604T052651_20180604T053435_T43RGM')
var postStorm = ee.Image('COPERNICUS/S2/20180614T052651_20180614T053611_T43RGM')

// Add a RGB Landsat 8 layer to the left map.
leftMap.addLayer(preStorm, rgb_vis);
rightMap.addLayer(postStorm, rgb_vis);
```



### NDVI Explorer UI 应用程序


Earth Engine 应用允许你显示交互式图表以响应用户操作。该应用程序展示了构建应用程序的常见设计模式，它允许用户单击地图上的任何位置并使用单击位置获取图表。

![Global NDVI Explorer App](https://courses.spatialthoughts.com/images/end_to_end_gee/global_ndvi_explorer.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.com/?scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FUI_Widgets_and_Apps%2FNDVI%20Explorer%20UI%20App)



```js
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
      .select("B.*")
      .copyProperties(image, ["system:time_start"])
}


// Write a function that computes NDVI for an image and adds it as a band
function addNDVI(image) {
  var ndvi = image.normalizedDifference(['B8', 'B4']).rename('ndvi');
  return image.addBands(ndvi);
}

function getComposite(geometry) {
  var filtered = s2
  .filter(ee.Filter.date('2019-01-01', '2019-12-31'))
  .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 30))
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
  'position':  'top-center',
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
    .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 50))
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


  filtered.aggregate_array('system:time_start').evaluate(function(ids) {
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

随着你的 Earth Engine 项目的增长，你需要一种方法来组织和共享代码从而与他人协作。我们将学习一些关于如何最好地在 Earth Engine 中设置项目的最佳实践。



### 分享单个脚本

要分享单个脚本的代码，你需要使用代码编辑器中的 **Get Link** 按钮。单击该按钮时，代码编辑器的内容将被捕获并编码到一个 URL 中。当你与某人共享此 URL 时，他们将能够看到与你的代码编辑器相同的内容。这是发送代码快照的好方法，以便其他人可以重现你的输出结果。请记住，脚本链接只是快照，如果你在将链接发送给某人后更改代码，他们将看不到更新。


> 
> 尝试向某人发送链接时，请勿单击 *Copy Script Path* 按钮。将此路径发送给某人不会让他们能够访问你的代码。脚本路径仅适用于公共或共享存储库。
> 



![Code Sharing using Get Link button](https://courses.spatialthoughts.com/images/end_to_end_gee/get_link.png)


在使用 *Get Link* 共享脚本时，还应该共享你可能已上传并在脚本中使用的任何私有**资产**。可以使用特定的电子邮件地址共享资产，或者如果希望任何拥有脚本链接的人都能够访问它，请选中*Anyone can read* 框。否则将阻止其他人运行你的脚本。


![Sharing Uploaded Assets](https://courses.spatialthoughts.com/images/end_to_end_gee/sharing_assets.png)


阅读 Google Earth Engine 用户指南的 [Script links](https://developers.google.com/earth-engine/guides/playground#get-link) 部分了解更多。


### 分享多个脚本

如果想与其他用户或合作者共享一组脚本，最好的方法是创建一个新的 **Repository**。



![Creating New Repository](https://courses.spatialthoughts.com/images/end_to_end_gee/new_repository.png)


可以在存储库中放置多个脚本并与其他用户共享存储库。可以授予他们 **Reader** 或 **Writer** 访问权限，以便他们可以查看/添加/修改/删除该存储库中的脚本。如果你想让它 **Public** 可读，那么可以点上 *Anyone can read* 选项。你将看到一个格式为 `https://code.earthengine.google.co.in/?accept_repo=...` 的 URL。当与其他用户共享此 URL 并且他们访问该链接时，你的存储库将根据他们的访问权限添加到他们的代码编辑器上的 Reader或Writer文件夹下。


![Creating New Repository](https://courses.spatialthoughts.com/images/end_to_end_gee/sharing_repository.png)


阅读 Google Earth Engine 用户指南的 [Script Manager](https://developers.google.com/earth-engine/guides/playground#script-manager-scripts-tab) 部分了解更多信息。



### 在脚本间共享代码

对于大型项目，最好在脚本之间共享常用功能。这样，每个脚本就无需重复造轮子。Earth Engine 通过 **Script Modules** 启用此功能。使用名为 `exports` 的特殊对象，您可以将函数公开给其他脚本。阅读 Google Earth Engine 用户指南的 [Script modules](https://developers.google.com/earth-engine/guides/playground#script-modules) 部分了解更多信息。

有许多 Earth Engine 用户公开共享了他们的存储库并编写了脚本模块来执行各种任务。下面是使用 `users/gena/packages` 存储库中的 grid 模块 在 Earth Engine 中创建规律间隔网格的示例。

![Using a function from a script module](https://courses.spatialthoughts.com/images/end_to_end_gee/script_modules.png)


[在代码编辑器中打开 ↗](https://code.earthengine.google.co.in/?accept_repo=users%2Fujavalgandhi%2FEnd-to-End-GEE&scriptPath=users%2Fujavalgandhi%2FEnd-to-End-GEE%3ASupplement%2FMiscellaneous%2FCode_Sharing_and_Script_Modules)



```js
var karnataka = ee.FeatureCollection("users/ujavalgandhi/public/karnataka");
Map.addLayer(karnataka, {color: 'gray'}, 'State Boundary')
var bounds = karnataka.geometry().bounds()
var coords = ee.List(bounds.coordinates().get(0))
var xmin = ee.List(coords.get(0)).get(0)
var ymin = ee.List(coords.get(0)).get(1)
var xmax = ee.List(coords.get(2)).get(0)
var ymax = ee.List(coords.get(2)).get(1)
// source code for the grid package:
// https://code.earthengine.google.com/?accept_repo=users/gena/packages

// Import the module to our script using 'require'
var gridModule = require('users/gena/packages:grid')

// Now we can run any function from the module
// We try running the generateGrid function to create regularly spaced vector grid
// generateGrid(xmin, ymin, xmax, ymax, dx, dy, marginx, marginy, opt_proj)

var spacing = 0.5
var gridVector = gridModule.generateGrid(xmin, ymin, xmax, ymax, spacing, spacing, 0, 0)
Map.centerObject(gridVector)
Map.addLayer(gridVector, {color: 'blue'}, 'Grids')
```



### 有用的公共存储库

请访问 [Awesome Earth Engine](https://github.com/giswqs/Awesome-GEE)，查看精选的 Google Earth Engine 资源列表。

我们还推荐一些选定的软件包，它们具有非常有用的功能，可帮助你在 Earth Engine 中高效工作。

**通用包**


* [eepackages](https://github.com/gee-community/ee-packages-py)：一组 Google Earth Engine 实用工具。
* [geetools](https://github.com/fitoprincipe/geetools-code-editor/wiki)：用于云屏蔽、批处理等的工具
* [ee-palettes](https://github.com/gee-community/ee-palettes)：生成调色板的模块。
* [spectral](https://github.com/awesome-spectral-indices/spectral)：一个 javascript 模块，为 GEE 提供现成的光谱索引列表。
* [eemont](https://github.com/davemlz/eemont)：Python 包，它提供实用方法，通过与 Python 方法链来友好地创建更流畅的代码。


**特定应用程序包**


* [LEAF-Toolbox](https://github.com/rfernand387/LEAF-Toolbox/wiki)：Google Earth Engine 应用程序，产生各种植被生物物理产品，包括叶面积指数 (LAI)。
* [RivWidthCloud](https://github.com/seanyx/RivWidthCloudPaper)：用于自动提取 Javascript 和 Python API 的河流中心线和宽度的包。







# 指导项目

以下是使用 Earth Engine 实施实际项目的基于视频的分步演练。可以在课后为感兴趣的区域实施这些项目来继续你的学习之旅。


## 获取代码

1. [单击此链接](https://code.earthengine.google.co.in/?accept_repo=users/ujavalgandhi/End-to-End-%20Projects) 以打开 Google Earth Engine代码编辑器并将存储库添加到你的帐户。
2. 如果成功，你将在 *Reader* 部分的 *Scripts* 选项卡中拥有一个名为 `users/ujavalgandhi/End-to-End-Projects` 的新存储库。


> 
> 如果你在 *Reader* 部分没有看到存储库，请刷新浏览器选项卡，它将显示出来。
> 
> 
> 



![Code Editor After Adding the Projects Repository](https://courses.spatialthoughts.com/images/end_to_end_gee/projects.png)


## 项目 1：干旱监测

使用 CHIRPS 网格降雨数据，根据 30 年平均值计算降雨偏差

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_drought.png)](https://www.youtube.com/watch?v=zHUCM3XLc6k&list=PLppGmFLhQ1HJ5VhW6BZfhPX6spUcTY7SR)


[开始指导项目](https://www.youtube.com/watch?v=zHUCM3XLc6k&list=PLppGmFLhQ1HJ5VhW6BZfhPX6spUcTY7SR)




## 项目 2：洪水测绘

使用 Sentinel-1 SAR 数据快速绘制洪水图。

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_flood.png)](https://www.youtube.com/watch?v=jYsK9Y4ICrY&list=PLppGmFLhQ1HJzzKVS_4v8nBiXLYxAu100)


[开始指导项目](https://www.youtube.com/watch?v=jYsK9Y4ICrY&list=PLppGmFLhQ1HJzzKVS_4v8nBiXLYxAu100)



## 项目 3：提取时间序列

使用 MODIS 数据在多个多边形上提取 10 年 NDVI 时间序列。

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_ndvi.png)](https://www.youtube.com/watch?v=LqSClCXrMl4&list=PLppGmFLhQ1HJV1CctqanQvXQI1JmqGDDD)


[开始指导项目](https://www.youtube.com/watch?v=LqSClCXrMl4&list=PLppGmFLhQ1HJV1CctqanQvXQI1JmqGDDD)




## 项目 4：土地覆盖分析

使用现有的土地覆盖产品来提取特定类别并计算跨区域的统计数据。

[![Video](https://courses.spatialthoughts.com/images/end_to_end_gee/project_landcover.png)](https://youtube.com/playlist?list=PLppGmFLhQ1HLl0St2wiOPePr58sKu0Vh1)


[开始指导项目](https://youtube.com/playlist?list=PLppGmFLhQ1HLl0St2wiOPePr58sKu0Vh1)






# 学习资源

* [Awesome Earth Engine](https://github.com/giswqs/Awesome-GEE)：Google Earth Engine 资源的精选列表。


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