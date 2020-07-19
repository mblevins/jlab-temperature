# Temeperature Analysis

## Noaa-data-\*.csv

These come from https://www.ncdc.noaa.gov/cdo-web/search . Select by zip code. On checkout, select temperature and precipitation settings. The data will be in one CSV file and will contain multiple stations per zip code.

## Generating stations.kml 

Running *stations* notebook will create a stations.kml file which can be imported into google maps.

## stations.json

Stations.json is a manually configured file with a list of stations to extract from the noaa data set. This must be a subset of stations.kml stations




