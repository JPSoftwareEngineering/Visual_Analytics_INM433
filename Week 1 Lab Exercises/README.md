# Visual Analytics Week 1 Lab Notes

## Geospatial Data

### What is Geospatial Data

**Geospatial, spatial, GIS or geodata**, are names for numeric data that identifies the geographical location of a physical object such as a building, a street, a town, a city, a country, etc. according to a geographic coordinate system. 

From the spatial data, you can find out not only the location but also the length, size, area or shape of any object. An example of a kind of spatial data that you can get are: coordinates of an object such as latitude, longitude, and elevation.

### Geoseries data

In order to understand how to plot onto geo dataframes that are generated from shapefiles, json etc., we need to understand the **GeoSeries** data types.

```
geopandas.geoseries.GeoSeries
```

Each value in the GeoSeries is a Shapely Object. It can be:

Point
Line
Polygon
MultiPolygon

Each object can be used for a different type of physical object such as: Point for building, Line for Street, Polygon for city, and MultiPolygon for country with multiple cities inside. For more information about each Geometric object, read this article:

https://shapely.readthedocs.io/en/stable/manual.html#geometric-objects

## The 'missingno' Python Package

### What is Missingno?

**missingno** is a Python library that provides the ability to understand the distribution of missing values through informative visualisations. The visualisations can be in the form of heat maps or bar charts. With this library, it is possible to observe where the missing values have occurred and to check the correlation of the columns containing the missing with the target column. Missing values are better handled once the dataset is fully explored. 

A useful tutorial can be found here:

https://analyticsindiamag.com/tutorial-on-missingno-python-tool-to-visualize-missing-values/#:~:text=Missingno%20is%20a%20Python%20library,missing%20values%20through%20informative%20visualizations.

