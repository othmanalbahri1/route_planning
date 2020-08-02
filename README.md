# OpenStreetMap Route Planner

This is my solution to Udacity's OpenStreetMap Route Planner as part of the C++ Development Nanodegree. The aim of this project is to successfully navigate a map via the shortest path between two points on the map using the [A* search algorithm](https://en.wikipedia.org/wiki/A*_search_algorithm).

- Map data from OSM XML file is parsed and the optimal path is plotted using IO2D Library in C++;
- Used GoogleTest Framework for unit testing.

<img src="map.png" width="600" height="450" />

# The Project

The steps of this project are the following:
- Parse the data from an .OSM xml file.
- The user inputs two points on the map.
- A* search is executed on the two input points.
- The path is returned and plotted used IO2D library.

# Dependencies, compiling, running, and teseting

For details on dependencies, compiling, running, and teseting - please refer to the original [project repository](https://github.com/udacity/CppND-Route-Planning-Project).
