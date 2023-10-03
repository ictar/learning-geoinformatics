原文：[Introduction to Dynamic World (Part 3) - Exploring Time Series.md](https://developers.google.com/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3)

---



















Introduction to Dynamic World (Part 3) - Exploring Time Series  |  Google Earth Engine  |  Google for Developers



 {
 "@context": "https://schema.org",
 "@type": "Article",
 
 "headline": "Introduction to Dynamic World (Part 3) - Exploring Time Series"
 }

 {
 "@context": "https://schema.org",
 "@type": "BreadcrumbList",
 "itemListElement": [{
 "@type": "ListItem",
 "position": 1,
 "name": "Google Earth Engine",
 "item": "https://developers.google.com/earth-engine"
 },{
 "@type": "ListItem",
 "position": 2,
 "name": "Introduction to Dynamic World (Part 3) - Exploring Time Series",
 "item": "https://developers.google.com/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3"
 }]
 }
 












* [Google

Earth Engine](https://developers.google.com/earth-engine)





















* English
* Bahasa Indonesia
* Deutsch
* Español
* Français
* Português – Brasil
* Русский
* 中文 – 简体
* 日本語
* 한국어




Sign in










[Home](https://developers.google.com/earth-engine) 


[Guides](https://developers.google.com/earth-engine/guides) 


[Reference](https://developers.google.com/earth-engine/apidocs) 


[Support](https://developers.google.com/earth-engine/help) 


[Community](https://developers.google.com/earth-engine/tutorials) 


[Cloud](https://developers.google.com/earth-engine/cloud) 


[Data Catalog](https://developers.google.com/earth-engine/datasets) 



















* [Google

Earth Engine](https://developers.google.com/earth-engine)







* [Home](/earth-engine)
* [Guides](/earth-engine/guides)
* [Reference](/earth-engine/apidocs)
* [Support](/earth-engine/help)
* [Community](/earth-engine/tutorials)
* [Cloud](/earth-engine/cloud)
* [Data Catalog](/earth-engine/datasets)




* [Community Overview](/earth-engine/tutorials)
* Tutorials

	+ [Explore](/earth-engine/tutorials/community/explore)
	+ [Writing a Tutorial](/earth-engine/tutorials/community/write)
	+ [Style Guide](/earth-engine/tutorials/community/styleguide)
	+ JavaScript Tutorials
	
		- [Anomalies Analysis of Soil Moisture and Precipitation](/earth-engine/tutorials/community/anomalies-analysis-smo-and-pre)
		- [Beginner's Cookbook](/earth-engine/tutorials/community/beginners-cookbook)
		- [Combining FeatureCollections](/earth-engine/tutorials/community/combining-feature-collections)
		- [Creating Web Apps](/earth-engine/tutorials/community/creating-web-apps)
		- [Customizing Base Map Styles](/earth-engine/tutorials/community/customizing-base-map-styles)
		- [Dynamic World (Part 1)](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1)
		- [Dynamic World (Part 2)](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2)
		- [Dynamic World (Part 3)](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3)
		- [Extracting Raster Values for Points](/earth-engine/tutorials/community/extract-raster-values-for-points)
		- [Forest Cover and Loss Estimation](/earth-engine/tutorials/community/forest-cover-loss-estimation)
		- [Getting Started with Drawing Tools](/earth-engine/tutorials/community/drawing-tools)
		- [HISTARFM - How to Work with Gap-Filled Imagery](/earth-engine/tutorials/community/histarfm-cloud-and-gap-free-landsat)
		- [Identifying Annual First Day of No Snow Cover](/earth-engine/tutorials/community/identifying-first-day-no-snow)
		- [Interactive Region Reduction App](/earth-engine/tutorials/community/drawing-tools-region-reduction)
		- [Introduction to Soil Moisture Active Passive (SMAP)](/earth-engine/tutorials/community/smap-soil-moisture)
		- [Land Surface Temperature in Uganda](/earth-engine/tutorials/community/ph-ug-temp)
		- [MODIS NDVI Times Series Animation](/earth-engine/tutorials/community/modis-ndvi-time-series-animation)
		- [Monitoring Forest Vegetation Condition](/earth-engine/tutorials/community/forest-vegetation-condition)
		- [Non-Parametric Trend Analysis](/earth-engine/tutorials/community/nonparametric-trends)
		- [Pseudo-Invariant Feature Matching](/earth-engine/tutorials/community/pseudo-invariant-feature-matching)
		- [Rapid Classification of Croplands](/earth-engine/tutorials/community/classify-maizeland-ng)
		- [Spatiotemporal Statistics of Vegetation Indices](/earth-engine/tutorials/community/spatiotemporal-image-statistics)
		- [Synthetic Aperture Radar (SAR) Basics](/earth-engine/tutorials/community/sar-basics)
		- [Time Series Modeling](/earth-engine/tutorials/community/time-series-modeling)
	+ Python Tutorials
	
		- [An Intro to the Earth Engine Python API](/earth-engine/tutorials/community/intro-to-python-api)
		- [Change Detection in GEE - The MAD Transformation (Part 1)](/earth-engine/tutorials/community/imad-tutorial-pt1)
		- [Change Detection in GEE - The MAD Transformation (Part 2)](/earth-engine/tutorials/community/imad-tutorial-pt2)
		- [Change Detection in GEE - The MAD Transformation (Part 3)](/earth-engine/tutorials/community/imad-tutorial-pt3)
		- [Detecting Changes in Sentinel-1 Imagery (Part 1)](/earth-engine/tutorials/community/detecting-changes-in-sentinel-1-imagery-pt-1)
		- [Detecting Changes in Sentinel-1 Imagery (Part 2)](/earth-engine/tutorials/community/detecting-changes-in-sentinel-1-imagery-pt-2)
		- [Detecting Changes in Sentinel-1 Imagery (Part 3)](/earth-engine/tutorials/community/detecting-changes-in-sentinel-1-imagery-pt-3)
		- [Detecting Changes in Sentinel-1 Imagery (Part 4)](/earth-engine/tutorials/community/detecting-changes-in-sentinel-1-imagery-pt-4)
		- [Groundwater Recharge Estimation](/earth-engine/tutorials/community/groundwater-recharge-estimation)
		- [Histogram Matching](/earth-engine/tutorials/community/histogram-matching)
		- [Sentinel-2 Cloud Masking with s2cloudless](/earth-engine/tutorials/community/sentinel-2-s2cloudless)
		- [Time Series Visualization with Altair](/earth-engine/tutorials/community/time-series-visualization-with-altair)
* Educational Resources

	+ [EDU](/earth-engine/tutorials/edu)
	+ [Training Resources](/earth-engine/tutorials/ttt)
* [Developer Resources](/earth-engine/tutorials/community/developer-resources)

















 /\* Styles inlined from /earth-engine/tutorials/community/tutorial.css \*/

.article-links {
 padding: 0 0 15px 0;
 font-size: 15px;
 text-align: right;
 text-transform: uppercase;
 font-weight: 500;
 float: right;
}

.article-link,
.article-link-with-divider {
 display: inline-block;
}

.article-link-with-divider {
 border-right: 1px solid #eceff1;
 padding-right: 20px;
 margin-right: 15px;
}



/\* Background cell styles to distinguish from input cells. \*/

devsite-code .tfo-notebook-code-cell-output {
 background: rgba(229, 238, 253, 1); /\* light blue \*/
}

devsite-code .tfo-notebook-code-cell-output + .devsite-code-buttons-container button {
 background: rgba(229, 238, 253, .7); /\* light blue \*/
}

devsite-code[dark-code] .tfo-notebook-code-cell-output {
 background: rgba(11, 11, 48, 1); /\* dark blue \*/
}

devsite-code[dark-code] .tfo-notebook-code-cell-output + .devsite-code-buttons-container button {
 background: rgba(11, 11, 48, .7); /\* dark blue \*/
}

 

* [Home](https://developers.google.com/)
* [Products](https://developers.google.com/products)
* [Google Earth Engine](https://developers.google.com/earth-engine)
* [Community](https://developers.google.com/earth-engine/tutorials)







 
 
 Send feedback
 
 

# Introduction to Dynamic World (Part 3) - Exploring Time Series




 
 Stay organized with collections
 

 
 Save and categorize content based on your preferences.
 










[Edit on GitHub](https://github.com/google/earthengine-community/edit/master/tutorials/introduction-to-dynamic-world-pt-3/index.md "Contribute to this article on GitHub.") 


[Report issue](https://github.com/google/earthengine-community/issues/new?title=Issue%20with%20tutorials/introduction-to-dynamic-world-pt-3/index.md&body=Issue%20Description "Report an issue with this article on GitHub.") 


[Page history](https://github.com/google/earthengine-community/commits/master/tutorials/introduction-to-dynamic-world-pt-3/index.md "View changes to this article over time.") 




 Author(s):
 
 [spatialthoughts](https://github.com/spatialthoughts "View the profile for spatialthoughts on GitHub") 




 Tutorials contributed by the Earth Engine developer community are not part of
 the official Earth Engine product documentation.


*This is part 3 of a 3-part tutorial, see also
[part 1](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1) and
[part 2](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2).*
A key differentiator of the Dynamic World dataset is the availability of a
regularly updated time-series of land cover predictions. This allows you to
monitor the landscape in near-real time and detect changes in land surface
state. In this section, we will explore how you can work with this rich
time-series data.


Continuing from the
[Part 2](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2)
of this tutorial, we will now learn how you can work with this
time-series data.


## Charting Class Probabilities Over Time


Each Dynamic World image has bands with the predicted probabilities for each
class. For any location in the world, we can plot a time series of these
probabilities to understand the temporal patterns.


We start by defining a location with its coordinates. The location in this
example is a point over the University of Wisconsin - Madison Arboretum in
Wisconsin, USA. It is a dense urban forest that undergoes seasonal changes
throughout the year. This is a great location to see how Dynamic World can
help us monitor the changing conditions.



```
var geometry = ee.Geometry.Point([-89.4235, 43.0469]);
Map.addLayer(geometry, {color: 'red'}, 'Selected Location');
Map.centerObject(geometry, 16);

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3/arboretum.png)
*Google Maps Satellite Image of the Selected Location*


We start by first filtering the Dynamic World collection for the time period
and location of interest. Here we want to chart the changes to this location
over the course of a year. So we apply the filter to select images collected
over this region in the time period of interest. Finally, we select all class
probability bands.



```
var startDate = '2020-01-01';
var endDate = '2021-01-01';

var dw = ee.ImageCollection('GOOGLE/DYNAMICWORLD/V1')
             .filterDate(startDate, endDate)
             .filterBounds(geometry);

var probabilityBands = [
  'water', 'trees', 'grass', 'flooded_vegetation', 'crops', 'shrub_and_scrub',
  'built', 'bare', 'snow_and_ice'
];

var dwTimeSeries = dw.select(probabilityBands);

```

We are now ready to create a chart showing changes in class probabilities
through the year. Earth Engine provides several charting functions to work
with time-series data. Since we want to plot the time series for a single
location—we can use the `ui.Chart.image.series` function. Once the chart is
created, print it to see it in the console.



```
var chart = ui.Chart.image.series(
    {imageCollection: dwTimeSeries, region: geometry, scale: 10});
print(chart);

```

The chart is useful but not very informative. We need to make several
adjustments. First, the line colors are assigned at random and do not match
the colors used in the Dynamic World taxonomy. It is also missing the axis
labels. Let's use the `setOptions` function to set some configuration
options. You will find the explanations and a full list of parameters in the
[Google Charts documentation](/chart/interactive/docs/gallery/linechart).


Each band value is plotted as a line in the chart. This is called a series.
We need to set the label, color, and style properties for each of the 9 series
in the chart. We define a helper function to make the code simpler. This
function returns a dictionary for each series based on the label and color
arguments.



```
var lineStyle = function(label, color) {
  var styleDict =
      {labelInLegend: label, color: color, lineWidth: 2, pointSize: 3};
  return styleDict;
};

```

We now create the chart and call `setOptions` on the time-series chart with
a dictionary of configuration options. Each series is now styled with the
label and color matching the Dynamic World taxonomy.



```
var chart = ui.Chart.image.series({
  imageCollection: dwTimeSeries,
  region: geometry,
  scale: 10
}).setOptions({
  vAxis: {
    title: 'Class probabilities',
    viewWindow: {min: 0, max: 1}},
  interpolateNulls: true,
  series: {
              0: lineStyle('Bare', '#A59B8F'),
              1: lineStyle('Built', '#C4281B'),
              2: lineStyle('Crops', '#E49635'),
              3: lineStyle('Flooded vegetation', '#7A87C6'),
              4: lineStyle('Grass', '#88B053'),
              5: lineStyle('Shrub and scrub', '#DFC35A'),
              6: lineStyle('Snow and ice', '#B39FE1'),
              7: lineStyle('Trees', '#397D49'),
              8: lineStyle('Water', '#419BDF')}
});
print(chart);

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3/chart.png)
*Time Series Chart of Class Probabilities*


The resulting chart is much more informative and interpretable. The chart
immediately reveals the shift from snow in the winter to trees in the spring.
You can also see the model predicting high probabilities for *shrub\_and\_scrub*
and *bare* classes at the seasonal transition.


### Summary


You learned how to explore the time-series of Dynamic World dataset by plotting
the probability of each class at each time step. You can easily obtain this
chart for any location in the world by simply changing the geometry and the
date range.


The full script for this section can be accessed from this Code Editor link:
<https://code.earthengine.google.com/3bf152cd06507cc984a1748de3f996b3>


## Change Detection using Probability Bands


As you saw in the previous section, Dynamic World dataset provides a
time-series of per-pixel class probabilities. This allows one to build change
detection models easily without training custom models or collecting training
data. In this example, we will see how to use the probability bands to explore
urban changes over time.


A unique feature of the Dynamic World *Built Area* class is that it incorporates
the built environment as well as adjacent land cover types in the definition.
When a previously non-urban region starts getting urbanized with new roads and
urban structures - the whole region is classified as built. This feature can be
very useful to detect urban sprawl. We will see how the Dynamic World’s
probability based model allows us to explore urban expansion with a few simple
rules.


We start by selecting a region of interest. For this tutorial, we will try to
detect urban expansion around the City of Bengaluru, India. It is a rapidly
growing city that is witnessing unprecedented urbanisation and sprawl in
recent years. We use the
[FAO GAUL: Global Administrative Unit Layers 2015, Second-Level Administrative Units](/earth-engine/datasets/catalog/FAO_GAUL_2015_level2)
dataset and select the boundary of the Bangalore Urban district as the region
of interest.



```
var admin2 = ee.FeatureCollection('FAO/GAUL_SIMPLIFIED_500m/2015/level2');
var selected = admin2.filter(ee.Filter.eq('ADM2_NAME', 'Bangalore Urban'));
var geometry = selected.geometry();
Map.centerObject(geometry, 12);

```

We want to detect newly urbanized regions from the year 2019 to 2020. We
first create start and end dates for the before and after periods for the
analysis. Using the `ee.Date.fromYMD` function along with `advance`
allows us to make the code easily adaptable to different time ranges without
having to make many changes.



```
var beforeYear = 2019;
var afterYear = 2020;

var beforeStart = ee.Date.fromYMD(beforeYear, 1, 1);
var beforeEnd = beforeStart.advance(1, 'year');

var afterStart = ee.Date.fromYMD(afterYear, 1, 1);
var afterEnd = afterStart.advance(1, 'year');

```

Now, we select the *built* band that contains the pixel-wise probabilities
indicating the likeliness of it being urban. Since we are considering many
images over the period of the year, we create a mean composite indicating the
average probability across the year.



```
var dw = ee.ImageCollection('GOOGLE/DYNAMICWORLD/V1')
             .filterBounds(geometry)
             .select('built');

var beforeDw = dw.filterDate(beforeStart, beforeEnd).mean();
var afterDw = dw.filterDate(afterStart, afterEnd).mean();

```

To detect newly urbanized regions, we can apply a simple criteria. Any pixel
in the built class that had an average probability of less than 0.2 before
and greater than 0.5 after would indicate previously non-urban area which is
now urban.



```
// Select all pixels that are
// < 0.2 'built' probability before
// > 0.5 'built' probability after
var newUrban = beforeDw.lt(0.2).and(afterDw.gt(0.5));

var changeVisParams = {min: 0, max: 1, palette: ['white', 'red']};
Map.addLayer(newUrban.clip(geometry), changeVisParams, 'New Urban');

```

![](/static/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3/sprawl.png)
*Red Pixels Indicating Detected Urban Sprawl between 2019 and 2020*


You can see how easy it was to build a custom model for urban sprawl. You can
also build a more complex decision tree using rules involving multiple
probability bands, or apply the same logic across multiple temporal steps.


It is always a good idea to validate our analysis. We can add before and
after composites of Sentinel-2 images to check whether the detected change is
visible in the imagery. Since optical images have clouds and cloud shadows
that are not masked out, it is preferable to use a median composite.



```
var s2 = ee.ImageCollection('COPERNICUS/S2')
             .filterBounds(geometry)
             .filter(ee.Filter.lt('CLOUDY_PIXEL_PERCENTAGE', 35));

var beforeS2 = s2.filterDate(beforeStart, beforeEnd).median();
var afterS2 = s2.filterDate(afterStart, afterEnd).median();

var s2VisParams = {bands: ['B4', 'B3', 'B2'], min: 0, max: 3000};
Map.addLayer(beforeS2.clip(geometry), s2VisParams, 'Before S2');
Map.addLayer(afterS2.clip(geometry), s2VisParams, 'After S2');

```

For ease of comparison, we can mask the non-change pixels from the binary
`newUrban` image using the `selfMask` function and add it to the map.



```
Map.addLayer(
    newUrban.selfMask().clip(geometry), changeVisParams, 'New Urban (Masked)');

```



| Before Composite | After Composite | Detected New Urban Areas |
| --- | --- | --- |
|  |  |  |


*Before and After Sentinel-2 Composites and Detected Change*


### Summary


This section covered techniques to explore the probability time-series to
build a robust change detection model with just a few lines of code. We could
detect newly urbanized regions by comparing the before and after
probabilities of the built class and visualize the results on a map.


The full script for this section can be accessed from this Code Editor link:
<https://code.earthengine.google.com/2dc41ef62608d81ee4cb8d2e72287a1b>




---




 The data described in this tutorial were produced by Google, in
 partnership with the World Resources Institute and National Geographic
 Society and are provided under a CC-BY-4.0 Attribution license.













 
 
 Send feedback
 
 




Except as otherwise noted, the content of this page is licensed under the [Creative Commons Attribution 4.0 License](https://creativecommons.org/licenses/by/4.0/), and code samples are licensed under the [Apache 2.0 License](https://www.apache.org/licenses/LICENSE-2.0). For details, see the [Google Developers Site Policies](https://developers.google.com/site-policies). Java is a registered trademark of Oracle and/or its affiliates.


Last updated 2022-06-09 UTC.







 [{
 "type": "thumb-down",
 "id": "missingTheInformationINeed",
 "label":"Missing the information I need"
 },{
 "type": "thumb-down",
 "id": "tooComplicatedTooManySteps",
 "label":"Too complicated / too many steps"
 },{
 "type": "thumb-down",
 "id": "outOfDate",
 "label":"Out of date"
 },{
 "type": "thumb-down",
 "id": "samplesCodeIssue",
 "label":"Samples / code issue"
 },{
 "type": "thumb-down",
 "id": "otherDown",
 "label":"Other"
 }]
 

 [{
 "type": "thumb-up",
 "id": "easyToUnderstand",
 "label":"Easy to understand"
 },{
 "type": "thumb-up",
 "id": "solvedMyProblem",
 "label":"Solved my problem"
 },{
 "type": "thumb-up",
 "id": "otherUp",
 "label":"Other"
 }]
 



 
 Need to tell us more?
 
 







* [![GitHub](/static/site-assets/logo-github.svg)
 
 
 GitHub](https://github.com/google/earthengine-api) 
Earth Engine on GitHub
* [![Medium](/static/site-assets/logo-medium.svg)
 
 
 Medium](https://medium.com/google-earth) 
Follow our blog on Medium
* [![GIS Stack Exchange](/static/site-assets/logo-gis-stack-exchange.svg)
 
 
 GIS Stack Exchange](https://gis.stackexchange.com/questions/tagged/google-earth-engine) 
Ask questions using the google-earth-engine tag
* [![Twitter](/static/site-assets/logo-twitter.svg)
 
 
 Twitter](https://twitter.com/googleearth) 
Follow @googleearth on Twitter
* [![Videos](https://www.gstatic.com/images/icons/material/product/2x/youtube_64dp.png)
 
 
 Videos](https://www.youtube.com/googleearth) 
Earth Engine on YouTube






* ### Connect


	+ [Blog](//googledevelopers.blogspot.com)
	+ [Instagram](https://www.instagram.com/googlefordevs/)
	+ [LinkedIn](https://www.linkedin.com/showcase/googledevelopers/)
	+ [Twitter](//twitter.com/googledevs)
	+ [YouTube](//www.youtube.com/user/GoogleDevelopers)
* ### Programs


	+ [Women Techmakers](//www.womentechmakers.com)
	+ [Google Developer Groups](/community/gdg)
	+ [Google Developer Experts](/community/experts)
	+ [Accelerators](/community/accelerators)
	+ [Google Developer Student Clubs](/community/gdsc)
* ### Developer consoles


	+ [Google API Console](//console.developers.google.com)
	+ [Google Cloud Platform Console](//console.cloud.google.com)
	+ [Google Play Console](//play.google.com/apps/publish)
	+ [Firebase Console](//console.firebase.google.com)
	+ [Actions on Google Console](//console.actions.google.com)
	+ [Cast SDK Developer Console](//cast.google.com/publish)
	+ [Chrome Web Store Dashboard](//chrome.google.com/webstore/developer/dashboard)







[![Google Developers](https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers/images/lockup-google-for-developers.svg)](https://developers.google.com/)
* [Android](//developer.android.com)
* [Chrome](//developer.chrome.com/home)
* [Firebase](//firebase.google.com)
* [Google Cloud Platform](//cloud.google.com)
* [All products](/products)




* [Terms](/terms/site-terms)
* [Privacy](//policies.google.com/privacy)
* Sign up for the Google for Developers newsletter
[Subscribe](/newsletter/subscribe)



* English
* Bahasa Indonesia
* Deutsch
* Español
* Français
* Português – Brasil
* Русский
* 中文 – 简体
* 日本語
* 한국어














[{&#34;dimensions&#34;: {&#34;dimension5&#34;: &#34;en&#34;, &#34;dimension11&#34;: false, &#34;dimension4&#34;: &#34;Google Earth Engine&#34;, &#34;dimension1&#34;: &#34;Signed out&#34;, &#34;dimension6&#34;: &#34;en&#34;, &#34;dimension3&#34;: false}, &#34;gaid&#34;: &#34;UA-24532603-1&#34;, &#34;metrics&#34;: {&#34;ratings\_value&#34;: &#34;metric1&#34;, &#34;ratings\_count&#34;: &#34;metric2&#34;}}, {&#34;dimensions&#34;: {&#34;dimension5&#34;: &#34;en&#34;, &#34;dimension11&#34;: false, &#34;dimension4&#34;: &#34;Google Earth Engine&#34;, &#34;dimension1&#34;: &#34;Signed out&#34;, &#34;dimension6&#34;: &#34;en&#34;, &#34;dimension3&#34;: false}, &#34;gaid&#34;: &#34;UA-60111163-2&#34;, &#34;metrics&#34;: {&#34;ratings\_value&#34;: &#34;metric1&#34;, &#34;ratings\_count&#34;: &#34;metric2&#34;}}]
{&#34;ga4&#34;: [&#34;G-272J68FCRF&#34;, &#34;G-CW83BZF8N3&#34;], &#34;ga4p&#34;: [&#34;G-272J68FCRF&#34;], &#34;gtm&#34;: [], &#34;parameters&#34;: {&#34;internalUser&#34;: &#34;False&#34;, &#34;language&#34;: {&#34;machineTranslated&#34;: &#34;False&#34;, &#34;requested&#34;: &#34;en&#34;, &#34;served&#34;: &#34;en&#34;}, &#34;pageType&#34;: &#34;article&#34;, &#34;projectName&#34;: &#34;Google Earth Engine&#34;, &#34;signedIn&#34;: &#34;False&#34;, &#34;tenant&#34;: &#34;developers&#34;, &#34;recommendations&#34;: {&#34;sourcePage&#34;: &#34;&#34;, &#34;sourceType&#34;: 0, &#34;sourceRank&#34;: 0, &#34;sourceIdenticalDescriptions&#34;: 0, &#34;sourceTitleWords&#34;: 0, &#34;sourceDescriptionWords&#34;: 0, &#34;experiment&#34;: &#34;&#34;}, &#34;experiment&#34;: {&#34;ids&#34;: &#34;&#34;}}, &#34;tags&#34;: []}



 
 (function(d,e,v,s,i,t,E){d['GoogleDevelopersObject']=i;
 t=e.createElement(v);t.async=1;t.src=s;E=e.getElementsByTagName(v)[0];
 E.parentNode.insertBefore(t,E);})(window, document, 'script',
 'https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers/js/app\_loader.js', '[1,"en",null,"/js/devsite\_app\_module.js","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers","https://developers-dot-devsite-v2-prod.appspot.com",1,null,["/\_pwa/developers/manifest.json","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/images/video-placeholder.svg","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers/images/favicon-new.png","https://fonts.googleapis.com/css?family=Google+Sans:400,500|Roboto:400,400italic,500,500italic,700,700italic|Roboto+Mono:400,500,700&display=swap"],1,null,[1,6,8,12,14,17,21,25,40,50,52,63,70,75,76,80,87,91,92,93,97,98,100,101,102,103,104,105,107,108,109,110,111,112,113,115,116,117,118,120,122,124,125,126,127,129,130,131,132,133,134,135,136,138,140,141,144,147,148,149,150,151,152,154,155,156,157,158,159,161,163,164,165,168,169,170,172,173,179,180,182,183,186,190,191,193,196],"AIzaSyAP-jjEJBzmIyKR4F-3XITp8yM9T1gEEI8","AIzaSyB6xiKGDR5O3Ak2okS4rLkauxGUG7XP0hg","developers.google.com","AIzaSyAQk0fBONSGUqCNznf6Krs82Ap1-NV6J4o","AIzaSyCCxcqdrZ\_7QMeLCRY20bh\_SXdAYqy70KY",null,null,null,["Profiles\_\_enable\_profile\_communities","Search\_\_enable\_devsite\_serp","Profiles\_\_enable\_profile\_collections","Profiles\_\_enable\_release\_notes\_notifications","Profiles\_\_enable\_profile\_notifications\_ui","MiscFeatureFlags\_\_enable\_tls\_version\_for\_gaia\_calls","Badges\_\_enable\_hide\_badges","Experiments\_\_reqs\_query\_experiments","Profiles\_\_enable\_suggested\_interests","Profiles\_\_enable\_developer\_profiles\_interests","Profiles\_\_enable\_searchable\_interests","SignIn\_\_enable\_auto\_signin\_oauth","MiscFeatureFlags\_\_developers\_footer\_dark\_image","MiscFeatureFlags\_\_developers\_footer\_image","Search\_\_enable\_page\_map","Cloud\_\_enable\_cloud\_facet\_chat","Cloud\_\_enable\_cloud\_shell","Cloud\_\_enable\_cloud\_dlp\_service","Significatio\_\_enable\_experiment\_id\_caching","Cloud\_\_enable\_free\_trial\_server\_call","Profiles\_\_require\_profile\_eligibility\_for\_signin","Badges\_\_enable\_delete\_badges","BookNav\_\_enable\_book\_nav\_filtering","Search\_\_enable\_acl\_suggestions","Cloud\_\_enable\_cloud\_shell\_fte\_user\_flow","AuthorPageInsights\_\_enable\_author\_page\_insights","Cloud\_\_enable\_cloudx\_ping","MiscFeatureFlags\_\_devpanel\_url","Analytics\_\_enable\_ga4\_analytics","Profiles\_\_enable\_developer\_profiles\_dashboard\_recommendations","Significatio\_\_enable\_footprints","Search\_\_enable\_suggestions\_from\_borg","Profiles\_\_enable\_page\_saving","Localization\_\_enable\_locale\_redirects","Search\_\_enable\_dynamic\_content\_confidential\_banner","Profiles\_\_enable\_public\_developer\_profiles","Experiments\_\_enable\_experiments","Badges\_\_enable\_drag\_and\_drop\_badges","BookNav\_\_enable\_collapsible\_book\_nav","Cloud\_\_enable\_cloudx\_experiment\_ids","Significatio\_\_enable\_by\_tenant","Profiles\_\_enable\_developer\_profiles\_callout","MiscFeatureFlags\_\_emergency\_css","Search\_\_enable\_faceted\_search"],null,null,"AIzaSyBLEMok-5suZ67qRPzx0qUtbnLmyT\_kCVE","https://developerscontentserving-pa.clients6.google.com","AIzaSyCM4QpTRSqP5qI4Dvjt4OAScIN8sOUlO-k","https://developerscontentsearch-pa.clients6.google.com",1]')
 




