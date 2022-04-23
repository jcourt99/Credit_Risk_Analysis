# Credit_Risk_Analysis
Module 17 - Supervised Machine Learning and Credit Risk

## Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the 'RandomOverSampler' and 'SMOTE' algorithms, and undersampled the data using the 'ClusterCentroids' algorithm. Then, I used a combinatorial approach of over- and undersampling using the 'SMOTEENN' algorithm. Next, I compared two new machine learning models that reduce bias, 'BalancedRandomForestClassifier' and 'EasyEnsembleClassifier', to predict credit risk. 

## Results

Comparison of all six machine learning models used in this analysis, specifically, the balanced accuracy scores, precision scores and recall scores:

* RandomOverSampler
    * Balanced Accuracy Score = 64.1%
    * Precision Score = high risk = 1%, low risk = 100%
    * Recall Score = high risk = 60%, low risk = 68%

* SMOTE
    * Balanced Accuracy Score = 63.7%
    * Precision Score = high risk = 1%, low risk = 100%
    * Recall Score = high risk = 60%, low risk = 68%

* ClusterCentroids
    * Balanced Accuracy Score = 52.9%
    * Precision Score = high risk = 1%, low risk = 100%
    * Recall Score = high risk = 61%, low risk = 45%

* SMOTEENN
    * Balanced Accuracy Score = 
    * Precision Score = 
    * Recall Score = 

* BalancedRandomForestClassifier
    * Balanced Accuracy Score = 
    * Precision Score = 
    * Recall Score = 

* EasyEnsembleClassifier
    * Balanced Accuracy Score = 
    * Precision Score = 
    * Recall Score = 


## Summary
* Summary of results
* Recommendation on which model to use, or there is no recommendation with a justification


