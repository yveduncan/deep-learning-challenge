# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The analysis serves the overarching goal of improving the accuracy and reliability of credit risk assessment in lending, which has significant implications for financial institutions and borrowers.

* Explain what financial information the data was on, and what you needed to predict.
The goal of the analysis is to predict the "Loan Status" based on the financial information provided by the loan applicants. By using machine learning models, the analysis seeks to leverage the financial information to make informed predictions about loan applicants' creditworthiness.

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
* Describe the stages of the machine learning process you went through as part of this analysis.
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

Machine Learning Model 1 (Logistic Regression with Original Data):

### Balanced Accuracy Score: 0.99
    #### The model has a high balanced accuracy score, indicating strong performance in correctly classifying both healthy and high-risk loans.
### Precision for Class 0 (Healthy Loans): 1.00
    #### The model has excellent precision for healthy loans, correctly identifying nearly all of them.
### Precision for Class 1 (High-Risk Loans): 0.85
    #### The precision for high-risk loans is good, with 85% of predictions being accurate.
### Recall for Class 0 (Healthy Loans): 0.99
    #### The model has high recall for healthy loans, capturing almost all actual healthy loans.
### Recall for Class 1 (High-Risk Loans): 0.91
    #### The recall for high-risk loans is solid, identifying the majority of actual high-risk loans.



Machine Learning Model 2 (Logistic Regression with Resampled Data):

### Balanced Accuracy Score: 0.99
    #### Model 2 also achieves a high balanced accuracy score, demonstrating strong performance in predicting both healthy and high-risk loans.
### Precision for Class 0 (Healthy Loans): 1.00
    #### The model has exceptional precision for healthy loans, accurately classifying almost all of them.
### Precision for Class 1 (High-Risk Loans): 0.84
    #### The precision for high-risk loans is good, with 84% of predictions being correct.
### Recall for Class 0 (Healthy Loans): 0.99
    #### The model demonstrates high recall for healthy loans, correctly identifying nearly all actual healthy loans.
### Recall for Class 1 (High-Risk Loans): 0.99
    #### The recall for high-risk loans is excellent, capturing almost all actual high-risk loans.

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )

If you do not recommend any of the models, please justify your reasoning.

Both machine learning models show impressive performance, with high balanced accuracy scores, strong precision values, and high recall values, indicating their effectiveness in predicting the loan statuses for both healthy and high-risk loans. The resampled model demonstrates a slightly lower precision for high-risk loans but compensates with an excellent recall, suggesting a good balance between precision and recall.
