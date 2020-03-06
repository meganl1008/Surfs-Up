# Surfs Up
I've decided to travel to Hawaii and will need to do some climate analysis on the area for my trip planning.

## Files
Hawaii.sqlite

## Step 1: Climate Analysis and Exploration
- Use SQLAlchemy create_engine to connect to your sqlite database 
- Use SQLAlchemy automap_base() to reflect your tables into classes and save a reference to those classes called Station and Measurement

### Precipitation Analysis
- Design a query to retrieve the last 12 months of precipitation data
- Select only the date and prcp values
- Load the query results into a Pandas DataFrame and set the index to the date column
- Sort the DataFrame values by date
- Plot the results using the DataFrame plot method  <br />
<img src = "results/precipitation.png" width = "30%">
- Use Pandas to print the summary statistics for the precipitation data  <br />
<img src = "results/precip_summary_table.png" width = "15%"> 

### Station Analysis
- Design a query to calculate the total number of stations
- Design a query to find the most active stations
- List the stations and observation counts in descending order
- Which station has the highest number of observations?
- Design a query to retrieve the last 12 months of temperature observation data (tobs)
- Filter by the station with the highest number of observations
- Plot the results as a histogram with bins=12

<img src = "results/temperature_observation_data.png" width = "30%">
