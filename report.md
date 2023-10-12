# Module 20 Report

## Overview of the Analysis

* The purpose of this analysis was to input loans and predict whether it would be a healthy (1) or high risk loan (0). 

* The data utilized included the loan size, the interest rate, borroweer income, debt income, the number of accounts, if there are derogatory marks, the total debt, and ultimately the loan status. Given the data we were provided, we were able to take the value counts of the which loans were healthy or high risk. From this we were able to utilize machine learning to build predictive models. 

* In order to generate the predictive models, we preprocessed the data by splitting it into training and test data. We also pulled a balanced accuracy score to gain more context about the strength of the model when pulling in accuracy and precision scores. 

* We used logistic regression because it allows us to predict the probability of a categorical outcome of the loan, allowing us to easily classify them. 

## Results

Using bulleted lists, describe the balanced accuracy scores and the precision and recall scores of all machine learning models.

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

The balanced score of the machine learning model was 0.94. 

               precision    recall  f1-score   support

  healthy loans       1.00      1.00      1.00     18759
high-risk loans       0.87      0.89      0.88       625

       accuracy                           0.99     19384
      macro avg       0.94      0.94      0.94     19384
   weighted avg       0.99      0.99      0.99     19384


* Machine Learning Model 2:

  * The balanced score of the machine learning model was 0.94. 

                 precision    recall  f1-score   support

  healthy loans       1.00      1.00      1.00     18759
high-risk loans       0.87      0.89      0.88       625

       accuracy                           0.99     19384
      macro avg       0.94      0.94      0.94     19384
   weighted avg       0.99      0.99      0.99     19384

## Summary

The model that peforms the best was model one given that it had slighlty higher prediction and accuracy scores. 

It is more important to predict the '0''s, otherwise known as the highrisk loans. This is becuase if we were to be risk avoidant we would most likely want to be notified which loans not to accept rather all of the ther loans that have been green-lit. 

I would not recommend using unsupervised learning for this data set becuase we are not trying to analyze algorithms or create clusters, rather we are trying to classify the loans. 
