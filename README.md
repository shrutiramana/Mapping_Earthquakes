# Mapping_Earthquakes

To build Earthquake map displaying the following - 
    Deliverable 1: Add Tectonic Plate Data across Earth 
    Deliverable 2: Add Major Earthquake Data that were recorded in last 7 days with magnitude > 4.5 on the ritcher scale.
Above 2 tasks are accomplished on the 3 different map layers 
    1. Street tile layer. 
    2. Dark tile layer.
    3. Satelite tile layer.


Resources- 
    Data Source:

    All earthquakes in the past 7 days : https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson
    Major earthquakes in the past 7 days: https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson
    Tectonic plates data: https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json

JavaScript, HTML and CSS using Visualstudio code and , Leaflet 1.7.1, Mapbox access tokens.

With JavaScript, Leaflet.js, and geoJSON data,we added tectonic plate data and major earthquake data using d3.json(), add the data using the geoJSON() layer, set the tectonic plate LineString data to stand out on the map, and add the tectonic plate data to the overlay object with the earthquake data. 
Added a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON(). 

<img width="1403" alt="image" src="https://user-images.githubusercontent.com/98556229/179379757-c9488580-e3c8-49d1-84d3-e53414ea7608.png">


<img width="1440" alt="image" src="https://user-images.githubusercontent.com/98556229/179379764-99b1f11e-d636-4845-9a32-be92c0eb4a75.png">

<img width="1439" alt="image" src="https://user-images.githubusercontent.com/98556229/179379766-ca0abd93-b9e5-4bef-a482-0e12e2e75ea4.png">

<img width="1436" alt="image" src="https://user-images.githubusercontent.com/98556229/179379768-3b5efc5b-ed2f-4324-b37e-d7a666918e82.png">



