# Mapping Earthquakes

## Project Overview
In the module, we created a earthquake map with two different maps (streets and satellite) and the earthquake overlay. Now, Basil and Sadhana would like to see the earthquake data in relation to the tectonic plates’ location on the earth, and they would like to see all the earthquakes with a magnitude greater than 4.5 on the map, and they would like to see the data on a third map.

## Summary

The following deliverables include:

1. Add Tectonic Plate Overlay:
    - Add tectonic plate data using d3.json()
    - Add the data using the geoJSON() layer
    - Set the tectonic plate LineString data to stand out on the map
    - Add the tectonic plate data to the overlay object with the earthquake data

2. Add Major Earthquake Data:
    - Add major earthquake data to the map using d3.json()
    - Add color and set the radius of the circle markers based on the magnitude of earthquake
    - Add a popup marker for each earthquake that displays the magnitude and location of the earthquake using the GeoJSON layer, geoJSON()

3. Add an Additional Map -- used Mapbox Dark style


## Resources
- Data Sources: Earthquake GeoJSON data, Major earthquake GeoJSON data >4.5 mag for the week, Tectonic Plate geoJSON data
- Languages: JavaScript, HTML