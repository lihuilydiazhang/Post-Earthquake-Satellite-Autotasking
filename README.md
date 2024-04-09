# Post-Earthquake-Satellite-Autotasking

This Jupyter Notebook will contain all code related to the accessing and tasking of satellites following an earthquake. The goal is to automate the process of image capture tasks for earthquake-affected areas using USGS's Latest Earthquake Program and Google Earth Engine's Satellite Archive.

An overview of the methods are as follows:

Leverage credible data source by USGS Latest Earthquakes Program API, which contains earthquakes list (past 24 hours, M2.5+) from the Advanced National Seismic System.

Explore Google Earth Engine’s (GEE) vast satellite archive to query and identify most recent imageries over the disaster location. *

Utilize Python and related geospatial packages to create a workflow - linking the USGS API with GEE API - that is automated, scable, and accurate.

Disclaimer: This code has leveraged ChatGPT to experiment & expediate process.

A Step-by-step tutorial of this process:
Access USGS Daily EarthQuake Notification via its web url API
Use USGS API to filter earthquake in chosen area with specific characterisitics (ie. earthquake magnitude)
Extract the location (latitude and longitude) and other key information of the selected earthquake
Access Google Earth Engine to query the most recent satellite (LandSat) imagery covering the same location
Perform mapping and other visualization methods, perform any geosptial analysis as fit
