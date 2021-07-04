# Credit_Risk_Analysis


## Overview: 
The purpose of this analysis is to evaluate the performance of various machine learning models in predicting credit risk. 

## Results:
### RandomOverSampler
![RandomOverSampler](https://github.com/marhanlang/Credit_Risk_Analysis/blob/main/Images/naiveRandomOversampling.png)
- balanced accuracy score: 0.649
- precision: 0.99
- recall score: 0.57
### SMOTE
![SMOTE](https://github.com/marhanlang/Credit_Risk_Analysis/blob/main/Images/SMOTE_Oversampling.png)
- balanced accuracy score: 0.658
- precision: 0.99
- recall score: 0.68
### ClusterCentroids
![ClusterCentroids](https://github.com/marhanlang/Credit_Risk_Analysis/blob/main/Images/clusterCentroids.png)
- balanced accuracy score: 0.544
- precision: 0.99
- recall score: 0.40
### SMOTEENN
![SMOTEENN](https://github.com/marhanlang/Credit_Risk_Analysis/blob/main/Images/SMOTEENN.png)
- balanced accuracy score: 0.662
- precision: 0.99
- recall score: 0.54
### BalancedRandomForestClassifier
![BalancedRandomForestClassifier](https://github.com/marhanlang/Credit_Risk_Analysis/blob/main/Images/BalancedRandomForestClassifier.png)
- balanced accuracy score: 0.789
- precision: 0.99
- recall score: 0.87
### EasyEnsembleClassifier
![EasyEnsembleClassifier](https://github.com/marhanlang/Credit_Risk_Analysis/blob/main/Images/EasyEnsembleClassifier.png)
- balanced accuracy score: 0.932
- precision: 0.99
- recall score: 0.94

## Summary: 
The ideal model for analyzing credit risk is a model that catches all high risk clients, even if it means a certain number of false positives in order to protect lenders. This indicates that high precision is less important than sensitivity.  EasyEnsemble has the highest scores but might indicate overfitting. The SMOTEENN model appears to be the best model in terms of accuracy and high-risk sensitivity for this purpose.
