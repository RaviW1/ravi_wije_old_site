What is weather prediction? and what am I trying to do? 

I am creating a machine learning algorithm that  can predict the maximum temperature in Memphis 

What is autocorrelation? 
Autocorrelation is when the data at a previous timesteps is useful for predicting at a future timestep

How can we use autocorrelation to predict weather?

We can correlate the temperature on one day with the temperature on another day  

Where did I get the data?

I got the data from the NCDC site 
I got data from 1960 to 2018 

What did I do to make the data suitable predict high temperature in Memphis? 

I cleaned up the data by getting rid of the nans, I separated the data into max temp; days; month; year, and 
fixed some other minor bugs

Does our data show autocorrelation?

it has an autocorrelation of .9


What did I do to predict the high temperature?

What is our prediction accuracy?

We had an MEA of 8.4

What am I planning to do next?

I am going to create a random forest model and turn it into a app using coreML 


