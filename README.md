# Leaflet-

USGS Earthquake Visualization
Background
The United States Geological Survey (USGS) is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. One of their key responsibilities is to collect and analyze earthquake data from all over the world to better understand seismic activity.

Project Description
This project aims to visualize earthquake data provided by the USGS in an interactive and informative way. The visualization will allow users to explore earthquake occurrences, their magnitudes, depths, and locations on a map. Additionally, a legend will provide context for understanding the data, and tooltips will provide detailed information about individual earthquakes.

Project Structure
This project is divided into two parts:

Part 1: Create the Earthquake Visualization
In this part, we will create a map visualization of earthquake data using Leaflet.js and D3.js. The visualization will include:

A map showing earthquake locations based on latitude and longitude.
Data markers reflecting earthquake magnitude (size) and depth (color).
Popups providing additional information about each earthquake when clicked.
A legend displaying depth levels and their corresponding colors.
Part 2: Gather and Plot More Data (Optional)
In this optional part, we can plot a second dataset showing the relationship between tectonic plates and seismic activity. The tectonic plates dataset can be obtained from this link.

Instructions
Part 1: Create the Earthquake Visualization
Get your dataset: Visit the USGS GeoJSON Feed page and choose a dataset to visualize.
Import and visualize the data: Use the URL of the chosen dataset to pull in the earthquake data. Create a map using Leaflet.js and plot the earthquake locations on it. Size the markers based on earthquake magnitude and color them based on depth. Add popups for additional earthquake information.
Create a legend: Add a legend to the map to provide context for the earthquake data.
Part 2: Gather and Plot More Data (Optional)
Plot the tectonic plates dataset: If desired, plot the tectonic plates dataset alongside the earthquake data.
Add other base maps: Provide options for users to choose different base maps.
Separate datasets into overlays: Place each dataset into separate overlays that can be turned on and off independently.
Add layer controls: Add layer controls to the map to allow users to toggle between different overlays.
Requirements
The following requirements apply to "Part 1: Create the Earthquake Visualization":

Map (60 points)
TileLayer loads without error (20 points)
Connects to geojson API using D3 without error (20 points)
Markers with size corresponding to earthquake magnitude (10 points)
A legend showing the depth and their corresponding color (10 points)
Data Points (40 points)
Data points scale with magnitude level (10 points)
Data points colors change with depth level (10 points)
Each point has a tooltip with the Magnitude, the location, and depth (10 points)
All data points load in the correct locations (10 points)
Dependencies
Leaflet.js: https://leafletjs.com/
D3.js: https://d3js.org/
Setup
Clone this repository to your local machine.
Navigate to the project directory.
Open index.html in a web browser to view the earthquake visualization.