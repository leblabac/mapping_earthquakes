# Mapping Earthquakes
Creating interactive maps using Leaflet.js library, Javascript, and HTML to retrieve earthquake information from a GeoJSON file and plot the results in a visual format.

## Overview
The purpose of this project is to visually show the differences between the magnitudes of earthquakes all over the world for the last seven days. A script was written to pull the GeoJSON earthquake data from the USGS website to retrieve the geographical coordinates and magnitudes of earthquakes for the last seven days. The data was then added to a map. Since the information is linked to a real-time source, the map will update whenever the user accesses it. Scripts were built using JavaScript and D3.js library to retrieve the coordinates and magnitudes of the earthquakes from the GeoJSON data. A Leaflet library was used to plot the data on a Mapbox style map through an API request and made it interactive by adding visualization for different map styles, creating layers to display tectonic plates, Earthquake magnitude and location information.

Throughout this project, visual customizations included:

- Toggling between map styles (i.e. dark, streets, satellite)
- Color changes to lines, marker types, and sizes
- Adding popup info box
- Plotting different points, multiple points, lines, polygons
