---
title: "AI4EO-An Opportunity for Computation Sustainability"
description: This post introduces how Earth Observation (EO), EO data sources and how EO  and Artificial Intelligence (AI) could be used for Computational Sustainability.
toc: true
comments: true
layout: post
categories: [Machine learning, Deep learning,  Eearth observation]
image: images/post/eo.jpg
author: Anthony Faustine & Shridhar Kulkarni
---

# AI4EO-An Opportunity for Computation Sustainability
## Introduction

Computational Sustainability focuses on developing computational models, methods, and tools to help policymakers design more effective solutions and policies for sustainable development. The advancement of Information and Communication Technologies (ICT), particularly Earth Observation (EO) and Artificial intelligence (AI) offer prospects of addressing sustainability challenges. A more in-depth explanation about the above project can be viewed in this video:

{% include youtube.html content="https://youtu.be/vDC5T9Wvgeo" %}

Earth observations (EO) are data and information about the planet’s physical, chemical, and biological systems. It involves the collection, analysis, and presentation about the status of, and changes in, the natural and human-made environment. The most common sources of EO data include drones, land stations, and satellites. While drones capture high-resolution images on a small scale, satellites generate growing amounts of multi-resolution and multi-bands imagery and other data sources for the whole Earth. These data could be used to create all kinds of different products so that businesses, scientists, policymakers, and even everyday citizens can understand the past, present, and future trends in the Earth systems. Figure [below](https://desktop.arcgis.com/en/arcmap/latest/manage-data/raster-and-images/raster-bands.htm) shows multiband imagery from satellites by the electromagnetic.
![]({{ site.baseurl }}/images/Multispectral_bands.png) 


On the other hand, AI is an area of computer science devoted to developing systems that can learn (from data) to make decisions and predictions within specific contexts. Indeed, AI technology can extract more in-depth insights from datasets than other techniques.  Lately, AI has been used with success in solving complex problems in several domains such as machine translation, computer vision, autonomous cars, to mention a few. Machine learning and particularly computer vision models provide explicitly useful and practical approaches for analyzing and extracting relevant information from EO imagery data. Deep learning models and especially Convolution Neural Networks (CNNs) have proven effective in several computer vision tasks such as object detection, classification, and video processing, image generations, and image captioning, to mention a few. These models could be applied to detect and classify objects from complex EO imagery at a larger scale. Figure 2 presents AI capability for object detection and using computer vision techniques for multiband satellite images. This image has been taken from [here](https://desktop.arcgis.com/en/arcmap/latest/manage-data/raster-and-images/raster-bands.htm)).
![]({{ site.baseurl }}/images/EO_AI.png)


Applying these techniques to EO data will make it easy to efficiently automate the recognition of known and unknown patterns at large-scale. This is likely to reveal useful insights and opportunities for addressing sustainability challenges. For example, AI models could be applied to perform automated change detection, crop mapping, and yield estimation from high-resolution imagery in a larger-scale. The fusion of EO data and other data sources such as geo-referenced, demographics, and social-network data can be used to facilitate the more targeted developmental challenge. For instance, it has been demonstrated that the AI model can be used to [predict the poverty level by analyzing satellite imagery, night lights, and demographic data](https://www.ifc.org/wps/wcm/connect/2cae89ee-dea3-4a7e-ba79-77c9011cbd0f/IFC_2019_Poverty+Estimation+with+Satellite+Imagery+at+Neighborhood+Levels.pdf?MOD=AJPERES&CVID=mHZhcxB). 
{% include youtube.html content="https://youtu.be/GxUOp0L5dws" %}
     


##  EO data sources

There are many EO data sources made available recently. These data sources offer virtual visualization of any location on earth with resolution ranging from 5 centimeters to 120 meters depending on the instruments of satellites, airbus, or drones. The data sources are published as public or commercial data sources.

**Public EO data providers**

The EO puplic data providers are public service framework that allows full, free and open access to all data collected. [Copernicus](https://www.copernicus.eu/en/about-copernicus) and [Landsat](https://landsat.gsfc.nasa.gov/about/) are the famous and largest public satellite data providers. 
Landsat s one of the world's largest satellite image providers. It is a joint program of the National Aeronautics and Space Administration (NASA) and the United States Geological Survey (USGS). It provides access to satellites of the Landsat family, which have access over the archival of 50 years of earth data. Landsat satellites collect data on the forests, farms, urban areas, and water sources, generating the longest continuous record. The freely available information is used to understand environmental change better, [manage agricultural practices](https://landsat.gsfc.nasa.gov/how_landsat_helps/agriculture/), [allocate scarce water resources](https://landsat.gsfc.nasa.gov/how_landsat_helps/water), [monitor the extent and health of forests](https://landsat.gsfc.nasa.gov/how_landsat_helps/forest-management/) and respond to natural disasters, and more. Data can be accessed using LandsLook Viewer, USGS GloVis, Earth Explorer, Free Web-Enabled Landsat Data (WELD). More information is available [here](https://landsat.gsfc.nasa.gov/data/where-to-get-data/).

{% include youtube.html content="https://youtu.be/Ezn1ne2Fj6Y" %}

Copernicus is managed by the Europe Unions EO program and collect data from a constellation of 6 families of satellites, known as Sentinels. Each Sentinel mission focuses on different but interrelated aspects of EO, including [Atmospheric monitoring (Sentinels 4 and 5)](http://atmosphere.copernicus.eu), [Marine environment monitoring (Sentinel-3)](http://marine.copernicus.eu), [Land monitoring (Sentinel-2)](http://land.copernicus.eu), [Climate Change](http://climate.copernicus.eu) and [Emergency management](http://emergency.copernicus.eu). Currently Copernicus produces 12 terabytes per day of data for the 6 families of satellites, known as "Sentinels." The data are  open access and can be freely downloaded using [Copernicus Open Access Hub]. A summary of Copernicus program can found  in this video

{% include youtube.html content="https://youtu.be/MGJss4lDaBo" %}


**Commercial data providers**

The commercial satellite imagery providers provide access to data with high resolution with 3 centimeters to 10 meters. These services are paid and have good archival imagery. The most popular commercial EO imagery providers include; [Planet Labs](https://www.planet.com/), [DigitalGlobe](https://www.digitalglobe.com/) and [Airbus](https://www.intelligence-airbusds.com/en/8692-pleiades). 

[Planet Labs](https://www.planet.com/) provides access to a wide range of satellite data. It provides access to SkySAT families and RapidEye satellites. With 120+ satellites in orbit, Planet can image anywhere on Earth’s landmass daily, at 3 - 5-meter resolution. Planet processes and delivers imagery quickly and efficiently. Planet’s platform downloads and processes 11+ TB of data daily, enabling customers to build and run analytics at scale. Users can access Planet's data, using the paid planet API. Nevertheless, university researchers, academics, and scientists apply for free access as decribed in this [link](https://www.planet.com/markets/education-and-research/).

The [DigitalGlobe](https://www.digitalglobe.com/) is similar to Planet Labs and provides data access to a full range constellation of satellites in orbit. It provides access to EarlyBird-1, IKONOS, QuickBird, GeoEye-1, a family of WorldView satellites. It offers a high resolution of up to 30cm, showing crisp details, satellite imagery, geospatial information, and location-based intelligence. Recently, DigitalGlobe has started providing 0.4m resolution imagery today, which is one of the best in the business. 

On the other hand, the Airbus, with Pleiades and SPOT missions, provide very high-resolution multispectral twin satellites with 0.5 meters and 1.5-meter resolution, respectively. These imagery data are particularly suitable for emergency response and up-to daily change detection.




### AI ready EO datasets
Building ML applications for EO requires access to both EO data and their ground truth. Creating such a data-set is time-consuming and costly. As a result different organisations provide ready-to-use EO dataset which allow ML and GIS researchers and other stakeholders to build and test their ML application specific to EO. Radiant MLHub and Spacenet are the two notable EO training data providers. [Radiant MLHub](www.mlhub.earth) is an open library for geospatial training data to advance machine learning applications on EO. It hosts open training datasets generated by Radiant Earth Foundation's team as well as other training data catalogs contributed by Radiant Earth's partners. The data provided by Radiant MLHub are stored using a SpatioTemporal Asset Catalog (STAC) compliant catalog and exposed through a standard API. These data are open to anyone to use. It also free stores, register and share your dataset. 

The [Spacenet](https://spacenet.ai/datasets/), on the other hand, provides access to high-quality geospatial data for developers, researchers, and startups with a specific focus on the four open-source key pillars: data, challenges, algorithms, and tools. It also hosts challenges that focus on applying advanced machine learning techniques to solve difficult mapping challenges. The SpaceNet Dataset is hosted as an [Amazon Web Services (AWS) Public Dataset](https://registry.opendata.aws/), which is open for geospatial machine learning research. The dataset consists of well-annotated and very high-resolution satellite imagery with foundational mapping features such as building footprints or road networks.

[Kaggle](https://www.kaggle.com), a world's largest data science community with powerful tools and resources, is another source of EO training datasets which host several machine learning challenges EO imagery. This challenges includes [Dstl Satellite Imagery Feature Detection](https://www.kaggle.com/c/dstl-satellite-imagery-feature-detection), [Airbus Ship Detection Challenge](https://www.kaggle.com/c/airbus-ship-detection) and [Draper Satellite Image Chronology](https://www.kaggle.com/c/draper-satellite-image-chronology) to mention a few.

![]({{ site.baseurl }}/images/ai_ready.png)


### API for accessing EO  data.

Despite the availability of free and commercial satellite imagery, it is somehow challenging to directly download  and use these data.  Accessing these data requires one to have expertise in satellite imagery. Several API solutions that make it easy to access, download, and use satellite imagery from different sources have been developed to address these challenges. Sentinel Hub API is one of the easily available data API. 

[Sentinel Hub API](https://www.sentinel-hub.com/) makes satellite data from Sentinel, Landsat, and other Earth observation imagery easily accessible via easy-to-integrate web services. The API allows users to integrate satellite data either into their applications. To this end, Sentinel-hub offers several plugins such as [sentinelhub-python](https://github.com/sentinel-hub/sentinelhub-py), [Sentinelhub-js](https://medium.com/sentinel-hub/sentinelhub-js-open-source-library-for-satellite-imagery-powered-web-applications-aabe5495495b), [Sentinel Hub QGIS](https://github.com/sinergise/qgis_sentinel_hub) and [EO Browser](https://github.com/sentinel-hub/EOBrowser/) which is is a search tool for Sentinel-2 and Landsat 5,7,8 satellite imagery. Sentinelhub-js offer seamless integration of Sentinel Hub and other similar EO web services in web or node.js. This allows web developers to access remote sensing data quickly and to integrate it with their applications. On the other hand, the sentinel hub-python enables users to seamlessly make requests from Sentinel Hub OGC web services, download, and process images within their Python scripts. The Sentinel Hub QGIS plugin allows users to configure and harness Sentinel Hub services directly in QGIS. The Sentinel Hub API is the paid services but the also offer free access for research purpose. More details could found on this [link](https://www.sentinel-hub.com/faq/it-possible-get-free-account-research-purposes/). 

Users can also use [sentinelsat](https://sentinelsat.readthedocs.io/en/stable/?badge=stable) a python API for searching, downloading and retrieving the metadata of Sentinel satellite images from the Copernicus Open Access Hub. Compared to Sentinel-hub API, this is free services limited to only Copernicus satellites.
{% include youtube.html content="https://youtu.be/jOG52oHdtbg" %}
        
## Opportunity and Challenges of AI4EO

Machine learning, precisely computer vision, can be applied to EO imagery data for multimodal semantic segmentation, detecting objects,  detecting changes from a time series satellite image or image retrieval. The computer vision model can automatically generate semantic maps of a large area from EO data [[Audebert2017a]](https://www.sciencedirect.com/science/article/pii/S0924271617301818). The resulting semantic maps can be used for the cartography of urban areas or to determine land use cover at a massive scale. In change detection, machine learning models could be used to extend the semantic analysis of EO data by incorporating the multi-temporal dimension. This enables us to track changes around the globe or monitor activity in high-revisit rate acquisitions. It also plays an essential role in the production of maps depicting the evolutions of land use, urban coverage, deforestation, and other multi-temporal type analysis. The image retrieval aims to retrieve images with similar visual contents with respect to the query image from a database. 

![]({{ site.baseurl }}/images/change_detection.png)

Even though AI provides a potential application to EO, several challenges need to be addressed to successfully exploits AI potentials.  This is because compared to other types of Data, EO  present several challenges for machine learning algorithms. The following video discuss some of the opportunities and challenges of machine learning for EO.
{% include youtube.html content="https://youtu.be/5PNnPagENxQ" %}

First, the EO data is multimodal and high dimensional. For instance, the EO satellite data come from a variety of sensors types such as passive sensors (RBGN), active sensors (Synthetic Aperture Radar (SAR)), near-infrared sensors. The data also contain additional geo-related data like weather, geo-physical or biochemical quantities and other derived products. This data variety raises the following fundamental challenges when applied to the machine learning model: *how to combine all these data types (data fusion) since all these sources provide complementary information that should be used jointly to maximize the model's performance.  As a  result, there is a need to develop novel machine learning models that match EO data taken from different sources with different imaging modalities. Modifying existing vision-based deep networks to these data is not trivial, as this requires to work with new data structures that do not share the same underlying physical and numerical properties. Other exciting topics could be investigating the transferability of deep learning networks to [EO imaging modalities] (https://ieeexplore.ieee.org/document/8113128). Among the other challenges are the sheer number of pixels and the geographic extent per image. For example, a single DigitalGlobe satellite image encompasses > 64 km2 and over 250 million pixels. Also, the objects of interest are microscopic, which complicates traditional computer vision techniques. 

The size of EO data is increasing at an exponential rate demanding automation, massive computing, and machine learning algorithms that are fast enough and sufficiently transferrable to be applied for the whole earth's surface. Besides,  these data contain plenty of unlabelled data, making it challenging to use well-established supervised machine learning techniques. Yet this provides an opportunity to explore the recent progress in semi-supervised learning, [self-supervised](https://lilianweng.github.io/lil-log/2019/11/10/self-supervised-learning.html) and active-learning methods for EO application. Furthermore, the existence of meta-data and other geo-referenced data such as the Open-street map (OSM) provides an opportunity for creating annotated satellite imagery data for machine learning algorithms.

 It should be noted that EO data are time-variable dependent as satellite guarantees continuous data acquisition for decades. For example, the sentinel-1 images the entire earth every six days. Thus machine learning algorithms for  EO imagery analysis should jointly exploit both the temporal, spectral, and spatial information of these data.  

The interpretability of the machine learning model applicable to EO is another exciting research opportunity. Machine learning models are useful to estimate correlations, but what about causations. Exploiting graphical models and causal discovery to learns cause and effects relations from EO data is a unique opportunity for machine learning in EO. This can be useful for hypothesis testing, model-data comparison, and understanding the causes of extreme impacts.

### Conclusion
The satellite has been in the orbit of the earth for many decades, but the access to the data and applications using satellite images has recently become prominent. In this blog, we have introduced the opportunity of using Earth Observation and Artificial Intelligence to address sustainability challenges. We introduced different sources for EO data sources that include public and private satellite providers. We also presented the prominent AI-ready EO data providers and introduced Sentinel-hub, which is an API for accessing EO data from different sources. Finally, the blog highlight opportunity and challenges of applying advanced machine learning techniques such as deep learning for EO imagery data. In the upcoming blog, we will discuss how to download, process, and use EO data for machine learning applications with a specif focus on computational sustainability. Stay tuned for more!


### References 
- [Working towards AI and Earth observation](https://www.esa.int/Applications/Observing_the_Earth/Working_towards_AI_and_Earth_observation)

