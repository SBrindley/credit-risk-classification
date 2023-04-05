
# Module 20 - Credit Risk Classification

## Overview of the Analysis

* The purpose of this analysis was to use various techniques to train and evaluate a model based on loan risk. This will be using a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers.

* I used loan data from a csv that contained data such as interest rates, borrower income and total debt for our model.

* Steps I went through to get the results:

Split the Data into Training and Testing Sets
Fit a logistic regression model by using the training data (X_train and y_train)
Predict a Logistic Regression Model with Resampled Training Data

## Results

* Machine Learning Model 1:
  * Description of Model 1 Accuracy, Precision, and Recall scores.

              precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.85      0.91      0.88       619

    accuracy                           0.99     19384
   macro avg       0.92      0.95      0.94     19384
weighted avg       0.99      0.99      0.99     19384

* Machine Learning Model 2:
  * Description of Model 2 Accuracy, Precision, and Recall scores.
  
                precision    recall  f1-score   support

           0       1.00      0.99      1.00     18765
           1       0.84      0.99      0.91       619

    accuracy                           0.99     19384
   macro avg       0.92      0.99      0.95     19384
weighted avg       0.99      0.99      0.99     19384


## Summary

* I think the second logistic regression model with the resampled data performed better than first model. The scores for the second model were better with the accuracy score being higher, and the recall score improving from 0.91 to 0.99. The first models f1 score indicated that there was 12% of higher risk loans not being captured and the second was less.

* My recommendation would be to use the logistic regression model with the resampled training data for the company to progress with.
