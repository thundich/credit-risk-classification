# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. 

* The purpose of this credit risk report is to create a model that would predict credit worthiness for borrowers trying to obtain a loan at the bank. By using linear regression, we were able to determine the accuracy, precision, and recall scores for healthy and high risk loans that were provided in the dataset. 
* The credit worthiness were based on a number of factors that were all found in the CSV that was provided: 
  - loan size (amount)
  - interest rate
  - borrower's income
  - debt to income ratio
  - total number of accounts
  - derrogatory marks found on credit
  - total debt
  - loan status. 
* The y value were the labels of the dataset and this was the target variable. This variable was classified as either a 0 or 1. The 0 represented a healthy loan and a 1 was represented as high-risk. The x variable were the features of the dataset. 
* The Stages of the Machine Learning Process that were performed in this report were: 
  - Gathering Data
  - Date Preparation
  - Data Wrangling 
  - Analyse Data
  - Train Model
  - Test Model 
  - Deployment 
* The Logistic Regression Model with resampling method were performed to observe the accuracy for the credit risk classification. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  - Accuracy: 96% 
  - Precision: for 0 100%, for 1 86% 
  - Recall scores: for 0 99%,  for 1 93%


* Machine Learning Model 2:
  - Accuracy: 99%
  - Precision: for 0 100%, for 1 86% 
  - Recall scores: for 0 99%,  for 1 100%

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
  - The Machine Learning Model 2 appears to have better accuracy results than the Machine Learning Model 1. The precision on both models mirror each other. Therefore, the conclusion is that Machine Learning Model 2 performed best based on the accuracy results and would be the recommended model to be used to determine credit risk worthiness. The higher recall scores also gives us the conclusion that this model is better at identifying samples that would have askewed results. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
  - Performance is impacted based on the problems trying to be solved. If we are trying to predict the just the 0s, there would also be other factors that could influence the credit risk worthiness and accuracy. 

