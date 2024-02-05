# Module 12 Report Template

## Overview of the Analysis

Description of the analysis completed for the machine learning models used in this Challenge include:

* This analysis was performed to assess the effectiveness of Supervised Machine Learning models on a financial dataset by using various techniques to train and evaluate loan risk.
* The financial information within the data contained lending information, and with the information presented a prediction could be made to assess the risk of loan default.
* Predictions were used to find likelihood of high-risk loans by value_counts of `1` from loan status column.
* Used the Test_Train_Split to split the data into Training data to train the machine to learn about the data and be able to test other data to predict outcomes. 
* LogisticRegression was used to estimate the probability of high-risk loans, based on lending dataset of independent variables.
* RandomOverSampler module was utilized for Machine Learning Model 2 to increase the amount of minority class of items to create balance between the classes of data.

## Results

* Machine Learning Model 1:
  * Accuracy: 99%
  * Precision: `0` = 100%, `1` = 85%
  * Recall score: `0` = 99%, `1` = 91%
  * F1-Scores: `0` =  100%, `1` = 88%
  * Balanced Accuracy: 95.20%



* Machine Learning Model 2:
  * Accuracy: 99%
  * Precision: `0` = 100%, `1` = 84%
  * Recall score: `0` = 99%, `1` = 99%
  * F1-Scores: `0` = 100%, `1` = 91%
  * Balanced Accuracy: 99.37%

## Summary

Recommendation of the Machine Learning Model 2 for the listed reasons below:
* The F1 score is higher for the item we are trying to predict. This is good as this is the percentage of positive predictions that are correct.
* Balanced Accuracy score increased from 95.20% on the the first model to 99.37%.

Performance of the Machine Learning Model 2 will not work as well on datasets that are balanced because the RandomOverSampler module was uses to balance the lesser of the classifications.
