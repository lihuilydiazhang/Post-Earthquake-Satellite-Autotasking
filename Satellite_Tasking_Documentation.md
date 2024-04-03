# Post Earthquake Satellite Autotasking Project

This is a project aimed to provide a workflow to increase the efficiency and impact for the remote sensing sector (particalarly data provider) in face of disaster response. 

A common operational challenge for many remote sensing companies during disaster response mission is identifying accurate and detailed disaster location in order to enact accurate and timely satellite data tasking request.

Many companies and organizations refer to through news/ social media scouting, local leads sharing, and other manual process. Time spent in gathering the precise location could delay the best response help. 

This is a automated workflow that connects reliabale earthquake information from USGS, with geospatial data, to automatically find and surface the most recent imagery in Google Earth Engine Archive used for Before graph. When tasking quota is available, this workflow could also be easily convert to automatically tasking a satellite (ie. Planet / Maxar / Airbus) soon after Earthquake being detected. 

# A Step-by-step tutorial of this process:

1. Create an account and access USGS Daily EarthQuake Notification
2. Use USGS API to filter earthquake in chosen area with specific characterisitics (ie. earthquake magnitude)
3. Extract the location  (latitude and longitude) of the selected earthquake
4. Use jupyter notebook & Google Earth Engine to visualize its location, perform any geosptial analysis as fit, such as mapping the historical / potential impact 
5. Inject the location as tasking / searching query in GEE to surface the most recent imagery

 
