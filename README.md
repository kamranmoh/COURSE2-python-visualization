# Python-data-analytics
This showcase has the following features:

Raw data: 
Min/max temperature data of Vestervig (a place in north –west Denmark) is downloaded from a source in web (The National Centers for Environmental Information - Daily Global Historical Climatology Network) as csv. Data columns we are interested in are weather station id (ID), date (date), type of temperature (element type (TMAX, TMIN)) and finally value of temperature in each type (value).

Report features:
  
1.	A line graph of the record high and record low temperatures by day of the year over the period 2005-2014. The area between the record high and record low temperatures for each day should be shaded.
2.	Overlay a scatter of the 2015 data for any points (highs and lows) for which the ten year record (2005-2014) record high or record low was broken in 2015.
3.	Removal of leap days from the dataset for the purpose of this visualization.

Code consists of:

•	Pandas dataframes

•	Numpy arrays

•	mplleaflet to convert Matplotlib plots into Leaflet web geographic maps

•	Cleaning, structuring and enriching raw data into a desired format (data wrangling)

•	Working with dates

•	Data aggregation

•	Pivot tables

•	Matplotlib multiplotting


IDE: Jupyter notebook
