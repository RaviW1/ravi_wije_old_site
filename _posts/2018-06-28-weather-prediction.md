---
layout: post
title: "Weather Prediction Algorithm"
date: 2018-06-28
---
I have made a weather prediction algorithm that predicts the maximum temprature in Memphis.
I did this by following Brandon Rohrer's course End-to-end data science: Time-series prediction.
To predict the temprature I used the autocorrelation of one day's temprature to the next. 
Autocorrelation is when the data at a previous timesteps is useful for predicting at a future timestep.
The data had an Autocorrelation of .9, the data was from 1960 to 2018, and I got the data from www.ncdc.noaa.gov.
I had to prepare the data by getting rid of missing values, seperating the data into maximum temprature and dates, and fixing some other minor bugs.
In the end I achieved a Mean Absolute Error of 8.4. I'm planning to create a random forest model and turn it into an ios app using CoreML.

the autocorrelation
![config.yml]({{ site.baseurl }}/data_images/autocorrellation.png)
