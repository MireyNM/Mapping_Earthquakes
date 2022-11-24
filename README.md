# Mapping_Earthquakes
Mapping Earthquakes with JS and APIs
## Overview
In this project, we used URL for GeoJSON earthquake data, tectonic data and major earthquakes data to retrieve geographical coordinates and magnitudes of earthquakes for the last seven days. Then we have visualized the data on a map.

### Aim
The aim of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days.

## Resources 
- Data Source: <a href="https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php">GeoJSON Earthquake Data</a>
- Software: Visual Studio 1.69.1 
- HTML code: <a href="https://github.com/MireyNM/Mapping_Earthquakes/blob/main/Earthquake_Challenge/index.html" target="_blank">index.html</a>
- JavaScript code:  <a href="https://github.com/MireyNM/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/js/challenge_logic.js" target="_blank">challenge_logic.js</a>
- Style .css code: <a href="https://github.com/MireyNM/Mapping_Earthquakes/blob/main/Earthquake_Challenge/static/css/style.css" target="_blank">style.css</a>

## Results

Using JavaScript and Leaflet.js we have created a map that has three styles: 
- Streets View 
- Satellite Streets View 
- Dark View

Using the JavaScript and the D3.js library we have retrieved the coordinates and magnitudes of the earthquakes from the <a href="https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson" target="_blank">GeoJSON data</a> of the last seven days. We have used Leaflet library to plot the data on a Mapbox map through an API request and created interactive circle markers for the earthquake data:
- We have color coded the circle markers and modified the radius of the circle based on each earthquake's magnitude.
- We have added a popup message for each earthquake data.
- And we have create a legend for the color range of earthquakes.

Following the same concept, we have retrieved major earthquakes data from the GeoJSON Summary Feed for <a href="https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson" target=“_blank”>M4.5+Earthquakes</a> for the past 7 days and we have added them to the map. 

Moreover, we have retrieved the Tectonic Plate Data  from this <a href="https://github.com/fraxen/tectonicplates" target=“_blank”>GitHub repository</a> and we have added them to the map and styled them.

The final map looks like Fig.1 below. 


<p align = "center">
<img width="499" alt="Outcomes_vs_Goals" src="https://user-images.githubusercontent.com/109363759/203714745-f758ff97-48c1-4885-b934-da4ed52465f9.png">
</p>
<p align = "center">
Figue 1 - Mapping earthquakes all over the world for the last seven days.
</p>


### Summary
We have visually mapped the earthquakes, major earthquakes and tectonic plates all over the world for the last seven days.
