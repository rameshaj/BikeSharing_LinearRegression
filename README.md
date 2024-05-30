# BikeSharing_LinearRegression
Using Multiple Linear Regression Algorithm to predict the demand for shared bikes.

## Table of Contents
* [Problem Statement](#problem-statement)
* [Dataset](#dataset)
* [Technologies Used](#technologies-used)
* [Methodology](#methodology)
* [Conclusions](#conclusions)
  
## Problem Statement:
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

The goal of this analysis is to understand the demand for shared bikes among the people after the quarantine situation ended across the US due to Covid-19. 



## Technologies Used:
- Python 3.8.10
- Jupyter Notebooks
- Pandas 1.5.3


## Methodology:
- Data Cleaning.
- EDA.
- Splitting the Data into Train and Test Sets.
- Feature Scaling.
- Iteratively creating models and discarding features based on p-values and VIF.
- Validating the assumptions of Linear Regression on the final model.

## Conclusions:
- Key driver variables for the Bike Demand:
  - Temperature (temp).
  - Year.
  - Working Day.
  - Holiday.
  - Season 
  - Weathersit 
  - weathersit 
  - Windspeed.

