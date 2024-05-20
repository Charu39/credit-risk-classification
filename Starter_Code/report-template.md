# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
* Explain what financial information the data was on, and what you needed to predict.
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).

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