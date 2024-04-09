# Post-Earthquake-Satellite-Autotasking

This project is to automate the process of satellite images acquisition for earthquake-affected areas using USGS's Latest Earthquake Program and Google Earth Engine's LandSAT Archive.

## An overview of the methods are as follows:
1. Leverage credible data source by USGS Latest Earthquakes Program API, which contains earthquakes list (past 24 hours, M2.5+) from the Advanced National Seismic System.
2. Explore Google Earth Engine’s (GEE) vast satellite archive to query and identify most recent imageries over the disaster location.  
3. Utilize Python and related geospatial packages to create a workflow - linking the USGS API with GEE API - that is automated, scable, and accurate.

Functioning codes are contained in: Post_Earthquake_Satellite_Autotasking.ipynb
 
