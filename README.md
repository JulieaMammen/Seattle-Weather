# A Comparison of Rainfall in Saint Louis, MO and Seattle, WA

The purpose of this project is to comapre the weather data sets from Saint Louis, MO and Seattle, WA. Through this comparison we can understand whether it rains more in Seattle compared to Saint Louis or not, and be able to effectively communicate this comparison in weather between the two cities. 

## Data
The data is daily precipitation measures in St. Louis and Seattle from January 1, 2017 to December 31, 2022 downloaded from the National Centers for Environmental Information.
This is a link to the data source: https://www.ncei.noaa.gov/cdo-web/search?datasetid=GHCND

## Data Preparation
The steps taken to prepare the data involves limiting the data sets to ensure it covers the years from 2018-2022 only. Furthermore, it also entails selecting only the relevant subsets of the data frames that we need in order to perform proper analysis for answering the question. This preparation also involves ensuring data entries are of the proper type, that there is consistent naming conventions that are easy to read and understand, as well as an interpolations needed to fill potential missing values in the data set. 

The file that perform the data prepartion is called: 
  JulieMammen-DATA 3320 Seattle St. Louis Data Preparation.ipynb

The file that contains the clean data file is called:
  clean_seattle_stl_weather.csv
