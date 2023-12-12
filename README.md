# CA Thomas Fire

## About 
The Thomas Fire occured in 2017 and burned for over 40 days. The fire destroyed over 280,00 acres, destroyed 1,063 structures and resulted in one civilian and one firefighter fatality[^1]. Understanding the impact on Air Quality is important for public health advisories, and planning when the next fire occurs. 

[^1] [Ventura County Fire Department](https://vcfd.org/news/vcfd-determines-cause-of-the-thomas-fire/#:~:text=The%20Thomas%20Fire%20started%20on,other%2C%20creating%20an%20electrical%20arc.)

## Goal

In this notebook I will investigate the Thomas Fire that occured in California in 2017, and its impact on the Air Quality Index (AQI) of Santa Barbara.

## Visualization

I created two visualizations. 
- The first is a time series graph to visualize the impact of the fire on the air quality index (AQI) of Santa Barbara County
- The second visualization is a false color image of California above the Santa Barbara Coast that shows the extent of the Thomas Fire.

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