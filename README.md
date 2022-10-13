Part 1: Analyse and Explore the Climate Data

For this section of the homework please open the folder "surfs up" and run the file "climate.ipynb" in a jupyter enabled enviroment. For this I used VScode with extensions.

Please also ensure to download and store the "resources" folder locally as this contains the CSV files needed for the workbook.

You will find in the workbook a percipitation bar chart and a histogram of the temperature observation data.

Part 2: Design Your Climate App

To run the climate app please open in a python enviroment and run "app.py" - this will generate a local webpage for you to open and explore the data. For this I used VScode.

In this part of the homework I created a Flask API based on the climate data that was created earlier in the "climate" notebook as follows.

- Create the homepage.

- List all the available routes.

- /api/v1.0/precipitation
  Convert the query results from the precipitation analysis using only the last 12 months of data.

- Return the JSON representation of your dictionary.

- /api/v1.0/stations
  Return a JSON list of stations from the dataset.

- /api/v1.0/tobs
  Query the dates and temperature observations of the most-active station for the previous year of data.

- Return a JSON list of temperature observations for the previous year.

- /api/v1.0/<start> and /api/v1.0/<start>/<end>
  Return a JSON list of the minimum temperature, the average temperature, and the maximum temperature for a specified start or start-end range.

  For a specified start, calculate TMIN, TAVG, and TMAX for all the dates greater than or equal to the start date.

  For a specified start date and end date, calculate TMIN, TAVG, and TMAX for the dates from the start date to the end date, inclusive.
