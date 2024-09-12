# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
The purpose of the analysis was to develop a model to predict credit risk.
* Explain what financial information the data was on, and what you needed to predict.
The financial information used were seven features ("loan_size", "interest_rate", "borrower_income",  "debt_to_income",  "num_of_accounts",  "derogatory_marks", "total_debt") and loan status. 
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
The model is trying to predict how many loans were predicted to be good loans and they were. 
* Describe the stages of the machine learning process you went through as part of this analysis.
Imported the modules, read the csv file, seperated the data into labels (loan_status) an features (the remaining columns).
* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
used lr (LogisticRegression). This is a classification model. Balance, Recall and the f1 score are important.

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.
* the precision score indicates that the model predicts True positives at 100% but only on 87% of the time.
* the recall score of 0.95 indicates that True positives were predicted 95% of the time 

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
* the precision score indicates that the model predicts True positives at 100% but only on 87% of the time.
* the recall score of 0.95 indicates that True positives were predicted 95% of the time 
## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best?
the LinearRegression model works well for this classification problem.
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
In the case of predicting credit risk it is important to be able to predict risk correctly. A lender cannot stay in business with excessive bad loans.
It is perhaps more important to have low false positives. Better to incorectly predict a good loan than to lend money to someone who will not pay.

If you do not recommend any of the models, please justify your reasoning.
