# Spatial Network Analysis of Walkability

## Overview

This repository contains code for spatial network analysis of walkability.  The `SpatialNetwork` library provides functionality for downloading network data 
from OpenStreetMap and analysis methods such as shortest path calculation, redundant path calculation, and route optimization.  

## Notebooks

Notebooks are provided to demonstrate use cases.

### Basic Functionality

This notebook demonstrates basic functions such as downloading road network data, working with catchment areas, and calculating paths between endpoints:

[LINK](https://github.com/ccchris-allen/walkability/blob/master/notebooks/spatial-network-demo.ipynb)

### Calculating a Walkability Index

This notebook demonstrates how the functions provided can be used to calculate a walkability index.  This library has been used in a study to calculate walkability scores
based on data from social media and public repositories--a model which we call walkability in neighborhood social score (WINS).  The following notebook shows how we calculate WINS:

[LINK](https://github.com/ccchris-allen/walkability/blob/master/notebooks/wins-calculate.ipynb)

### Visualizing Walkability Scores

This notebook demonstrates how we can use this library, as well as other tools, to visualize walkability scores for our study areas:

[LINK](https://github.com/ccchris-allen/walkability/blob/master/notebooks/wins-visualize.ipynb)

## Related Libraries

Besides standard Python libraries, the following modules were used:

* [OSMNX](https://github.com/gboeing/osmnx)
* [GeoPandas](http://geopandas.org)
* [NetworkX](https://networkx.github.io)

