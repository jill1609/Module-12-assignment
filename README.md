# Module-12-assignment

## Overview of the Analysis
----
The purpose of the analysis here is to determine the creditworthiness of borrowers at a peer-to-peer lending services company. The task at hand included using the Logistic Regression model with the original data, and then using it a second time with resampled data in order to predict the healthy loans and high risk loans for credit analysis purposes. 

While using the Logistic Regression model, the parameters used for an in-depth credit analysis are balanced accuracy score, confusion matrix and classification report. These parameters put together, portray a very clear picture of how accurate and useful the Logitic Regression model can be for the purpose of credit analysis. 

## Results
---

* Machine Learning model 1: 
    * This model consists of Logistic Regression model fit with original training data for predicting healthy and high risk loans
    * The balanced accuracy score is 95% for this model 
    * The precision score is 99%, whilst the recall score is 99%

* Machine learning model 2:
    * This model consists of Logistic regression model fit with oversampled data for predicting healthy and high risk loans
    * The balanced accuracy score for this model is 99%.
    * Both the precision and recall scores for this model with oversampled data is again 99%.


## Summary 
---
In conclusion, Machine Learning model 2 (fit with oversampled data) performs relatively better than Machine Learning model 1 (fit with original data). This is evident from the fact that model 2 has a higher accuracy score than that of model 1. As such, the Logistic Regression model can prove to be quite useful for credit analysis purposes, and the model with oversampled data is more accurate than the the one used with original data.   


