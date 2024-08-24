# credit-risk-classification

## Overview of the Analysis

In this project various techniques were used to train and evaluate a model based on loan risk. This was achieved through using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

The main variable of interest in this analysis was the loan_status, which indicates whether a loan is considered healthy (0) or high-risk (1).
To predict loan status, the model used other financial variables such as loan size, interest rate, borrower income, debt-to-income ratio, number of accounts, derogatory marks, and total debt.

* Stages of the Machine Learning Process:
  - Data Preparation: The dataset was imported, and features and labels were separated. The data was then split into training and testing sets using train_test_split.
  - Model Training: A logistic regression model was instantiated and fitted using the training data.
  - Model Evaluation: Predictions were made on the testing data, and the model's performance was evaluated using a confusion matrix and classification report.
* Methods Used:
  - Logistic Regression: The primary algorithm used in this analysis was logistic regression from the sklearn library. 
  - Train-Test Split: The data was split into training and testing sets to train the model on one set and evaluate its performance on another.
  - Confusion Matrix and Classification Report: These evaluation metrics were used to assess the model's performance in predicting healthy and high-risk loans.

## Results

This analysis successfully utilized financial information from the dataset to predict loan status using logistic regression. The model demonstrated high accuracy, precision, and recall for both healthy and high-risk loans, making it a reliable tool for identifying creditworthiness among borrowers.

* The model achieved an accuracy score of 0.99, indicating that it correctly predicted 99% of the loan statuses.
* For healthy loans (Class 0), the precision score was perfect at 1.00, meaning that when the model predicted a loan as healthy, it was correct 100% of the time.
* For high-risk loans (Class 1), the precision score was 0.85, indicating that when the model predicted a loan as high-risk, it was correct 85% of the time.
* The recall score for healthy loans was 0.99, showing that the model correctly identified 99% of the actual healthy loans.
* The recall score for high-risk loans was 0.91, meaning that the model captured 91% of the actual high-risk loans in its predictions.

## Summary

In summary, the model does a great job at identifying high-risk loans, with a precision of 0.84 and a recall of 0.94. This means it correctly finds most of the actual high-risk loans and balances accuracy well. Overall, the logistic regression model is effective in predicting both safe and high-risk loans, showing high accuracy and strong performance for both categories.

### Instructions to Final Work 

You may find the code in the "credit_risk_classification.ipynb" file, located in the "Credit_Risk" folder. 

Thank you! 
