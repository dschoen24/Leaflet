# leaflet-challenge
## Visualizing Earthquake Data with Leaflet

_____________________________________________________________

### Objective:

The USGS (United States Geological Survey) is interested in building a new set of tools that will allow them to visualize their earthquake data.  They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it.  Their hope is that being able to visualize their data will allow them to better educate the public and other goverment organizations (and hopefully secure more funding) on issues facing our planet.

My goal is to create some visualizations that will help with this objective.

____________________________________________________________

You can deploy final visualization of the earthquake data by clickling this link: https://dschoen24.github.io/leaflet-challenge/

All the below images displayed can also be found within the images folder in this repository.

Final code used can be found here:




_________________________________________________________________

## Task #1

Visualize an earthquake data set

1. I retrieved my data set from the USGS GeoJSON Feed page (https://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) which supplied me with a JSON representation of this data.

2. I imported the data for visualization

3. I created a map using Leaflet that plots all of the earthquakes from my data set based on their longitude and latitude.

  - The data markers for my map reflect the magnitude of the earthquake by their size and depth of the earthquale by color.  Earthquakes with higher magnitudes appear larger and earthquakes with greater depth appear darker in color

  - I included popups on my map that provide additional information about each earthquake when that specific marker is clicked

  - I created a legend that provides context for my map data

Popup Image:  ![Earthquake_Popup](https://user-images.githubusercontent.com/82673788/131376824-4ccd45b1-96b2-429a-b781-4ebc0596f872.PNG)

Legend Image: ![Earthquake_Legend](https://user-images.githubusercontent.com/82673788/131376856-1a1f5e5f-81ce-4177-ad46-98599b3dbd4e.PNG)
 
 _________________________________________________________________
 
 ## Task #2

I plotted a second data set on my map that illustrates the relationship between tectonic plates and seismic activity.  In order to accomplish this, I needed to pull in a second data set and visualize it alongside my original set of data.

1. I plotted a second data set on my map

2. I added a number of base maps that the user can choose from

3. My two different data sets (earthquakes & tectonicplates) were seperated out into overlays on my map that can be turned on and off independently.

4. Layer controls were added onto my map

Toggle Bar Image: ![Earthquake_Toggle_Bar](https://user-images.githubusercontent.com/82673788/131377180-b10db069-abe0-4498-98bd-fbdf4cedda30.PNG)

Earthquake Toggle Bar Image: ![Earthquake_Toggle_Only](https://user-images.githubusercontent.com/82673788/131377194-96b396f2-a8cc-4d32-b6ca-27d440236584.PNG)

Tectonic Toggle Bar Image: ![Tectonic_Toggle_Only](https://user-images.githubusercontent.com/82673788/131377213-4421061d-e090-4216-9a4e-b52e8d5a35bb.PNG)

## Final Map Images

Satellite Map: ![Earthquake_Satellite_Map](https://user-images.githubusercontent.com/82673788/131377623-c7e3bac5-4f76-43e9-a3dc-5d362211a38a.PNG)

Outdoors Map: ![Earthquake_Grayscale_Map](https://user-images.githubusercontent.com/82673788/131377713-1c680db3-f62a-4632-a7d5-76a9eabd5011.PNG)

Grayscale Map: ![Earthquake_Dark_Map](https://user-images.githubusercontent.com/82673788/131377735-38754f2d-bf36-43aa-97e9-a04665839e13.PNG)

Dark Map: ![Earthquake_Outdoors_Map](https://user-images.githubusercontent.com/82673788/131377670-9beaf90f-7018-4250-abda-698d36735aea.PNG)

