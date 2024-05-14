# Earthquake Visualization with Leaflet.js 🌍

## Overview ℹ️
The United States Geological Survey (USGS) collects vast amounts of earthquake data worldwide. This project visualizes that data in an interactive map, providing insights into earthquake occurrences, magnitudes, depths, and locations.

## Features 🚀
- Map displaying earthquake locations based on latitude and longitude.
- Data markers reflect earthquake magnitude (size) and depth (color).
- Popups show detailed information about each earthquake.
- Legend provides context for understanding earthquake depths.
- Optional: Plot tectonic plate boundaries alongside earthquake data.

## Instructions 📝
1. Visit the USGS GeoJSON Feed page to choose a dataset.
2. Import the data and visualize it using Leaflet.js and D3.js.
3. Customize the map to size and color markers based on earthquake properties.
4. Add popups for detailed earthquake information.
5. Enhance the visualization with a legend and optional tectonic plate boundaries.

## Requirements 🎯
- TileLayer loads without error.
- Connects to GeoJSON API using D3 without error.
- Markers size corresponds to earthquake magnitude.
- Legend displays earthquake depths and colors.
- Data points scale with magnitude level.
- Data points colors change with depth level.
- Each point has a tooltip with magnitude, location, and depth.
- All data points load in the correct locations.

## Github Page
https://jasleenshergill.github.io/Leaflet-challenge/  

## Dependencies 🛠️
- Leaflet.js: [https://leafletjs.com/](https://leafletjs.com/)
- D3.js: [https://d3js.org/](https://d3js.org/)

## Setup 🚀
1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open `index.html` in a web browser to view the earthquake visualization.
