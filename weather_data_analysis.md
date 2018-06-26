What is weather prediction? and what am I trying to do? 

I am trying to create a machine learning algorithm that predicts the maximum temperature in Memphis 

What is autocorrelation? 

How can we use autocorrelation to predict weather?

We can correlate the temperature with itself one day before  

Where did I get the data?

I got the data from NCDC

What did I do to make the data suitable predict high temperature in Memphis? 

I cleaned up the data by getting rid of the nans, I separated the data into max temp; days; month; year, and 
fixed some other minor bugs

Does our data show autocorrelation?

Yes


What did I go to predict the high temperature?

What is our prediction accuracy?

We had an MEA of 8.4

What am I planning to do next?

I am going to create a forest model and turn it into a app using coreML 

I have made a weather prediction algorithm that predicts the maximum temprature in Memphis. I did this by following Brandon Rohrer's course End-to-end data science: Time-series prediction. 
To predict the temprature I used the autocorrelation of one day's temprature to the next.
Autocorrelation is when the data at a previous timesteps is useful for predicting at a future timestep.
The data had an Autocorrelation of .9. The data was from 1960 to 2018. I got the data from www.ncdc.noaa.gov.
I had to prepare the data by getting rid of missing values, seperating the data into maximum temprature and dates, and fixing some other minor bugs. 
In the end I achieved a Mean Absolute Error of 8.4. I'm planning to create a random forest model and turn it into an ios app using CoreML.

