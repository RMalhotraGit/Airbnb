# Analysis of Prices for Airbnb Listings in Major US Cities
## Abstract:
The focus of the project is to design models which will be used to predict and interpret the price of various Airbnb listings in major US cities using several factors. Among the factors, the most important ones were determined while others were omitted due to a lack in predicting capability. These results are useful for Airbnb hosts looking to create a new listing, as they can prioritize their time and investments towards aspects of a listing that will yield them the most return on their investment. To conduct the analysis, a dataset containing 74,111 listings was used, which included 28 predictors and the response, which is the logarithm of a listing’s price. Prior to any analysis, some predictors were omitted, such as those consisting of text, categorical variables with several (hundreds) classes, and listings with missing data. The final dataset consisted of 47,787 listings and 15 predictors. Then, analysis was done which included several different models from the three approaches: 1) linear, 2) non-linear, and 3) tree based. To evaluate the models, the test mean squared error (MSE) was reported and it was found that the random forest model performed the
best. The first three datasets come from https://www.worldometers.info/coronavirus/ and the last comes from https://www.insidernj.com/bergen-county-town-covid-19-list-15982-cases-total-friday/

## Files:
MSDS Final Project.Rmd - R Markdown file used to generate report

Dataset:
The dataset is too large to be uploaded but can be found on https://www.kaggle.com/rudymizrahi/airbnb-listings-in-major-us-cities-deloitte-ml
