# Air Quality and Thomas Fire Visualization in Santa Barbara
This repository has been made from content of the EDS 220 course

## About
This repository contains two notebooks: 'aqi-santa-barbara.ipynb' and 'thomas-fire.ipynb' that analyzes air quality in Santa Barbara in 2017-2018 and the association with the Thomas Fire in Santa Barbara that occurred in 2017, respectively.

## Visualization
After filtering air quality data to Santa Barbara county, I make a line plot showing AQI and a 5-day average for Santa Barbara in 2017-2018. The second visualization is a false color image of Santa Barbara with the area of the Thomas Fire burn overlayed to show the extent. 

## Highlights
 
  - Data wrangling and exploration with `pandas`
  - Geospatial data wrangling with `geopandas`
  - Merging of tabular and vector data
  - Creating and customizing a line plot
  - Creating and customizing a false color image

## Data
The data for AQI is available from: https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2017.zip (2017) and here: https://aqs.epa.gov/aqsweb/airdata/daily_aqi_by_county_2018.zip (2018). Access date October 28, 2023. 

The data for the false color image and Thomas Fire are available in the repository in the 'data' folder.
