---
title: "Weather Prediction Algorithm"
date: 2018-06-28
disable_comments: true
---
I have made a weather prediction algorithm that predicts the maximum temprature in Memphis.
I did this by following Brandon Rohrer's Udemy course End-to-end data science: Time-series prediction.
To predict the temprature I used the autocorrelation of one day's temprature to the next to predict three days into the future. 
Autocorrelation is when the data at a previous timesteps is useful for predicting at a future timestep.
The data had an Autocorrelation of .9, the data was from 1960 to 2018, and I got the data from www.ncdc.noaa.gov.
I had to prepare the data by getting rid of missing values, seperating the data into maximum temprature and dates, and fixing some other minor bugs.
In the end I achieved a Mean Absolute Error of 8.4. I'm planning to create a random forest model and turn it into an ios app using CoreML.
For the date of June 29, 2018 the algorithm predicts a temprature of 90.01 degrees fahrenheit.

### Scatter plot of the autocorrelation

![autocorrellation](/blog/2018-06-28-weather-prediction_files/autocorrellation.png)


The scatter plot shows that we have a high autocorrelation from the day before to the next.


### A plot of the maximum tempratures

![max_temp](/blog/2018-06-28-weather-prediction_files/max_temp.png)

This plot show the maximum tempratures from 1960 to 2018

My goal is to make an weather forecasting device as accurate as this one:
![weather_rock](/blog/2018-06-28-weather-prediction_files/weather_rock.jpg)
