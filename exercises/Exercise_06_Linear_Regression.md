# Week 6 Exercises: Statistics for Data Science

### Question 1: Sea Level Rise

The file key_west.csv contains Mean Sea Level values monthly for Key West, Florida.
Use this data to fit a linear regression model with target value the Monthly_MSL column and predictor variable the Year.

a. What coefficient do you obain for the Year variable? Is it statistically significant?

b. How can we interpret the meaning of this coefficient?

### Question 2: Penguins

For these questions, you'll be working with the penguins dataset.

a. Fit a linear regression model with target variable body_mass_g and predictor flipper_length_mm. Interpret the meaning of the coefficients you get. What does the model estimate the average body_mass_g will be for a penguin with flipper length of 190 mm? Create a prediction interval for a flipper length of 190 mm and interpret the meaning of this interval.

b. Check whether the coefficients you got in part a are statistically significant.

c. Fit a model with target variable body_mass_g and predictor variable sex. Interpret the meaning of the coefficients you get.

d. Fit a model with target variable body_mass_g and predictor variable species. Interpret the meaning of the coefficients you get.

### Question 3: King County Home Prices
The file kc_sample.csv contains a sample of 1000 homes that were sold in King County, Washington. 

Build a linear regression model with target variable `price` and predictor variable `sqft_living`. How well does this model perform? Plot confidence intervals and prediction intervals against your dataset. Check the residuals. What problems might be present in this model?