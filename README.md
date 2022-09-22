# Surfs_Up

## Overview of Analysis
In the effort to open a surf shop in Oahu, Hawaii, our investor is interested in seeing an analysis of the weather conditions for this area in order to acertain that the invesment will not be in vain.

The goal of this analysis was to reveiw the provided dataset of weather conditions and provide statistical analysis the show wheather the weather conditions are compatible with this buisness venture. In order to explore the dataset, we used an SQLite database and SQLAlchemy to connect and facilitate the queries. We then used Python code to create a Flask webpage application that can share the results of the analysis. 

## Results
After doing some preliminary exploration (see climate_analysis.ipynb) we delved into looking specifically at June and December temperature measures to provide an idea of what the weather could look like year round. 

Below depicts the summary tables for those months:

![June Temps Data Summary](https://raw.githubusercontent.com/chichi-ugo/Surfs_Up/381ef7d9eedeab76e9af7ce0cf683c0d2e5d0fc1/images/June_temps_sum.PNG) ![December Temps Summary](https://raw.githubusercontent.com/chichi-ugo/Surfs_Up/381ef7d9eedeab76e9af7ce0cf683c0d2e5d0fc1/images/Dec_temps_sum.PNG)

From this data, we observe:
- The average temperature for June is about $75{\textdegree}$ and the average for December is about $71{\textdegree}$. 
- The maximum temperatures in June and December are $85{\textdegree}$ and $83{\textdegree}$ respectively.
- the minimum temperatures in June and December are $64{\textdegree}$ and $56{\textdegree}$ respectively.

We see that these values are very close together, which could indicate that the weather maintains around a moderate temperature yearound.

## Summary
