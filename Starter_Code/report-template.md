# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

# Purpose of the analysis
This analysis aims at developing and evaluating a predictive learning model to identify the creditworthiness of borrowers so that lenders can make an informed decision and manage their risk better.

# Financial Information 
The datset used for the analysis includes the following:
'Loan_size', 'interest_rate', 'borrower_income', 'debt_to_income', 'num_of_accounts', 'derogatory_marks', 'total_debt' ,'loan_status'
Our primary focus was on column 'loan_status' where 0 indicates a healthy loan and 1 indicates a high risk loan. 

# Target Variable 
This analysis primarity targets high risk loans with Key variables as:
- X variable represents borrower's income, number of accounts, debt to income ratio of the borrower and total amount of debt. 
- Y variable represents 'loan_status' where 0 indicates a healthy loan and 1 indicates a high risk loan. 


# Stages of the machine learning process

The machine learning process was divided into the following stages:

- Data Cleaning, Exploration and preparation- reading, understandinga splitting the data into training and testing sets.

- Model Building- using Logistic Regression model to train the data.

- Model Evaluation - Assessing the perfomamce of the model using confusion matrix and classification reports.  

- Model Interpretation- summarizing the results.

# Methods used (e.g., `LogisticRegression`, or any other algorithms).
Methods used for the analysis were:
- Logistic regression algorith to identify the credit worthiness of the borrowers.
- Resampling technique to gather more information of the dataset, improve accuracy and estimate the uncertainity.
- Confusion matrix and classification report to evaluate the performance of the model.


## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
        - Overall Accuracy - 99.2%

        - Healthy Loan 
            - precision: 99.7%
            - recall: 99.5%

        - High Risk Loan 
            - precision: 84.7%
            - recall: 91.0%

* Machine Learning Model 2 - Oversampled:
    * Description of Model 2 Accuracy, Precision, and Recall scores.
        - Overall Accuracy - 99.2%

        - Healthy Loan 
            - precision: 100%
            - recall: 99.4%

        - High Risk Loan 
            - precision: 84.1%
            - recall: 99.4%


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Both models perform well with high accuracy in predicting healthy loans (>99%) and high precision when predicting high risk loans (~84%).Both the models show nearly perfect results with  Model 2 (oversampling) being slightly better in identifying high-risk loans(recall) by 8%.

The choice of model may depend on the specific problem being addressed. For example, if it is crucial to accurately predict high-risk loans, Model 2 might be preferred due to its higher precision for high-risk loans and almost negligible drop in performance of other metrics.