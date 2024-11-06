
## Overview of the Analysis

The purpose of this analysis was to predict whether a loan is "healthy" (0) or "high-risk" (1) based on financial data such as loan size, interest rate, borrower income, and debt-to-income ratio. The goal was to build a model that could accurately predict loan status.

Key Variables:
- Loan Status: The target variable to predict (0 for healthy loans, 1 for high-risk loans).
- Other features include financial variables like loan size, income, and debt-to-income ratio, which were used to make predictions.

Machine Learning Process:
- Data Preprocessing: Cleaned the data and separated features and target variable.
- Model Training: We used Logistic Regression, which is a common algorithm for binary classification.
- Model Evaluation: We evaluated the model’s performance using accuracy, precision, recall, and F1-score.

## Results

Logistic Regression Model:
- Accuracy: 99%
- Precision (Healthy Loans): 1.00 (Perfect)
- Recall (Healthy Loans): 1.00 (Perfect)
- F1-Score (Healthy Loans): 1.00
- Precision (High-Risk Loans): 0.86
- Recall (High-Risk Loans): 0.91
- F1-Score (High-Risk Loans): 0.88
- 
Summary of Key Metrics:
- The model is highly accurate overall (99%).
- It perfectly predicts healthy loans (precision and recall of 1.00).
- For high-risk loans, it has good recall (91%) but could improve precision (86%) to avoid misclassifying healthy loans as high-risk.

## Summary

The Logistic Regression model performs very well, especially at predicting healthy loans. It’s also good at identifying high-risk loans, though it could be better at avoiding false positives (predicting healthy loans as high-risk).

Recommendation:
- Best Model: Logistic Regression is the best choice, with excellent accuracy and performance for healthy loans.
- Considerations: If it’s important to reduce false positives (misclassifying healthy loans as high-risk), there is room for improvement, but overall, this model is highly effective.
