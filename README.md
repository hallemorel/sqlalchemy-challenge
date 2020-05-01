# sqlalchemy-challenge
Climate Analysis of Honolulu, Hawaii:

In this project I used Python and SQLAlchemy to do basic climate analysis and data exploration of the climate database.

I used the SQLAlchemy create_engine to connect to the sqlite database and automap_base() to reflect the tables into classes.

The query does the following:


  -  Retrieve the last 12 months of precipitation data.

  -  Station Analysis:

	Calculates the total number of stations.
  
	Finds the most active stations and lists them and their counts in descending order.
  
	Finds which stations have the highest number of observations.
  
  -  Retrieves the last 12 months of temperature observations and filters by the station with the highest number of observations. 

After creating these queries I created a Flask API to create my routes. 
