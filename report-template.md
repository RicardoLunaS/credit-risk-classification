# Module 12 Report Template

## Overview of the Analysis

The purpose of this analysis is to evaluate the logistic regression model created in order to classify loans as Healthy Loans or High Risk Loans. 

To create this model, historical data was used from previous lending activity which included the following variables:
    1) Loan amount
    2) Interest rate %
    3) Yearly borrower income
    4) Debt to income ratio
    5) Number of accounts
    6) Derogatory marks
    7) Total Debt

The predicting variable was the loan status which is a binary variable, 0 was considered a Healthy Loans and 1 for High Risk Loans.

For the creation of this model, the data set was separated in a response array and a features dataset that were used to determine the type of loan.
Then, the feature dataset and response array were split, one for training the model and other for testing the model.
Finally, the data was fitted in to a Logistic Regression model.

## Results

* Logistic Regression:
    - Accuracy: 99%
    - Precision: Healthy Loans = 100%, High Risk Loans = 85%
    - Recall scores: Healthy Loans = 99%, High Risk Loans = 91%

## Summary

The Logistic Regression model is good on predicting Healthy Loans but not for High Risk Loans.
It is important to notice that for the financial well being of the company to improve the prediction precision of the High Risk Loans.
