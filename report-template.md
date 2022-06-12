# Module 12 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

*ANSWER: the purpose of this analysis is to use supervised machine learning (LogisticRegression & RandomOverSampler) to make predictions on loan status and evalute the result metrics
* Explain what financial information the data was on, and what you needed to predict.

*ANSWER: The financial info includes loan size, interest rate, borrower income, Debt to income ratio, ect and we need to predict the loan status
* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).

*ANSWER: Out of all the loans, 2500 are unhealthy loans (by using value_counts)
* Describe the stages of the machine learning process you went through as part of this analysis.

*ANSWER: 1. split data by using train_test_split
*ANSWER: 2. instantiate a LogisticRegression model
*ANSWER: 3. make predictions
*ANSWER: 4. Evaluate the model’s performance

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any resampling method).

*ANSWER: LogisticRegression and RandomOverSampler have been used in this analysis

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.


* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

*ANSWER: it seems logistic regression model predicted '0' almost perfecly, both precison and Recall close to 100%; logistic regression model predicted '1' pretty well, 0.85 precison and 0.91 Recall.


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
*ANSWER: logistic regression model (fit with oversampled data) predicted '0' almost perfecly, both precison and Recall close to 100%. It improved prediction for '1' , similar precison at 0.84 (vs 0.85) but higher Recall at 0.99 (vs. 0.95)


## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
logistic regression model (fit with oversampled data) seems to perform best overall, therefore we recommend model of  logistic regression model (fit with oversampled data)
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
*ANSWER: Yes, it seems so, model output would depend on what we are trying to solve, for example whether its more important for 1 or 0 to be correctly predicted

If you do not recommend any of the models, please justify your reasoning.

