#SQLAlchemy Challenge

This project examines climate data station in Hawaii. Utilizing SQLAlchemy and SQLite to analyze data from hawaii.sqlite. Next steps is to create API with Flask to show queries. 

#Section 1 - Climate Analysis

Utilizing SQLAlchemy to create engine to connect to SQLite database. Using the automap_base function to reflect tables into classes named station and measurent. By using pandas to plot the last 12 months of precipitation which indica the higest precipitation between July - September of 2016.

The most recent date found in the measurement table: 08.23.2017
Station with the greatest number of observations: USC00519281', 2772
Lowest Temperature: 54.0
Highest Temperature: 85.0
Average Temperature: 71.66378066378067

#Section #2 - Climate App
A Flask API was design based on the queries found in Climate Analysis section #1.

The routes below shows the following: 

api/v1.0/precipitation - Return a JSON representation of precipitation data for the last 12 months
api/v1.0/stations - Return a JSON list of stations
api/v1.0/tobs - Return a JSON list of temperature observations for the most active station
api/v1.0/<start>/<end> -  Return a JSON list of the minimum, average, and maximum temperatures for a date range.


