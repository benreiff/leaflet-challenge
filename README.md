# Visualizing Data with Leaflet

![1-Logo](Leaflet-Step-1/Images/1-Logo.png)

The USGS provides scientific data about natural hazards, the health of our ecosystems and environment, and the impacts of climate and land-use change. They collect a massive amount of data from all over the world each day, which I used to visualize updated information about earthquakes in a given 24-hour time period.

1. **Get your data set**

   ![3-Data](Leaflet-Step-1/Images/USGS_webpage_header.PNG)

   The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When you click on a data set, for example 'All Earthquakes from the Past 7 Days', you will be given a JSON representation of that data. You will be using the URL of this JSON to pull in the data for our visualization.

   ![USGS_GeoJSON](Leaflet-Step-1/Images/USGS_GeoJson.PNG)

2. **Import & Visualize the Data**

   Create a map using Leaflet that plots all of the earthquakes from your data set based on their longitude and latitude.

   * Your data markers should reflect the magnitude of the earthquake in their size and color. Earthquakes with higher magnitudes should appear larger and darker in color.

   * Include popups that provide additional information about the earthquake when a marker is clicked.

   * Create a legend that will provide context for your map data.

   * Your visualization should look something like the map above.

- - -

* Add layer controls to our map.

- - -

### Assessment

Your final product will be assessed on the following metrics:

* Completion of assigned tasks

* Visual appearance

* Professionalism

### Copyright

Trilogy Education Services © 2019. All Rights Reserved.
