# Mapping_Earthquakes

### Visualizing Earthquakes with GeoJSON data

The purpose of this project is to use earthquake GeoJSON data from the USGS API to explore trends of earthquakes around the world with an interactive map. The earthquake data is plotted showing magnitude with color and size of the marker. In addition the tectonic plate lines are also plotted to allow the user to see the correlation between earthquakes and tectonic plates.

### Data

The data used comes from the USGS public API. The three sets of data used are [All Earthquakes GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/all_week.geojson), [Earthquakes over 4.5 magnitude GeoJSON](https://earthquake.usgs.gov/earthquakes/feed/v1.0/summary/4.5_week.geojson), and [Tectonic Plate Boundaries GeoJSON](https://raw.githubusercontent.com/fraxen/tectonicplates/master/GeoJSON/PB2002_boundaries.json). The software used includes HTML/CSS, JavaScript, [Leaflet 1.7.1](https://leafletjs.com/SlavaUkraini/download.html), and [D3.js 7.3.0](https://d3js.org/).

### Set Up

To interact with the maps API the user have to visit mapbox.com, create a Mapbox account and retrieve the access token.

The call for the config.js file in the index.html file is:

![](https://github.com/roeggealissa/Mapping_Earthquakes/blob/23ff091303c416ecf7af777c7ef685f907f2b0a2/images/config_reference.png)

Create a config.js file in the static/js folder. It will contain the API key in the following format.

![](https://github.com/roeggealissa/Mapping_Earthquakes/blob/23ff091303c416ecf7af777c7ef685f907f2b0a2/images/config_key.png)

To open the index.html file, open the command line, navigate to the main folder and on the command line, enter python -m http.server.

### Results

The map results in three views, Street, Satellite, and Dark as shown below. With minimal additions more GeoJSON data could be added and displayed.

![](https://github.com/roeggealissa/Mapping_Earthquakes/blob/c0e8b05150da5c6f3925c91ce3f3677b2a71836a/images/Street_view.png)
![](https://github.com/roeggealissa/Mapping_Earthquakes/blob/c0e8b05150da5c6f3925c91ce3f3677b2a71836a/images/Satellite_view.png)
![](https://github.com/roeggealissa/Mapping_Earthquakes/blob/c0e8b05150da5c6f3925c91ce3f3677b2a71836a/images/Dark_view.png)
