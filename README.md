# Map Apple Stores

This software was created in HTML utilizing the ArcGIS library to map Apple Store locations in the U.S. At the moment, it only displays 21 of the 271 Apple Stores in the states. The HTML contains the necessary ID to obtain this feature layer, but the API key is absent. You will have to provide your own to access ArcGIS features.

When the software is run, it pulls up a web page centered on the United States. Markers can be found on the page of the locations of the Apple Stores. When you click on a store, a popup will appear displaying the store's name and location. To create the feature layer, I had to create and upload a CSV file that contains each stores information. ArcGIS then transfers this data into the database.

I created this file to learn about ArcGIS's features and how to create my own feature layer. Fortunately, ArcGIS provides CSS stylesheets for the map, so must of the hard work is already out of the way.

[Software Demo Video](http://youtube.link.goes.here)

# Development Environment

* ArcGIS
*HTML
*Visual Studio Code
* Microsoft Excel

# Useful Websites

* [ArcGIS Tutorials](https://developers.arcgis.com/documentation/mapping-apis-and-services/tutorials/)

# Future Work

* Include more stores
* Filters which stores are displayed by state
* Use the Apple logo as a marker
