# leaflet-challenge
 https://amatutuwaa.github.io/leaflet-challenge/ 
 
 <img width="1792" alt="Screenshot 2023-05-29 at 3 57 00 PM" src="https://github.com/amatutuwaa/leaflet-challenge/assets/114604829/2b092c5c-af2a-4145-98bd-74ddc847a846">

The United States Geological Survey, or USGS for short, is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.
This projeect aims to visualize their earthquake data that will allow them to better educate the public and other government organizations (and hopefully secure more funding) on issues facing our planet.

## Part 1: Create the Earthquake Visualization

The first task is to visualize an earthquake dataset through the following steps:

1. Getting the dataset. 
   - The USGS provides earthquake data in a number of different formats, updated every 5 minutes. I visitted the USGS GeoJSON Feed page and chose a dataset to visualize.
   - When a dataset is chosen, a JSON representation of that data is provided. I use the URL of this JSON to pull in the data for the visualization.

2. Importing and visualizing the data by doing the following:
   - Using Leaflet, I create a map that plots all the earthquakes from the dataset based on their longitude and latitude.
       * Your data markers should reflect the magnitude of the earthquake by their size and the depth of the earthquake by color. Earthquakes with higher magnitudes should appear larger, and earthquakes with greater depth should appear darker in color.

   - I included popups that provide additional information about the earthquake when its associated marker is clicked.
   - I created a legend that will provide context for the map data.


