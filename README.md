# Fire Risk Assessment
This repository contains data on the atmospheric composition and related weather conditions in the State of California, USA.  A folder containing burned areas (shape files) and Landsat8- images of the state of California.
The goal of this project is to assess the fire risks through understanding of the interactions between atmosphere and biosphere. The Landsat08 data will be used to identify and measure various types of vegetation and comparison with the atmospheric conditions will allow us to assess the accumulation of dry biomass and/or fuel during wildfire season in California, which normally lasts from May-October.

If we are able to determine qunatitative relationships between atmospheric conditions, droughts,and wildfires, we can develop fire indices along with the assest values (property and population density)to forecast vulnerable areas. This will allow us to plan ahead of time to mitigate diaster and protect precious resources. 

# Background
Wildfire episodes are becoming more prevalent with global warming and climate change. Every year it causes lot of damage in terms of burnt acres, poor air quality and climate through emission of various trace greenhouse gases.
The world has warmed by 1.9 degrees Fahrenheit (1.09 degrees Celsius) since 1880, with the five warmest years on record occurring in the last five years. High temperatures and low humidity are two essential factors behind the rise in fire risk and activity, affecting fire behavior from its ignition to its spread.

In California, Santa Ana events which are characterized by high temperature, low relative humidity have caused many fires to spread over long distances. Over the few years the cost to control the fires have trippled ($550 millions)largely due to warmer and drier environment in California. In this project, my goal is identify the relationships between the intensity and duration of wildfires in California with atmospheric conditions.
# Contribution to Data Science
The work flow developed for California can be implemented for other states and countries where air quality, weather data and satellite data is available. 

 # Development Environment and Workflow
The notebooks were developed using Python 3.7.1 on a Windows system and earth-analytics-python environment. The instructions on how to install these packages are found on these links 
(https://www.earthdatascience.org/workshops/setup-earth-analytics-python/),
(https://github.com/earthlab/earth-analytics-python-env)

 Tools and Packages
1. Numpy
2. Pandas
3. Matplotlib
4. Geopandas
5. earthpy
6. Rasterio
7. Scikit Learn

This Gitrep is comprised of following sections.

## Final Notebooks
To run these notebooks, you would require following data files (provided via google drive). 
1. sd_chemical_composition_2014_mean_v02.csv
2. sd_weather_2014_mean_values_only.csv
3. sd_combined_data_2014_mean_values_only.csv
After completing this project, I plan on adding data to "figshare"

Two new notebooks are added in this folder.
1. SciKit-learn-MLR-stats-final
This notebook provides information on statistical analysis conducted using Scikit-Learn.
2. understanding_wildfires_cause_consequences
This notebook provide information on processes responsible for ozone formation. 
I have explored the effect of weather and chemical compostion on the ozone equilibrium,
(net ozone= formation -destruction processes) 

Previous notebook with preliminary data exploration
3. San_Diego_2014_ wildfires_Time-series-analysis-of-the-air
4. SanDiego_2014_wildfires_NDVI_DNBR-anaysis

## Presentations
Two powerpoint presentation describing 2014 wildfire events and atmospheric conditions. Work in progress.
1. Time series analysis conducted earlier
2. SD_fires_air_quality_06172020_final

3. Wildfires SD_Causes and Consequences-blog

### Test-notebooks
The folder contain two sub folders for air quality and image processing. Each subfolder contains various files to test strategies to clean raw data and reduce file sizes to be used for the final project. Work in progress.

### Output files
This folder contains output data files and figures. Work in progess. 

PS: please note that this work is in progress and the repository will be updated frequently in the next few months. README.md file will be updated as work continue to progress.


