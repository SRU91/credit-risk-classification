# credit-risk-classification
 Module 20 Challenge




## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.
    The purpose of this analysis was to train a model to predict a healthy versus high-risk loan.
    
* Explain what financial information the data was on, and what you needed to predict.
    The financial data provided included: 
        loan size
        interest rate
        borrower income
        debt to income
        number of accounts
        derogatory marks
        total debt
        loan status
    The goal was to predict whether a loan fell into a healthy or high-risk loan
    category.


## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.
        - Accuracy: The model was 99% accurate
        - Precision: Healthy loans were 100% precise while high-risk loans were 
          only 85% precise
        - Recall scores: Healthy loans had a 99% recall score while high-risk loans
          only received a 91% score


* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
        - Accuracy: The model was 99% accurate
        - Precision: Healthy loans were 100% precise while high-risk loans were 
          only 84% precise
        - Recall: Healthy loans had a 99% recall score while high-risk loans
          increased to a 99% score

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:
* Which one seems to perform best? How do you know it performs best?
    While both models were 99% accurate, model 2 seemed to have better scores
    overall
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? )
    Predicting both healthy and high-risk loans provides a more accurate overall picture. In our case, we could have only predicted healthy loans and *assumed* all the rest of the loans were high-risk but by doing this, we would also assume precision of 100% for high-risk loans but as we can see from the models, this wasn't necessarily correct.
If you do not recommend any of the models, please justify your reasoning.