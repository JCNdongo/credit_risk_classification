# credit_risk_classification
Credit Risk Analysis Report: Building a model that evaluates borrowers' creditworthiness 

# Overview
Using consumer lending data, a peer-to-peer lender has commissioned an analysis to determine the creditworthiness of its potential clients.

The analysis consisted of logistic regressions with loan status as the dependent (y) variable and the following independent variables (X): loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt. 

# Analysis
The dependent (y) variable is binary: (0) for healthy loans, and (1) for high-risk loans. The analysis followed the steps below:
1. Read the data from the original .csv file, created a data frame  then split the data into training and testing data.

2. Processed a logistic regression with a model based on the original data. This model returned an accuracy score of 99%, accurately predicting heatlhy loans with precision scores of of 1 and 0.87 for high risk loans.
![image](https://github.com/JCNdongo/credit_risk_classification/assets/120480912/891c54c0-e129-4804-9152-0ae5d29c0984)


3. Resampled the training data, then processed a logistic regression on that data. The model based on the resampled data returned an accuracy score of 100% and precision scores  of 1 for heatlhy loans and 0.87 for high risk loans.
![image](https://github.com/JCNdongo/credit_risk_classification/assets/120480912/9fbcbe42-7137-4711-83f3-da8e54b420ca)


# Summary
I would recommend this model to the lender with some reservations. While the accuracty and precision scores are high, they indicate the possiblity of missing varaibles. Additional factors should be considered for more accurate and realistic analysis of the borrowers' creditworthiness.
