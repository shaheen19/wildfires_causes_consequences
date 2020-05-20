# Fire Risk Assessment
This repository contains data on the atmospheric composition and related weather conditions in the State of California, USA.  A folder containing burned areas (shape files) and Landsat8- images of the state of California.
The goal of this project is to assess the fire risks through understanding of the interactions between atmosphere and biosphere. The Landsat08 data will be used to identify and measure various types of vegetation and comparison with the atmospheric conditions will allow us to assess the accumulation of dry biomass and/or fuel during wildfire season in California, which normally lasts from May-October.

If we are able to define qunatitative relationships between atmospheric conditions, droughts,and wildfires, we can develop fire indices along with the assest values (property and population density)to forecast vulnerable areas. This will allow us to plan ahead of time to mitigate diaster and protect precious resources. 

# Background
Wildfire episodes are becoming more prevalent with global warming and climate change. Every year it causes lot of damage in terms of burnt acres, poor air quality and climate through emission of various trace greenhouse gases.
The world has warmed by 1.9 degrees Fahrenheit (1.09 degrees Celsius) since 1880, with the five warmest years on record occurring in the last five years. High temperatures and low humidity are two essential factors behind the rise in fire risk and activity, affecting fire behavior from its ignition to its spread.

In California, Santa Ana events which are characterized by high temperature, low relative humidity have caused many fires to spread over long distances. Over the few years the cost to control the fires have trippled ($550 millions)largely due to warmer and drier environment in California. In this project, my goal is identify the relationships between the intensity and duration of wildfires in California with atmospheric conditions. 


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

My preliminary analysis comprised of
### Final Notebooks
1) workflow and analysis of atmospheric composition and weather parameters.
2) workflow and analysis of vegetation  using normalized vegetation index and normalized burn ratio in the county of San Diego before and after wildfires. 
### Test-notebooks
The folder contain various files to test strategies to clean and reduce data files to be used for the final project.
### Scripts 
Few functions defined to automate data analysis
### Output files
This folder contains output data files and figures 
### Presentations
First powerpoint presentation describing 2014 wildfire events and atmospheric conditions.

The main repository contains license, gitignore and README.md files.

PS: please note that this work is in progress and the repository will be updated frequently in the next few months. README.md file will be updated as work continue to progress.


