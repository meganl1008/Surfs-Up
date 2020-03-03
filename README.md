# sqlalchemy-challenge

This project is designed to share my knowledge on Advance Data Storage
[technologies utilized: SQLAlchemy ORM queries, Pandas, Matplotlib]

In this project, I have conducted analysis and data exploration from a climate database containing historical data on Hawaii's weather (using sqlite files)

<b>Step 1: Climate Analysis </b>

Precipitation Analysis
1. Used SQLAlchemy to connect to sqlite database
2. Designed a query to retrieve the last 12 months of precipitation data 
3. Loaded query results into Python 
4. Created data visualizations to analyze weather trends

Station Analysis
1. Designed a query to calculate the total number of stations
2. Desgined a query to find the most active stations
3. Plot results 

<b>Step 2: Climate App </b>

Goal: Designed a Flask API based on the queries determined in Step 1
Process: Used Flask to create routes

<b>Step 3: Performed additional analysis </b>
- Temperature Analysis 1 using SQL Alchemy: Determined monthly temperature trends and calculated average temperatures at all stations across all years 
- Temperature Analysis using Python: Calculated daily normals (avg, min, max, temps) to identify best times of the year to travel to Hawaii based off weather trends
