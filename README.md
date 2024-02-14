# credit-risk-classification
## Module 20 Challenge

Tamara Hundich

02/13/2024

Michigan State University edX Data Analytics Bootcamp 

In this Challenge, you’ll use various techniques to train and evaluate a model based on loan risk. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

## Before You Begin 

- Create a new repository for this project called credit-risk-classification. Do not add this homework to an existing repository.
- Clone the new repository to your computer.
- Inside your credit-risk-classification repository, create a folder titled "Credit_Risk."
- Inside the "Credit_Risk" folder, add the credit_risk_classification.ipynb and lending_data.csv files found in the "Starter_Code.zip" file.
- Push your changes to GitHub.

## Instructions
The instructions for this Challenge are divided into the following subsections:
- Split the Data into Training and Testing Sets
- Create a Logistic Regression Model with the Original Data
- Write a Credit Risk Analysis Report

## Split the Data into Training and Testing Sets
- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets by using train_test_split.

## Create a Logistic Regression Model with the Original Data
Use your knowledge of logistic regression to complete the following steps:
- Fit a logistic regression model by using the training data (X_train and y_train).
- Save the predictions for the testing data labels by using the testing feature data (X_test) and the fitted model.
- Evaluate the model’s performance by doing the following:
    - Generate a confusion matrix.
    - Print the classification report.
- Answer the following question: How well does the logistic regression model predict both the 0 (healthy loan) and 1 (high-risk loan) labels?

## Credit Risk Analysis Report
- Read the lending_data.csv data from the Resources folder into a Pandas DataFrame.
- Create the labels set (y) from the “loan_status” column, and then create the features (X) DataFrame from the remaining columns.
- Split the data into training and testing datasets by using train_test_split.

## Install 
Scikit-learn, Pandas, Visual Studio Code or Anaconda Jupyter Notebook for code 