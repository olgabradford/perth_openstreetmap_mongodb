# perth_openstreetmap_mongodb
Perth OpenStreetMap data wrangling with python using MongoDB
The goal of this project is to choose an area of the world in https://www.openstreetmap.org, assess the quality of data for validity, accuracy, completeness, consistency and uniformity, clean it, and import to MongoDB.


Following steps were performed:



1 Defining functions to clean problematic tags, street names and types, maximum speed values, and cycling-related tags.

2 Transformation of data to Python dictionary and export to JSON format.

3 Connecting to MongoDB and importing data.

5 Data exploration of database in MongoDB using queries requested from Python.



A custom Perth area was selected and downloaded as OSM XML from Mapzen to perform the exercise. The file structure is described in the relevant openstreetmap wiki:
https://wiki.openstreetmap.org/wiki/OSM_XML



File is downloaded from https://mapzen.com/data/metro-extracts/metro/perth_australia/
perth_australia.osm.bz2   Zipped OSM XML file, unzipped after that (perth_australia.osm)
