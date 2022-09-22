# Surfs_Up
Weather Data Analysis

## Overview of Analysis
In the effort to open a surf shop in Oahu, Hawaii, our investor is interested in seeing an analysis of the weather conditions for this area in order to ascertain that the investment will not be in vain.

The goal of this analysis was to review the provided dataset of weather conditions and provide statistical analysis the show if the weather conditions are compatible with this business venture. In order to explore the dataset, we used an SQLite database and SQLAlchemy to connect and facilitate the queries. We then used Python code to create a Flask webpage application that can share the results of the analysis. 

## Results
After doing some preliminary exploration (see climate_analysis.ipynb) we delved into looking specifically at June and December temperature measures to provide an idea of what the weather could look like year-round. 

Below depicts the summary tables for those months:
|            |              |
|------------|--------------|
|![June Temps Data Summary](https://raw.githubusercontent.com/chichi-ugo/Surfs_Up/381ef7d9eedeab76e9af7ce0cf683c0d2e5d0fc1/images/June_temps_sum.PNG) | ![December Temps Summary](https://raw.githubusercontent.com/chichi-ugo/Surfs_Up/381ef7d9eedeab76e9af7ce0cf683c0d2e5d0fc1/images/Dec_temps_sum.PNG)|

From this data, we observe:
- The average temperature for June is about $75{\textdegree}$ and the average for December is about $71{\textdegree}$. 
- The maximum temperatures in June and December are $85{\textdegree}$ and $83{\textdegree}$ respectively.
- The minimum temperatures in June and December are $64{\textdegree}$ and $56{\textdegree}$ respectively.

We see that these values are very close together, which could indicate that the weather maintains around a moderate temperature year-round.

## Summary
In order to further provide information to support our inferences from the above observations, we also factored in the precipitation readings from these two months to get an indication of the other aspects of weather that need to be considered.
|            |              |
|------------|--------------|
|![June Temps & Precip Data Summary](https://github.com/chichi-ugo/Surfs_Up/blob/main/images/June_pre_t_sum.PNG?raw=true) | ![December Temps & Precip Summary](https://github.com/chichi-ugo/Surfs_Up/blob/main/images/Dec_pre_t_sum.PNG?raw=true)|

From these tables we see that the average precipitation for June and December are 14% and 22% respectively. This data indicates that there is overall low precipitation year-round, which helps alleviate the worry of the business being rained out. However, to further ascertain this assumption, we also looked at the data from two other months in the year - one from the fall and one from the spring - to get a better picture.

|            |              |
|------------|--------------|
|![April Temps & Precip Sum](https://github.com/chichi-ugo/Surfs_Up/blob/main/images/Apr_pre_t_sum.PNG?raw=true) | ![Oct Temps & Precip Sum](https://github.com/chichi-ugo/Surfs_Up/blob/main/images/Oct_temps_sum.PNG?raw=true)|

From this data, we see again low averages for precipitation (15% for April and 16% for October) as well as average temperatures in the mid-seventies. 

In summation, the data analysis supports the assumption that Oahu, Hawaii has 'good' weather year-round on average - with temperatures averaging in the mid-seventies and low percentage of average precipitation. The data also shows some indication that chances for precipitation increase only slightly during the autumn and winter months compared to the spring and summer.
