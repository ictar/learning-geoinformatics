原文：[Introduction to Dynamic World (Part 2) - Calculating Statistics of a Region.md](https://developers.google.com/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2)

---



















Introduction to Dynamic World (Part 2) - Calculating Statistics of a Region  |  Google Earth Engine  |  Google for Developers



 {
 "@context": "https://schema.org",
 "@type": "Article",
 
 "headline": "Introduction to Dynamic World (Part 2) - Calculating Statistics of a Region"
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
 "name": "Introduction to Dynamic World (Part 2) - Calculating Statistics of a Region",
 "item": "https://developers.google.com/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-2"
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
 
 

# Introduction to Dynamic World (Part 2) - Calculating Statistics of a Region




 
 Stay organized with collections
 

 
 Save and categorize content based on your preferences.
 










[Edit on GitHub](https://github.com/google/earthengine-community/edit/master/tutorials/introduction-to-dynamic-world-pt-2/index.md "Contribute to this article on GitHub.") 


[Report issue](https://github.com/google/earthengine-community/issues/new?title=Issue%20with%20tutorials/introduction-to-dynamic-world-pt-2/index.md&body=Issue%20Description "Report an issue with this article on GitHub.") 


[Page history](https://github.com/google/earthengine-community/commits/master/tutorials/introduction-to-dynamic-world-pt-2/index.md "View changes to this article over time.") 




 Author(s):
 
 [spatialthoughts](https://github.com/spatialthoughts "View the profile for spatialthoughts on GitHub") 




 Tutorials contributed by the Earth Engine developer community are not part of
 the official Earth Engine product documentation.


*This is part 2 of a 3-part tutorial, see also
[part 1](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1) and
[part 3](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3).*
A high resolution Land Use Land Cover (LULC) dataset like Dynamic World allows
us to estimate the footprint of human activity on carbon cycles, biodiversity
and other anthropogenic natural processes. Using the Dynamic World taxonomy, we
can calculate and summarize statistics over any region. In this section, we
will learn how to calculate the number of pixels for a single land cover class
in a region as well as the distribution of pixel counts for all classes.



> 
> Note that summary statistics could be used to get class proportions for a
> stratified sample, but reference data would need to be collected in order to
> correct for biases and perform area estimation.
> 
> 
> 


We continue from
[Part 1](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1)
of the Tutorial with the selected region of Dane
County, Wisconsin. In this section, you will learn how to calculate the
fraction of a single land cover class in this county as well as the
pixel counts for all the classes.


## Calculate the Fraction of a Single Class


Let's say we want to estimate what percentage of a region is
built-up area. We start by creating a mode composite for the
given time period.



```
var counties = ee.FeatureCollection('TIGER/2016/Counties');
var filtered = counties.filter(ee.Filter.eq('NAMELSAD', 'Dane County'));
var geometry = filtered.geometry();
Map.centerObject(geometry, 10);

var startDate = '2020-01-01';
var endDate = '2021-01-01';

var dw = ee.ImageCollection('GOOGLE/DYNAMICWORLD/V1')
             .filterDate(startDate, endDate)
             .filterBounds(geometry);

// Create a mode composite.
var classification = dw.select('label');
var dwComposite = classification.reduce(ee.Reducer.mode());

```

According to the Dynamic World taxonomy, the *Built Area* class is
represented with the pixel value **6**. We can use the boolean operator `.eq()`
to extract all pixels with that value.



```
// Extract the Built Area class.
var builtArea = dwComposite.eq(6);

```

The resulting `builtArea` image is a binary image—with pixel value 1 where
the condition matched and 0 where it didn't. We can add both the composite
and the built area images to the Map to verify it.



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
Map.addLayer(builtArea.clip(geometry), {}, 'Built Areas');

```



| Composite | Built Area Composite |
| --- | --- |
|  |  |


*Dynamic World Composite and Extracted Built Area Image*


Before proceeding further, it is helpful to rename our image bands so it is
easier to keep track of them.



```
var dwComposite = dwComposite.rename(['classification']);
var builtArea = builtArea.rename(['built_area']);

```

To count pixels within a region, we can use the `reduceRegion()` function with
the `ee.Reducer.count()` reducer. We first count total pixels in the image. Then
we use the `selfMask()` function to mask all 0 values and count the remaining
pixels.



```
// Count all pixels.
var statsTotal = builtArea.reduceRegion({
    reducer: ee.Reducer.count(),
    geometry: geometry,
    scale: 10,
    maxPixels: 1e10
    });
var totalPixels = statsTotal.get('built_area');

// Mask 0 pixel values and count remaining pixels.
var builtAreaMasked = builtArea.selfMask();

var statsMasked = builtAreaMasked.reduceRegion({
    reducer: ee.Reducer.count(),
    geometry: geometry,
    scale: 10,
    maxPixels: 1e10
    });
var builtAreaPixels = statsMasked.get('built_area');
print(builtAreaPixels);

```

The last step is to calculate the built area fraction by dividing the total
built area pixels by total image pixels. We round off the number to 2 decimal
places using the `format()` function and print the result.



```
var fraction = (ee.Number(builtAreaPixels).divide(totalPixels))
  .multiply(100);
print('Percentage Built Area', fraction.format('%.2f'));

```

## Summarizing Pixel Counts for All Classes


The method described in the previous section is useful for many applications,
but it can be limiting if you want to summarize the pixel counts for all the
classes. Instead, we can take the `dwComposite` image and use another reducer
called `ee.Reducer.frequencyHistogram()`. This reducer computes the counts for
all unique pixel values in the image. Note that this is a weighted reducer, so
it will count the pixels based on their overlap with the geometry. To match the
results we get from `ee.Reducer.count()`, we can create an unweighted reducer by
calling `unweighted()` on it. Learn more about
[Weighted Reducers](/earth-engine/guides/reducers_reduce_region?#pixels-in-the-region).



```
var pixelCountStats = dwComposite.reduceRegion({
    reducer: ee.Reducer.frequencyHistogram().unweighted(),
    geometry: geometry,
    scale: 10,
    maxPixels: 1e10
    });

var pixelCounts = ee.Dictionary(pixelCountStats.get('classification'));
print(pixelCounts);

```

The result is a dictionary with pixel values as keys and pixel counts as values.
We can rename the keys in the dictionary with the class names to make the
results more readable.



```
// Format the results to make it more readable.
var classLabels = ee.List([
    'water', 'trees', 'grass', 'flooded_vegetation', 'crops',
    'shrub_and_scrub', 'built', 'bare', 'snow_and_ice'
    ]);

// Rename keys with class names.
var pixelCountsFormatted = pixelCounts.rename(
  pixelCounts.keys(), classLabels);
print(pixelCountsFormatted);

```

If you are summarizing pixel counts over a large region, you may get a
**Computation Timed Out** error when you print the results. In such cases, you
must export the results instead of printing them in the Console.


The pixel counts are stored in a dictionary. To export it, we have to convert
the dictionary to a Feature Collection. A simple solution is to create a
Feature Collection having a single feature with null geometry and set the
dictionary as its properties. This resulting collection can then be exported
using the `Export.table.toDrive()` function. Run the script and click *Run* to
start the Export. Once the Export task finishes, you will have a file named
`pixel_counts.csv` in your Google Drive with the result of the computation.



```
// Create a Feature Collection.
var exportFc = ee.FeatureCollection(
  ee.Feature(null, pixelCountsFormatted));

// Export the results as a CSV file.
Export.table.toDrive({
  collection: exportFc,
  description: 'pixel_counts_export',
  folder: 'earthengine',
  fileNamePrefix: 'pixel_counts',
  fileFormat: 'CSV',
});

```

## Summary


You learned different techniques to calculate statistics on the LULC composite
image. We covered the method to extract pixels for a single class and
calculate its fraction. The tutorial also showed how to summarize pixel counts
of all classes in a region and export the results as a CSV file.


The pixel counts obtained through the method described here should be used with
care. For accurate area estimates, it should be further refined by comparing
against reference datasets and applying bias corrections.


The full script for this section can be accessed from this Code Editor link:
<https://code.earthengine.google.com/020bc4a2311777545bcb1d44d6f524be>


In [Part 3](/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-3)
of this tutorial, we will explore the probability time-series and
use it to detect changes.




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














[{&#34;dimensions&#34;: {&#34;dimension11&#34;: false, &#34;dimension5&#34;: &#34;en&#34;, &#34;dimension1&#34;: &#34;Signed out&#34;, &#34;dimension4&#34;: &#34;Google Earth Engine&#34;, &#34;dimension3&#34;: false, &#34;dimension6&#34;: &#34;en&#34;}, &#34;gaid&#34;: &#34;UA-24532603-1&#34;, &#34;metrics&#34;: {&#34;ratings\_value&#34;: &#34;metric1&#34;, &#34;ratings\_count&#34;: &#34;metric2&#34;}}, {&#34;dimensions&#34;: {&#34;dimension11&#34;: false, &#34;dimension5&#34;: &#34;en&#34;, &#34;dimension1&#34;: &#34;Signed out&#34;, &#34;dimension4&#34;: &#34;Google Earth Engine&#34;, &#34;dimension3&#34;: false, &#34;dimension6&#34;: &#34;en&#34;}, &#34;gaid&#34;: &#34;UA-60111163-2&#34;, &#34;metrics&#34;: {&#34;ratings\_value&#34;: &#34;metric1&#34;, &#34;ratings\_count&#34;: &#34;metric2&#34;}}]
{&#34;ga4&#34;: [&#34;G-272J68FCRF&#34;, &#34;G-CW83BZF8N3&#34;], &#34;ga4p&#34;: [&#34;G-272J68FCRF&#34;], &#34;gtm&#34;: [], &#34;parameters&#34;: {&#34;internalUser&#34;: &#34;False&#34;, &#34;language&#34;: {&#34;machineTranslated&#34;: &#34;False&#34;, &#34;requested&#34;: &#34;en&#34;, &#34;served&#34;: &#34;en&#34;}, &#34;pageType&#34;: &#34;article&#34;, &#34;projectName&#34;: &#34;Google Earth Engine&#34;, &#34;signedIn&#34;: &#34;False&#34;, &#34;tenant&#34;: &#34;developers&#34;, &#34;recommendations&#34;: {&#34;sourcePage&#34;: &#34;&#34;, &#34;sourceType&#34;: 0, &#34;sourceRank&#34;: 0, &#34;sourceIdenticalDescriptions&#34;: 0, &#34;sourceTitleWords&#34;: 0, &#34;sourceDescriptionWords&#34;: 0, &#34;experiment&#34;: &#34;&#34;}, &#34;experiment&#34;: {&#34;ids&#34;: &#34;&#34;}}, &#34;tags&#34;: []}



 
 (function(d,e,v,s,i,t,E){d['GoogleDevelopersObject']=i;
 t=e.createElement(v);t.async=1;t.src=s;E=e.getElementsByTagName(v)[0];
 E.parentNode.insertBefore(t,E);})(window, document, 'script',
 'https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers/js/app\_loader.js', '[1,"en",null,"/js/devsite\_app\_module.js","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers","https://developers-dot-devsite-v2-prod.appspot.com",1,null,["/\_pwa/developers/manifest.json","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/images/video-placeholder.svg","https://www.gstatic.com/devrel-devsite/prod/v47124a092dd56bf2680cfca4b2ab69e9e6a534f056a1a0dbc4abcaa7cdbba977/developers/images/favicon-new.png","https://fonts.googleapis.com/css?family=Google+Sans:400,500|Roboto:400,400italic,500,500italic,700,700italic|Roboto+Mono:400,500,700&display=swap"],1,null,[1,6,8,12,14,17,21,25,40,50,52,63,70,75,76,80,87,91,92,93,97,98,100,101,102,103,104,105,107,108,109,110,111,112,113,115,116,117,118,120,122,124,125,126,127,129,130,131,132,133,134,135,136,138,140,141,144,147,148,149,150,151,152,154,155,156,157,158,159,161,163,164,165,168,169,170,172,173,179,180,182,183,186,190,191,193,196],"AIzaSyAP-jjEJBzmIyKR4F-3XITp8yM9T1gEEI8","AIzaSyB6xiKGDR5O3Ak2okS4rLkauxGUG7XP0hg","developers.google.com","AIzaSyAQk0fBONSGUqCNznf6Krs82Ap1-NV6J4o","AIzaSyCCxcqdrZ\_7QMeLCRY20bh\_SXdAYqy70KY",null,null,null,["MiscFeatureFlags\_\_devpanel\_url","Experiments\_\_reqs\_query\_experiments","Profiles\_\_enable\_profile\_collections","Significatio\_\_enable\_footprints","Experiments\_\_enable\_experiments","Significatio\_\_enable\_by\_tenant","Badges\_\_enable\_drag\_and\_drop\_badges","Cloud\_\_enable\_cloud\_shell\_fte\_user\_flow","Search\_\_enable\_acl\_suggestions","Search\_\_enable\_dynamic\_content\_confidential\_banner","SignIn\_\_enable\_auto\_signin\_oauth","Profiles\_\_enable\_public\_developer\_profiles","MiscFeatureFlags\_\_developers\_footer\_dark\_image","Badges\_\_enable\_delete\_badges","Profiles\_\_enable\_page\_saving","Profiles\_\_enable\_developer\_profiles\_dashboard\_recommendations","BookNav\_\_enable\_collapsible\_book\_nav","Analytics\_\_enable\_ga4\_analytics","Cloud\_\_enable\_cloudx\_ping","Profiles\_\_enable\_suggested\_interests","MiscFeatureFlags\_\_developers\_footer\_image","Cloud\_\_enable\_cloud\_facet\_chat","Search\_\_enable\_page\_map","AuthorPageInsights\_\_enable\_author\_page\_insights","Profiles\_\_require\_profile\_eligibility\_for\_signin","Search\_\_enable\_devsite\_serp","Localization\_\_enable\_locale\_redirects","Cloud\_\_enable\_free\_trial\_server\_call","Profiles\_\_enable\_searchable\_interests","Profiles\_\_enable\_release\_notes\_notifications","Profiles\_\_enable\_profile\_communities","Cloud\_\_enable\_cloud\_shell","MiscFeatureFlags\_\_emergency\_css","Search\_\_enable\_suggestions\_from\_borg","Search\_\_enable\_faceted\_search","Profiles\_\_enable\_profile\_notifications\_ui","Cloud\_\_enable\_cloud\_dlp\_service","BookNav\_\_enable\_book\_nav\_filtering","Significatio\_\_enable\_experiment\_id\_caching","Cloud\_\_enable\_cloudx\_experiment\_ids","MiscFeatureFlags\_\_enable\_tls\_version\_for\_gaia\_calls","Profiles\_\_enable\_developer\_profiles\_callout","Badges\_\_enable\_hide\_badges","Profiles\_\_enable\_developer\_profiles\_interests"],null,null,"AIzaSyBLEMok-5suZ67qRPzx0qUtbnLmyT\_kCVE","https://developerscontentserving-pa.clients6.google.com","AIzaSyCM4QpTRSqP5qI4Dvjt4OAScIN8sOUlO-k","https://developerscontentsearch-pa.clients6.google.com",1]')
 




