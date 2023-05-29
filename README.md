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


<img width="1792" alt="Screenshot 2023-05-29 at 4 13 50 PM" src="https://github.com/amatutuwaa/leaflet-challenge/assets/114604829/7d50aa8b-a825-4539-9290-d1f4fab3fef4">

## Part 2: Gather and Plot More Data 

1. I plot a second dataset on the map to illustrate the relationship between tectonic plates and seismic activity. 
   - For this I will need to pull in [this dataset]([http://www.google.fr/](https://github.com/fraxen/tectonicplates) "this dataset title") and visualize it alongside the original data.

   - I perform the following tasks:
      * Plot the tectonic plates dataset on the map in addition to the earthquakes.
      * Add other base maps to choose from.
      * Put each dataset into separate overlays that can be turned on and off independently.
      * Add layer controls to your map.
