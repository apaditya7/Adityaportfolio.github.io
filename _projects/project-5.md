---
title: "Diamond Price Predictor"
excerpt: " A XGBoost Model built on Hex and Snowpark built to predict diamond prices. Utilised Snowflake as a data warehouse.
<br/><img src='images/mobalytics.png'>"
collection: projects
---
Desrciption:

Stored the data on snowflake as the data warehouse and loaded on to hex and used Snowpark and Scikit Learnt as the libraries for the projects. 

Processed the data using Ordinal Encoders and MinMaxScalers to normalise the categorical columns. 
The data was then loaded into a preprocessing pipeline and which was then used into the XGBoost Regression Model. The model was trained and then fine tuned it using Grid Search CV to find the best fitting for the model for both the learning rate and the number of estimators.

The fine tuned model then got a 98% accuracy score when testing the R^2 accuracy. The model was then deployed it as a Vectorised User Defined Function.