# leaflet-challenge
Visualizing Data with Leaflet

_____________________________________________________________

** Objective: **

The USGS (United States Geological Survey) is interested in building a new set of tools that will allow them to visualize their earthquake data.  They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it.  Their hope is that being able to visualize their data will allow them to better educate the public and other goverment organizations (and hopefully secure more funding) on issues facing our planet.

My goal is to create some visualizations that will help with this objective.

____________________________________________________________

## Task #1

Visualize an earthquake data set

1. I retrieved my data set from the USGS GeoJSON Feed page (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) which supplied me with a JSON representation of this data.

2. I imported the data for visualization

3. I created a map using Leaflet that plots all of the earthquakes from my data set based on their longitude and latitude.

  - The data markers for my map reflect the magnitude of the earthquake by their size and depth of the earthquale by color.  Earthquakes with higher magnitudes appear larger and earthquakes with greater depth appear darker in color

  - I included popups on my map that provide additional information about each earthquake when that specific marker is clicked

  - I created a legend that provides context for my map data

![Earthquake_Popup](https://user-images.githubusercontent.com/82673788/131376824-4ccd45b1-96b2-429a-b781-4ebc0596f872.PNG)

![Earthquake_Legend](https://user-images.githubusercontent.com/82673788/131376856-1a1f5e5f-81ce-4177-ad46-98599b3dbd4e.PNG)
 
 _________________________________________________________________
 
 ## Task #2

I plotted a second data set on my map that illustrates the relationship between tectonic plates and seismic activity.  In order to accomplish this, I needed to pull in a second data set and visualize it alongside my original set of data.

1. I plotted a second data set on my map

2. I added a number of base maps that the user can choose from

3. My two different data sets (earthquakes & tectonicplates) were seperated out into overlays on my map that can be turned on and off independently.

4. Layer controls were added onto my map
