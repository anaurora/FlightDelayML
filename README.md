# Flight Delay Prediction

These datasets are taken from Microsoft Azure Machine Learning Studio's sample datasets. It contains flight delay data for various airlines for the year 2013. There are two files uploaded as a compressed archive in this GitHub repository.

1) **Flight_Delays_Data.csv** : This contains arrival and departure details for various flights operated by 16 different airlines. The schema is pretty self explanatory but I will mention the important and slightly obscure columns:

*OriginAirportID/DestAirportID* : The unique 5 digit integer identifier for a particular airport.

*CRSDepTime/CRSArrTime* : Time in 24 hour format (e.g. 837 is 08:37AM)

*ArrDel15/DepDel15* : Binary columns where 1 means that the flight was delayed beyond 15 minutes and 0 means it was not.

*ArrDelay/DepDelay* : Time (in minutes) by which flight was delayed.

2) **Airport_Codes_Dataset.csv** : This file gives the city, state and name of the airport along with the unique 5 digit integer identifier.

The carrier corresponding to the 2 letter IATA code, can be looked up by entering the code [on this website.](http://www.iata.org/publications/Pages/code-search.aspx).

**Goals:**

1. Clean the data, and see which features may be important and which might be redundant.

2. Do an exploratory analysis of the data to identify where most of the flight delays lie (e.g. which carrier, airport etc.).

3. Choose and build an appropriate regression model for this dataset to predict ArrDelay time in minutes.

4. Choose and build alternative models and compare all models with various accuracy metrics.

**The algorithm runs in a Google Colaboratory environment (based on Jupyter notebooks), which is independent of the local machine. They are ipython notebooks and all you need is a browser to run them.**

**NOTE: If GitHub fails to load the ipython file(s) (.ipynb), you can access them using nbviewer. SGD regression can be viewed [here](https://nbviewer.jupyter.org/github/AnujArora23/FlightDelayML/blob/master/SGDFlightDelayDataset.ipynb)**
