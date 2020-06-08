# Mapping_Earthquakes
 
### Background
To illustrate the severity of the earthquakes in relation to the tectonic plates. I will need to make an API call to the tectonic plate data using d3.json(), and then add the data as an overlay to the map using the L.geoJSON() layer. All map styles will be added to the base layer so that they show up on the map to allow the user to change which layers are visible.

### Objectives
- The goals of this challenge are to use d3.json() to get tectonic plate data and add the data using the L.geoJSON() layer.
- Style the tectonic plate LineString data to stand out on the map.
- Add the tectonic plate data as an overlay with the earthquake data.
- Add a third map style to allow the user to select from three different maps.

### Process
Created a new folder named  “Earthquake_Challenge.”
Established Folder Structure.

Used the GeoJSON/PB2002_boundaries.json data from the GitHub repository for the tectonic plate data. 
Placed the d3.json() call with the L.geoJSON() layer for the tectonic plate data.
Styled the lines with a strong, bright color so the lines show up on the satellite map and are not too light to be seen on the lighter maps.
Created the tectonic plate layer for the map.
Added the tectonic plate layer to the overlays so that they show up in the tile layer, as shown in the image below.
Added the tectonic plate and earthquake data to the map for any map style choice.
Edited the base layer so that it holds all three maps.
Made the streets map the default map.
