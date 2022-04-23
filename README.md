# Credit_Risk_Analysis
Module 17 - Supervised Machine Learning and Credit Risk

## Overview

Using the credit card credit dataset from LendingClub, a peer-to-peer lending services company, I oversampled the data using the 'RandomOverSampler' and 'SMOTE' algorithms, and undersampled the data using the 'ClusterCentroids' algorithm. Then, I used a combinatorial approach of over- and undersampling using the 'SMOTEENN' algorithm. Next, I compared two new machine learning models that reduce bias, 'BalancedRandomForestClassifier' and 'EasyEnsembleClassifier', to predict credit risk. 

## Results

Comparison of all six machine learning models used in this analysis, specifically, the balanced accuracy scores, precision scores and recall scores:

* RandomOverSampler (Oversampling)
    * Balanced Accuracy Score: 64.1%
    * Precision Score: high risk = 1%, low risk = 100%
    * Recall Score: high risk = 60%, low risk = 68%

    ![Image of RandomOverSampler](https://github.com/jcourt99/Credit_Risk_Analysis/blob/main/Images/RandomOverSampler_classification.jpg)


* SMOTE (Oversampling)
    * Balanced Accuracy Score: 63.7%
    * Precision Score: high risk = 1%, low risk = 100%
    * Recall Score: high risk = 60%, low risk = 68%

    ![Image of SMOTE](https://github.com/jcourt99/Credit_Risk_Analysis/blob/main/Images/SMOTE_classification.jpg)


* Cluster Centroids (Undersampling)
    * Balanced Accuracy Score: 52.9%
    * Precision Score: high risk = 1%, low risk = 100%
    * Recall Score: high risk = 61%, low risk = 45%

    ![Image of Cluster Centroids](https://github.com/jcourt99/Credit_Risk_Analysis/blob/main/Images/Centroid_Cluster_classification.jpg)
    

* SMOTEENN (Combination sampling)
    * Balanced Accuracy Score: 63.9%
    * Precision Score: high risk = 1%, low risk = 100%
    * Recall Score: high risk = 70%, low risk = 58%

    ![Image of SMOTEENN](https://github.com/jcourt99/Credit_Risk_Analysis/blob/main/Images/SMOTEENN_classification.jpg)
    

* BalancedRandomForestClassifier (Ensemble Classifier)
    * Balanced Accuracy Score: 78.8%
    * Precision Score: high risk = 4%, low risk = 100%
    * Recall Score: high risk = 67%, low risk = 91%

    ![Image of Balanced Random Forest](https://github.com/jcourt99/Credit_Risk_Analysis/blob/main/Images/Balanced_Random_Forest_classification.jpg)


* EasyEnsembleClassifier (Ensemble Classifier)
    * Balanced Accuracy Score: 92.5%
    * Precision Score: high risk = 7%, low risk = 100%
    * Recall Score: high risk = 91%, low risk = 94%

    ![Image of Balanced Random Forest](https://github.com/jcourt99/Credit_Risk_Analysis/blob/main/Images/EasyEnsemble_classification.jpg)


## Summary
* Summary of results
* Recommendation on which model to use, or there is no recommendation with a justification


