---
layout: post
title: "Random Forest Weather Prediction Algorithm"
date: 2018-07-18
---

I created a new random forest weather prediction model using Sklearn.
I used William Koehrsen's tutorial: https://towardsdatascience.com/random-forest-in-python-24d0893d51c0 to create the model.
The model can predict the maximum temprature ii Memphis with a MAE of 4.44 and an accuracy of 92.72%.
I got the data from www.ncdc.noaa.gov. I had to clean the data, fix some bugs, replace nans, encode the month and day, and get rid of unneeded columns.
The model requires the maximum temprature, percipitation, and minimum teprature of the previous day.
A random forest is a model that uses many of decision trees to make a prediction.
The random forest is a good choice because of the amount of data it uses to come to a conclusion. This means that it is fairly accurate.
For tommorrow which is June 7th 2018 the model predicts a maximum temprature of 90 degrees fahrenheit.


