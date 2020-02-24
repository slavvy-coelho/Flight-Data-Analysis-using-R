# Flight-Data-Analysis-using-R

This project aims to build a prediction model for predicting flight delays for the year 2013. The project consists data of domestic flights that departed from the three major New York City airports in 2013. The data was collected over the entire year of 2013 and consists of various factors such as scheduled flight time, scheduled arrival time, weather details, carrier details, etc. This data pertains to three major airports viz, John F. Kennedy International Airport (JFK), Newark Liberty International Airport (EWR) and LaGuardia Airport (LGA).
In this project, various statistical learning frameworks for both classification and regression were explored to build efficient prediction models. The models were explored and improved by standard statistical tests and tuning and the results were compared to in turn select the best one for prediction on the held-out test set.


##DATA
The data is taken from the ‘nycflights13’ package in R. The folder 'DATA' consists of a csv file named fltrain.csv which was combined using the following 4 datasets from this package:
§ Flights: all flights that departed from NYC in 2013 (schedule and logistical modifications)
§ Weather: hourly meteorological data for each airport
§ Airports: airport names and locations
§ Planes: construction information about each plane
It contains 43 variables measured on 200,000 flights. The dataset contains information about all flights departed from NYC in 2013, hourly meteorological data for each airport, airport names and locations, construction information about each plane.
