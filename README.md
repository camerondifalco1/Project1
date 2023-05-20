# Project1
Project1

Resources:


Output Data:
Map of countries involved in Happiness Report.
Map showing life expectancies in countries.

Python Working Files:

    PB_Maps:
     - Using the 2015 Merged file    
     - 2015_Life_happines_mergedupdate.csv

     - Access Geoapify API: to grab latitude & longitude for each country.
     - https://apidocs.geoapify.com/docs/geocoding/forward-geocoding/#about 

     - Used Geoapify Playground to assist in building the API query: 
     - https://apidocs.geoapify.com/playground/geocoding/

     - Generate map to show the counties involved in the Happiness Report.
     - Generate map to show the life expectancy in each country.

    support_and _freedom:
     - Using the 2015 Merged file    
     - 2015_Life_happines_mergedupdate.csv

     - Clean data for required columns, 
        - family=family & social connections
        - freedom=freedom to make life decisions
        - give countries a ranking happiness
        - add columns for calculation of 
             - percentage of happiness from family
             - percentage of happiness from freedom

     - Group data by continent, explore data using boxplots

     - Scatter plots and line of regression to see if the following correlates to happiness or life expectancy, for all countries, and top/bottom 20
         - Happiness vs family & social support
         - Happiness vs freedom to make life choices
         - Life expectancy vs family & social support
         - Life expectancy vs freedom to make life decisions

    life_happiness_variance:
         - explore happiness score vs life expectancy to see if they correlate overall


