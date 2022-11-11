# Project Name
Boom Bikes Demand Analysis - Linear Regression Model


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

Which variables are significant in predicting the demand for shared bikes.
How well those variables describe the bike demands Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors.
Business Goal: You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market.


## Technologies Used

numpy
pandas 
matplotlib.pyplot 
seaborn 
sklearn


## Conclusions

We carried out the analysis using the techique of elimation of variables with OLS method. Our training model resulted in a R square value of almost 80 percent which is acceptable. Which concludes that, almost 80 percent of the data of cnt present in the training set is explained by our independent variables.

The final relationship between demand and predictors is as follows.

cnt = 0.5029 + 0.2650yr + 0.0470workingday + (-0.1292)windspeed + (-0.2602)spring + (-0.2759)Light rain_Light snow_Thunderstorm + (-0.0952)Mist_cloudy + (-0.1196)december + (-0.1079)january + (-0.1290)november + (0.0800)september + 0.0500*saturday.

where 'temp','hum','windspeed' and 'cnt' are normalized.

Our test data set has returned a R Square of 79 percent, which states 79 percent of the data present in test set is explained by the model we have created. This is a descent result to achieve.

Note :

Data has been cleaned to drop outliers that might affect the model adversely The model has been verified for Multicollinearity effects Residual Analysis has been carried out and the model satisfies the assumptions of Ordinary Least Squares approach Q-Q plot between residual distribution and normal distribution shows that residuals follow a normal distribution for all interpolations.


## Contact
@sreejith-rajashekaran 
