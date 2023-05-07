# sqlalchemy-challenge

Background: I have decided to treat myself to a long holiday vacation in Honolulu, Hawaii. To help with my trip planning, I have decided to do a climate analysis about the area. I will be analysing the precipitation and the stations to help me accomplish this goal.

## Part 1: Analyse and Explore the Climate Data
In this section, I’ll use Python and SQLAlchemy to do a basic climate analysis and data exploration of your climate database. Specifically, I’ll use SQLAlchemy ORM queries, Pandas, and Matplotlib. I will be answering the question, which station id has the greatest number of observations? and also analysing the precipitation levels

## Part 2: Design Your Climate App
Since the initial climate analysisis complete, I will design a Flask API based on the queries that I developed. Using Flask, I will create routes for the following:

The homepage ("/"), which lists all available routes.
"/api/v1.0/precipitation", which converts the query results to a dictionary using date as the key and prcp as the value, and returns the JSON representation of the dictionary.
"/api/v1.0/stations", which returns a JSON list of stations from the dataset.
"/api/v1.0/tobs", which queries the dates and temperature observations of the most-active station for the previous year of data, and returns a JSON list of temperature observations for the previous year.
"/api/v1.0/<start>" and "/api/v1.0/<start>/<end>", which return a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range. For a specified start, the API calculates TMIN, TAVG, and TMAX for all the dates greater than or equal to the start date. For a specified start date and end date, the API calculates TMIN, TAVG, and TMAX for the dates from the start date to the end date, inclusive.
  
  Bibiliography
  https://github.com/sliwet/sqlalchemy-challenge/
  https://www.earthdatascience.org/courses/use-data-open-source-python/use-time-series-data-in-python/date-time-types-in-pandas-python/customize-dates-matplotlib-plots-python/
