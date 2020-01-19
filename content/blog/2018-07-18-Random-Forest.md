---
title: "Random Forest Weather Prediction Algorithm"
date: 2018-07-18
slug: random-forest
categories: []
tags: []
disable_comments: true
---

I created a new random forest weather prediction model using Sklearn.
I used [William Koehrsen's tutorial](https://towardsdatascience.com/random-forest-in-python-24d0893d51c0) to create the model.
The model can predict the maximum temperature in Memphis with a MAE of 4.44 and an accuracy of 92.72%.
I got the data from  the [National Centers for Environmental Information](www.ncdc.noaa.gov). I had to clean the data, fix some bugs, replace nans, encode the month and day, and get rid of unneeded columns.
The model requires the maximum temperature, precipitation, and minimum teperature of the previous day.
A random forest is a model that uses many decision trees to make a prediction.
The random forest is a good choice because of the amount of data it uses to come to a conclusion. This means that it is fairly accurate.
For tomorrow, which is June 19th 2018, the model predicts a maximum temperature of 90 degrees Fahrenheit.
My goal in the future is to convert this into an ios app using CoreML.
<!--[The code for the random forest model](https://raviw1.github.io/code/Weather_RFv2).-->  

### A smaller version of one the decision trees.

![small_tree](/blog/2018-07-18-Random-Forest_files/small_treev2.png)


### A comparison of my random forest model's predictions, my autocorrelation model's predictions, and the real temprature.

![temps](/blog/2018-07-18-Random-Forest_files/temperatures.png)

As shown in the graph the random forest model is much closer than the autocorrelation model which is predicting temperatures lower than the actual temperatures.

