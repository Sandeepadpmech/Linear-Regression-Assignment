# Bike Sharing System - Multiple Linear Regression Model 
To build a multiple linear regression model for the prediction of demand for shared bikes and to understand, 
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands


## Table of Contents
* [General Info]
* [Technologies Used]
* [Conclusions]
* [Acknowledgements]


## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. 

The company wants to know:
Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands

Business Goal:

You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features.

Model Building

In the dataset provided, you will notice that there are three columns named 'casual', 'registered', and 'cnt'. The variable 'casual' indicates the number casual users who have made a rental. The variable 'registered' on the other hand shows the total number of registered users who have made a booking on a given day. Finally, the 'cnt' variable indicates the total number of bike rentals, including both casual and registered. The model should be built taking this 'cnt' as the target variable.

Model Evaluation:

When you're done with model building and residual analysis and have made predictions on the test set, just make sure you use the following two lines of code to calculate the R-squared score on the test set.


## Conclusions
The demand for the bikes depends on the following fatcors
Year, Holiday, Summer, Saturday, months of February, January, November, September, Lightsnow+Rain, Mist+Cloudy, atemp

The demand increses in
Summer, November, September, Year 2019 and atemp

The demand decreses in
Holiday, Sunday, February, January, Lightsnow+Rain, Mist+Cloudy



## Technologies Used
- panda - version 1.4.2
- sklearn - version 0.20.1
- seaborn - version 0.11.2
- matplotlib - version 2.2.3
- numpy - version 1.21.5


## Acknowledgements
Give credit here.
- This project was created as a part of assignment, submitted to UPGRADE and IIIT Bangalore 

## Contact
Created by [@sandeepadpmech] - feel free to contact me!



```python

```
