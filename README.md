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
* When comparing all 6 algorithms for predicting high and low risk loan applicants, the EasyEnsembleClassifier produced the highest accuracy score of 92%. The undersampling algorithm, ClusterCentroids, produced the lowest accuracy score at 52.9%. All of the models had low precision scores for high risk applicants which is indicative of a large number of false positives. However, it is better in this case to have more false positives than false negatives when looking at high risk credit applicants.

* I would recommend using the EasyEnsembleClassifier to predict the high risk candidates. The accuracy score of 92% is much higher than the other 5 models. It also had a better precision score of 7% and a much higher recall which indicates fewer false negatives. 


