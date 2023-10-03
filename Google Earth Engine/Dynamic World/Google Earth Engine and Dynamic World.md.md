原文：[Google Earth Engine and Dynamic World.md](https://geovisualization.net/2022/09/09/google-earth-engine-and-dynamic-world/)

---

# Google Earth Engine and Dynamic World

 
Posted by [Alberto](https://geovisualization.net/author/geovisualization/)｜[2022/09/09](https://geovisualization.net/2022/09/09/google-earth-engine-and-dynamic-world/)


![](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-02.png?w=1568) 

Let me please introduce you this “new” LULC source I have come across with recently. The potential of this 10m “clutter” source is being able to acquire data from a few days ago instead of using outdated “very old” 2020 vintage datasets. I know, if these days something 2020 is very old then myself, born in 1972, I’m *older than the riverside*, *older than peeing in a wall*, even *older than Methuselah* (all these are spanish sayings) Yes, that’s the way it is nowadays. 


[![](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-04.png?w=1024)](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-04.png)Google Earth Engine
Google Earth Engine is a geospatial processing service where you can perform geospatial processing at scale, powered by Google Cloud Platform. The purpose of Earth Engine is to:


Provide an interactive platform for geospatial algorithm development at scale  
Enable high-impact, data-driven science  
Make substantive progress on global challenges that involve large geospatial datasets


Google Earth Engine combines a multi-petabyte catalog of satellite imagery and geospatial datasets with planetary-scale analysis capabilities. Scientists, researchers, and developers use Earth Engine to detect changes, map trends, and quantify differences on the Earth’s surface. Earth Engine is now available for commercial use, and remains free for academic and research use.


[![](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-20220909.png?w=784)](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-20220909.png)Google Earth Engine – Dynamic World
Dynamic World is a ***near*** ***realtime*** land cover dataset for our constantly changing planet. The real world is as dynamic as the people and natural processes that shape it. Dynamic World is a near realtime 10m resolution global land use land cover dataset, produced using deep learning, freely available and openly licensed. It is the result of a partnership between [Google](https://www.google.com/earth/outreach/) and the [World Resources Institute](https://www.wri.org/), to produce a dynamic dataset of the physical material on the surface of the Earth. Dynamic World is intended to be used as a data product for users to add custom rules with which to assign final class values, producing derivative land cover maps.


Key innovations of Dynamic World


[![](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-02.png?w=1024)](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-02.png)<https://dynamicworld.app/explore>
Near realtime data. Over 5000 Dynamic World image are produced every day, whereas traditional approaches to building land cover data can take months or years to produce. As a result of leveraging a novel deep learning approach, based on Sentinel-2 Top of Atmosphere, Dynamic World offers global land cover updating every 2-5 days depending on location.  
Per-pixel probabilities across 9 land cover classes. A major benefit of an AI-powered approach is the model looks at an incoming Sentinel-2 satellite image and, for every pixel in the image, estimates the degree of tree cover, how built up a particular area is, or snow coverage if there’s been a recent snowstorm, for example.


[![](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-03.png?w=1024)](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220907-03.png)Which is the layer that interests you the most?
Ten meter resolution. As a result of the European Commission’s Copernicus Programme making European Space Agency Sentinel data freely and openly available, products like Dynamic World are able to offer 10m resolution land cover data. This is important because quantifying data in higher resolution produces more accurate results for what’s really on the surface of the Earth.  
Dynamic World is produced using the Google Earth Engine and AI Platform. We developed the Dynamic World dataset in alignment with Google’s AI Principles.


Explore Dynamic World in Resource Watch by the World Resources Institute, and learn more about WRI’s Land & Carbon Lab.


Read the Nature Scientific Data publication:   
**Dynamic World, Near real-time global 10m land use land cover mapping** (you can find the link in sources section below).


Dynamic World is a 10m near-real-time (NRT) Land Use/Land Cover (LULC) dataset that includes class probabilities and label information for nine classes. Dynamic World predictions are available for the Sentinel-2 L1C collection from 2015-06-27 to present. The revisit frequency of Sentinel-2 is between 2-5 days.


Dynamic World predictions are available for the Sentinel-2 L1C collection from 2015-06-27 to present. The revisit frequency of Sentinel-2 is between 2-5 days depending on latitude. Dynamic World predictions are generated for images for Sentinel-2 L1C images with CLOUDY\_PIXEL\_PERCENTAGE <= 35%. Predictions are masked to remove clouds and cloud shadows using a combination of S2 Cloud Probability, Cloud Displacement Index, and Directional Distance Transform.


Images in the Dynamic World collection have names matching the individual Sentinel-2 L1C asset names from which they were derived, e.g:


ee.Image(‘COPERNICUS/S2/20160711T084022\_20160711T084751\_T35PKT’)


has a matching Dynamic World image named: ee.Image(‘GOOGLE/DYNAMICWORLD/V1/20160711T084022\_20160711T084751\_T35PKT’).


All probability bands except the “label” band collectively sum to 1.


To learn more about the Dynamic World dataset and see examples for generating composites, calculating regional statistics, and working with the time series, see the [Introduction to Dynamic World](https://developers.google.com/earth-engine/tutorials/community/introduction-to-dynamic-world-pt-1) tutorial series.


Given Dynamic World class estimations are derived from single images using a spatial context from a small moving window, top-1 “probabilities” for predicted land covers that are in-part defined by cover over time, like crops, can be comparatively low in the absence of obvious distinguishing features. High-return surfaces in arid climates, sand, sunglint, etc may also exhibit this phenomenon.


To select only pixels that confidently belong to a Dynamic World class, it is recommended to mask Dynamic World outputs by thresholding the estimated “probability” of the top-1 prediction.


Now it’s time for you to put your hands on. Create a Google Earth Engine account, copy paste this code below, change dates, minor parameters here and there, find how to export to your format… Let’s get started!!!!  
  
<https://code.earthengine.google.com/>


[![](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220912.png?w=1024)](https://geovisualization.files.wordpress.com/2022/09/google-earth-engine-south-africa-20220912.png)Google Earth Engine
————Explore in GEE———————-



```
// Construct a collection of corresponding Dynamic World and Sentinel-2 for
// inspection. Filter the DW and S2 collections by region and date.
var COL_FILTER = ee.Filter.and(
    ee.Filter.bounds(ee.Geometry.Point(20.6729, 52.4305)),
    ee.Filter.date('2021-04-02', '2021-04-03'));

var dwCol = ee.ImageCollection('GOOGLE/DYNAMICWORLD/V1').filter(COL_FILTER);
var s2Col = ee.ImageCollection('COPERNICUS/S2').filter(COL_FILTER);

// Join corresponding DW and S2 images (by system:index).
var DwS2Col = ee.Join.saveFirst('s2_img').apply(dwCol, s2Col,
    ee.Filter.equals({leftField: 'system:index', rightField: 'system:index'}));

// Extract an example DW image and its source S2 image.
var dwImage = ee.Image(DwS2Col.first());
var s2Image = ee.Image(dwImage.get('s2_img'));

// Create a visualization that blends DW class label with probability.
// Define list pairs of DW LULC label and color.
var CLASS_NAMES = [
    'water', 'trees', 'grass', 'flooded_vegetation', 'crops',
    'shrub_and_scrub', 'built', 'bare', 'snow_and_ice'];

var VIS_PALETTE = [
    '419BDF', '397D49', '88B053', '7A87C6',
    'E49635', 'DFC35A', 'C4281B', 'A59B8F',
    'B39FE1'];

// Create an RGB image of the label (most likely class) on [0, 1].
var dwRgb = dwImage
    .select('label')
    .visualize({min: 0, max: 8, palette: VIS_PALETTE})
    .divide(255);

// Get the most likely class probability.
var top1Prob = dwImage.select(CLASS_NAMES).reduce(ee.Reducer.max());

// Create a hillshade of the most likely class probability on [0, 1];
var top1ProbHillshade =
    ee.Terrain.hillshade(top1Prob.multiply(100))
    .divide(255);

// Combine the RGB image with the hillshade.
var dwRgbHillshade = dwRgb.multiply(top1ProbHillshade);

// Display the Dynamic World visualization with the source Sentinel-2 image.
Map.setCenter(20.6729, 52.4305, 12);
Map.addLayer(
    s2Image,
    {min: 0, max: 3000, bands: ['B4', 'B3', 'B2']},
    'Sentinel-2 L1C');
Map.addLayer(
    dwRgbHillshade,
    {min: 0, max: 0.65},
    'Dynamic World');
```

————Explore in GEE———————-


Summarizing, these days a lot of new 10m land use datasets have just arrived, which one is the best?. this article explains it well:   
  
**Global 10 m Land Use Land Cover Datasets: A Comparison of Dynamic World, World Cover and Esri Land Cover** (you can find the link in sources section below).


Abstract: The European Space Agency’s Sentinel satellites have laid the foundation for global  
land use land cover (LULC) mapping with unprecedented detail at 10 m resolution. We present a  
cross-comparison and accuracy assessment of Google’s Dynamic World (DW), ESA’s World Cover  
(WC) and Esri’s Land Cover (Esri) products for the first time in order to inform the adoption and  
application of these maps going forward. For the year 2020, the three global LULC maps show  
strong spatial correspondence (i.e., near-equal area estimates) for water, built area, trees and crop  
LULC classes.


Conclusions  
LULC mapping at global extents has been revolutionized by the plethora of mediumresolution satellite data available from programs such as Landsat and Sentinel. In our  
cross-comparison of global 10 m resolution LULC maps, we found large inaccuracies and  
spatial and thematic biases in each product that vary across biomes, continents and human  
settlement types. **Our overarching recommendation is to critically evaluate each LULC product with reference to the application purpose**. We highlight the novelty of DW as a global near real-time LULC product with class probability scores. LULC types, regardless of definition and type system, share with ecosystems the property that their composition, structure and processes often vary in a gradual, continuous manner over space and time.  
We suggest that the DW probability scores offer a fundamental shift in land cover mapping from categorical to continuum concepts.


So that’s what we will do, using each one of them after deep evaluation of purposes and accuracy needed.


Sources:  
<https://earthengine.google.com/>  
<https://dynamicworld.app/>  
<https://www.nature.com/articles/s41597-022-01307-4>  
<https://developers.google.com/earth-engine/datasets/>  
<https://developers.google.com/earth-engine/datasets/tags/landcover>  
<https://developers.google.com/earth-engine/datasets/catalog/GOOGLE_DYNAMICWORLD_V1>  
<https://www.mdpi.com/2072-4292/14/16/4101>



