# credit-risk-classification
# Module 20 Report Template

## Overview of the Analysis

In this section, describe the analysis you completed for the machine learning models used in this Challenge. This might include:

* Explain the purpose of the analysis.

The purpose to to draw conclusions about the data and by running the models we can see how the data preforms and which is most accurate for any questions about the data. this helps with decision making for approvals and compliance for the lenders.

* Explain what financial information the data was on, and what you needed to predict.

The info was about loans and the risks based on the customer info like debt to income ratio, size of loan, total debt. using this we predicted if the data from the model could predict healthly and high risk loans

* Provide basic information about the variables you were trying to predict (e.g., `value_counts`).
predicting loan status we see there are 75036 healthy loans and 2500 high risk loans.

* Describe the stages of the machine learning process you went through as part of this analysis.
-data collection- creating the dataframe
-preprocessing data- seperating x &y
-reviewing variable
-splitting and testing the data
-creating the model- training the model
-making predictions
-evaluate proformance
-deployment

* Briefly touch on any methods you used (e.g., `LogisticRegression`, or any other algorithms).
i used the logistic regression, confusion matrix, and classification reports

## Results

Using bulleted lists, describe the accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
    * Description of Model 1 Accuracy, Precision, and Recall scores.
    -class 0 precision was spot on at 1 recall was spot on as 1 f1score was spot on as 1 
    class 1 precision was 87% recall 89% f1 88% 
    -the creating an accuracy of 99%
    

## Summary

Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. For example:

* Which one seems to perform best? How do you know it performs best? i would recommend this model for the company because it presented accurate results and no false info, the would be good because it will cause the bank a lot of risk and loss if the results were not as accurate as the results we got. 
* Does performance depend on the problem we are trying to solve? (For example, is it more important to predict the `1`'s, or predict the `0`'s? ) i think that even tho high risk did not show 100% i think that would be normal as there is risk and loss in loans, but the info we received for high risk is still pretty high and would require human discrecion 

If you do not recommend any of the models, please justify your reasoning.
