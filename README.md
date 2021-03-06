# Objective
The objective of this project was to generate three interactive map of earthquakes, and its relation with maginitude, location and tectonic plates.
# Resources
To deliver the challenge we use the following resources:
## Softwares
* Visual Studio Code
* MapBox API's
* Leaflet D3
* JavaScript
* HTML - CSS
## Data
* Major Earthquake data: 
* Earthquake data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson"
* Major Earthquake data: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
* Tectonic plate data: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json
# Results
The first reult it was to provide a map with the earthquake and tectonic plate data as shown in the image below:

![This is and image](https://github.com/JJF1962/Mapping_Earthquakes/blob/main/Eartquake_Challenge/Resources/Delivery%201.PNG)

The second result consist in to provide a map using https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson, to provide the map showing the major earthquakes in the figure below:

![This is and image](https://github.com/JJF1962/Mapping_Earthquakes/blob/main/Eartquake_Challenge/Resources/Major%20Eartquakes%20Deliver%202%20point%203.PNG)

In the second part of the delivery two, we muts obtain a map showing all the Eartquakes, to do that, it was  added the major earthquake layer group variable to the map, i.e, majorEarthquakes.addTo(map), and then close the d3.json() callback, in VSA code we launched the index.html file and confirm that your map with the two earthquake data sets and tectonic plate data is similar to the following image. 

![This is and image](https://github.com/JJF1962/Mapping_Earthquakes/blob/main/Eartquake_Challenge/Resources/Deliver%202.PNG)

Finaly to deliver the third delivery Using the options from the Mapbox styles (Links to an external site.), add a third map style as a tile layer object to the challenge_logic.js file, add the map variable to the base layer object, started the Python server and launch the index.html file to obtain the dark map below, where there are three map styles, and displays the two earthquake data sets and the tectonic plate data.

![This is and image](https://github.com/JJF1962/Mapping_Earthquakes/blob/main/Eartquake_Challenge/Resources/Delivery%203%20.PNG)

# Conclusion and Summary
Very challenging module that allow us to learn more about Data visualization and two new tools MapBox API's and Leaflet D3
