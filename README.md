# COVID__CAHousing

## COVID-19 Impact on California Housing Market

This research embarks on an exploration of the intricate effects of the pandemic on the housing markets, aiming to provide a comprehensive understanding of its impact on California home prices. The complex interplay between public health measures, policy interventions, and technological advancements and its effects on the housing market are unraveled.

The primary objective of this study is to analyze the impact of the COVID-19 pandemic on California home prices by creating a forecasting model using both statewide and county-level data.  The current state reveals a real estate sector navigating through economic uncertainties, influenced by fluctuations in market conditions, government interventions, and evolving consumer preferences. A macro-level view is captured through the statewide average home price, while a more comprehensive understanding is gained by individual county-level data.

This study unravels the layers of influence, ensuring a comprehensive understanding of the dynamics shaping the impact of the pandemic on California’s housing market.  By employing a time series analysis on the median price of existing single-family in California from January 1990 to September 2023, sourced from the California Association of Realtors, the significance of this research extends beyond a macro-level overview, utilizing state and county-level data to capture regional variations and key drivers influencing market dynamics.


This repository contains the 4 csv files that were used to create out data pipeline as listed below: 

California State Jobs csv from Kaggle.com - https://www.kaggle.com/datasets/datasciencedonut/california-state-jobs  
2023 Income Limits by County from CA.gov website - https://data.ca.gov/dataset/income-limits-by-county 
Median Prices of Existing Single Family Homes - https://www.car.org/en/marketdata/data/housingdata 
      Note: There was a manual deletion of the first 7 lines from the Median Prices of Existing Single Family Homes file and csv conversion before loading into mysql workbench 

The repository also contains a Income Limits Data Dictionary that was obatined from https://data.ca.gov/dataset/income-limits-by-county which explains the column names for the 2023 Income Limits by County csv 

There is a finalproject_azure.sql file which outlines all of the data extraction, loading and transformation processes that were performed to build the database. 
The adsfinalproject.ipynb file contains all of the data analysis, visualizations and build of the dashboard used for the project. 
There is a JSON file (template.json) that was exported from Microsoft Azure which defines the infastructure and configuration of the database. 

The database is being stored on a Microsoft Azure server and can be accessed with the following credentials: 
Host ID: jobsfinal507.mysql.database.azure.com 
Username: admin507
Password: finalproject507!


