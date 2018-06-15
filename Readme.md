# Visualizing Data with Leaflet

## Background

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific 
data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. 
Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes.

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from 
all over the world each day, but they lack a meaningful way of displaying it. This project is to visualize their data will allow them to 
better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

## Task

### Step 1. **Get your data set**
![png](Images/3-Data.png)

The USGS provides earthquake data in a number of different formats, updated every 5 minutes. 
Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) 
page to exploare more data. When you click on a data set, for example 'All Earthquakes 
from the Past 7 Days', you will be given a JSON representation of that data. In this project, we will be using the 
URL of this JSON to pull in the data for our visualization.

![png](Images/4-JSON.png)
    
### Step 2. **Import & Visualize the Data**
Create a map using Leaflet that plots all of the earthquakes from the data set based on their longitude and latitude.

* The data markers reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

* Include pop-ups that provide additional information about the earthquake when a marker is clicked.

### Step 3. **More Data Add to the Map**
In this project, we will add a second data set on the map to illustrate the relationship between tectonic plates and seismic activity. 
Data on tectonic plates can be found at <https://github.com/fraxen/tectonicplates>.

In this step we are going to..

* Plot a second data set on the map.

* Add a number of base maps to choose from as well as separate out our two different data sets into overlays that can be turned on and off independently.

* Add layer controls to our map.

![png](Images/darkmap.png)
