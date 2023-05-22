# Project1 - Happiness and Life Expectancy

## Description
_Project 1 Challenge - University of Adelaide - Data Analytics BootCamp_

Team: Paula Beckett, Juanita Sands, Joey Zheng, Cameron DiFalco

We are exploring whether happiness impacts life expectancy, and what impacts happiness and life expectancy?

Our analysis is summarised in our powerpoint presentation, titled: DAB Group 3 Powerpoint.

**Research Questions to Answer:**

Which are the happiest countries?
What are some factors that can impact life expectancy?
  - Compare factors against happiness rating:
      - Country Wealth measured predominantly through GDP
      - Health
      - Schooling
      - Social Support
Do those living in happier countries have a higher life expectancy?

The analysis was performed using pandas, matplotlib, hyplot and is outlined further below.

## **Resources**
The World Happiness Report 2015 (csv)

World Health Organisation – Life Expectancy Report (csv)

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
         
    JRSProject1-FinalVersion:
         - explores the impact of GDP per capita, generosity and Income Composition of Resources on happiness and life expectancy to see if they correlate
         
    Joey_Project1_health:
         - explores the impact of health on happiness and life expectancy to see if they correlate
         
    cameron code doc:
         - explores the impact of schooling on happiness and life expectancy to see if they correlate    

## Authors and acknowledgements
Paula Beckett  https://github.com/PaulaBeckett

Juanita Sands  https://github.com/wickedwes78

Joey Zheng  https://github.com/joey52chopin

Cameron DiFalco  https://github.com/camerondifalco1

