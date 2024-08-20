# Visualizing Data with Leaflet

## Background

![1-Logo](Images/1-Logo.png)

Welcome to the United States Geological Survey, or USGS for short! The USGS is responsible for providing scientific data about natural hazards, the health of our ecosystems and environment; and the impacts of climate and land-use change. Their scientists develop new methods and tools to supply timely, relevant, and useful information about the Earth and its processes. 

The USGS is interested in building a new set of tools that will allow them visualize their earthquake data. They collect a massive amount of data from all over the world each day, but they lack a meaningful way of displaying it. Their hope is that being able to visualize their data will allow them to better educate the public and other government organizations (and hopefully secure more funding..) on issues facing our planet.

### Before I Begin

1.  I created a new repository for this project called `leaflet-challenge`. **Do not add this homework to an existing repository**.

2.  I cloned the new repository to my computer.

3.  Inside my local git repository, i created a directory for the Leaflet challenge. I used the folder names to correspond to the challenges: **Leaflet-Step-1** and **Leaflet-Step-2**.

4.  This task utilizes both **html** and **Javascript** so be sure to add all the necessary files. These will be the main files to run for analysis.

5.  I Pushed the above changes to GitHub or GitLab.

## my Task

### Level 1: Basic Visualization

![2-BasicMap](Images/2-BasicMap.png)

My first task is to visualize an earthquake data set.

1.  **Get my data set**

    ![3-Data](Images/3-Data.png)

    The USGS provides earthquake data in a number of different formats, updated every 5 minutes. Visit the [USGS GeoJSON Feed](http://earthquake.usgs.gov/earthquakes/feed/v1.0/geojson.php) page and pick a data set to visualize. When me click on a data set, for example 'All Earthquakes from the Past 7 Days', me will be given a JSON representation of that data. me will be using the URL of this JSON to pull in the data for our visualization.

    ![4-JSON](Images/4-JSON.png)

2.  **Import & Visualize the Data**

    I create a map using Leaflet that plots all of the earthquakes from my data set based on their longitude and latitude.

    -   My data markers should reflect the magnitude of the earthquake by their size and and depth of the earth quake by color. Earthquakes with higher magnitudes should appear larger and earthquakes with greater depth should appear darker in color.

    -   **HINT** the depth of the earth can be found as the third coordinate for each earthquake.

    -   I Included popups that provide additional information about the earthquake when a marker is clicked.

    -   I created a legend that will provide context for my map data.
------------------------------------------------------------------------
# leaflet-challenge