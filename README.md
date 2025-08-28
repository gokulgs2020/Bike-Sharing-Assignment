# Multi linear regression analysis 
> MLR analysis to identify the features affecting bike rental demand. The MLR is performed using RFE and viewing the summary statistics and multi collinearity using VIF to identify features to be dropped.


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

## General Information
- Provide general information about your project here.
- A bike sharing rental company wants to understand the key features that impact the demand for bike rental bookings. The company has shared the bookings related data points like temperature of the day, sesaon and weather conditions to use for modelling and prediction
- Based onthe model output we can predict conditions that can lead to increase or decrease in demand.

## Conclusions
The top 3 variables that impact bike rental bookings are
- Temperature (change of 1 unit increases bookings by 0.4960 units)
- Presence of Light Snow or Light Rain (Weathersit=3) (if there is light snow the bookings drop by 0.2396 units)
- Year (increase in bookings by 0.2307 units in 2019 vs 2018)

Impact of some categorical variables
- Season - Bookings increases from Seasons 1 to 3. Fall has maximum bookings follow by Summer and winter and spring
- Year - Significant jump in bookings in the year 2019 compared to 2018. Overall bike sharing is gaining popularity. Regression coeff 0.2307. Increase in bookings by 0.2307 units in 2019 vs 2018)
- Month - Bookings increase from Jan till May and peak during the months 6 to 9 before again dropping slowly till Dec
- Weather type - Maximum bookings happen in clear weather conditions and drop as the weather worsens



## Technologies Used
- Python 3
- Key libraries like statsmodels, sklearn



## Acknowledgements
- Thanks to IITB and Upgrad team to share the data set required for all the analysis


## Contact
Created by [@gokulgs2020] - feel free to contact me!


