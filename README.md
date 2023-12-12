# CA Thomas Fire

## Goal

In this notebook I will investigate the Thomas Fire that occured in California in 2017. I will create a time series graph to visualize the impact of the fire on the air quality index (AQI) of Santa Barbara County, and a false color image to understand the extent of the fire. 

## Visualization

Created two visualizations. The first is a plot that shows the daily and 5-day rolling average Air Quality Index (AQI) of Santa Barbara in 2018. The second visualization is a map of California above the Santa Barbara Coast that shows the extent of the Thomas Fire.

## Highlights

- Data wrangling and exploration using `pandas`
- Geospatial analysis of false and true color images with `geopandas` and `rioxarray`
- Creating visualizations to give context for AQI measures as a result of the Thomas Fire

## Data Citation

We obtained the data from these sources:

California Perimeter Data: [California State Geoportal. 2019. California Fire Perimeters (all).](https://gis.data.ca.gov/datasets/CALFIRE-Forestry::california-fire-perimeters-all-1/about)

AQI Data: [Environmental Protection Agency. Air Quality Index.](https://www.airnow.gov/aqi/aqi-basics/)

Landsat data: [Microsoft Planetary Computer. Landsat Collection 2 Level-2.](https://planetarycomputer.microsoft.com/dataset/landsat-c2-l2#overview)

### File Structure


        ca-thomas-fire
        │   README.md
        │   thomas-fire.ipynb    
        │
        └───data
            |   landsat8-2018-01-26-sb-simplified.nc
            |
            └───California_Fire_Perimeters_2017
                │   California_Fire_Perimeters_2017.cpg
                │   California_Fire_Perimeters_2017.dbf
                │   California_Fire_Perimeters_2017.prj
                │   California_Fire_Perimeters_2017.shp
                │   California_Fire_Perimeters_2017.shx