<h1 align="center">Car Price Prediction with Linear Regression</h1>

## Purpose of Repository:
The used cars market in India has grown rapidly in the recent years and demand for passenger vehicles has encouraged the industry to collect enormous amount of data to serve the customers better. This document proposes an idea to use such a dataset for building a tool that can predict the selling price of a vehicle by using statistical techniques. This proposal includes information and plan of actions to achieve the main goal of this project.

## About Dataset:
The dataset is sourced from a popular website called Kaggle, released by an Indian company named Cardekho. The original dataset includes 13 variables and 8,128 observations, but this is planned to be reduced to 5 variables, where 4 are predictors and 1 is the response variable. Total number of observations will be a random sample of 13% taken from the original dataset which will result in 901 observations in total. The 5 featured are tabulated below:
Variables	Continuous/Discrete/Categorical 	Predictor/Response 
vehicle_brand	Categorical nominal (22 brands)	Predictor
year (model)	Quantitative discrete	Predictor
cubic_capacity	Quantitative continuous	Predictor
km_driven	Quantitative continuous	Predictor
selling_price	Quantitative continuous	Response


## Questions To Be Answered :
1.	Whether a luxury car manufactured by a brand like Mercedes, has a higher selling price than a usual Indian brand like Maruti?
2.	Does an old car have a lower value in the resale market? (Except for classic vehicles)
3.	How does an engine specification of a car affect its selling price?
4.	Does the resale price of the car drop as its distance covered increases?

Finding answers for the above questions will help me perform Exploratory Data Analysis to identify the causal relationship between the variables. Having this clarity would help me develop a multiple linear regression model that fits the data and will allow me to check if the fitted model has a higher explanatory power which could be interpreted by computing R2 value.


## Objective:
The main goal of this project is to predict the price of a used Indian car (selling_price) based on 4 regressors mentioned: vehicle_brand, year, cubic_capacity, km_driven, selling_price.
        
## Statistical Analysis:    
Firstly, the dataset’s missing values are planned to be handled by imputing the mean/mean after checking the normality of the dataset. Some missing values would be removed based on how it affects the dataset. Multiple Linear Regression is planned to be used to develop a model to fit the data so that selling price of a car can be predicted based on the mentioned regressors. Summary of fit table will be used to interpret the R2 value, sample size and Root Mean Squared Error. ANOVA table will be generated to interpret the measure of significance and Parameters estimates/coefficients table will be used to interpret the P-value. Project is posted on Github, work in-progress can be monitored

     
