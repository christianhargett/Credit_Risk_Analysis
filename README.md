# Credit_Risk_Analysis

## Overview

In this project we are working with LendingClub, a peer-to-peer lending services company. LendingClub has tasked us with building a Machine Learning model that predicts credit risk when given a certain loan dataset. We have utilized libraries from SciKit Learn in order to assess different Machine Learning algorithms and determine the best model for the client. 

## Results

We began our assessment by using two different oversampling methods: Naive Random Oversampling and SMOTE oversampling.

### Naive Random Oversampling

![](https://github.com/christianhargett/Credit_Risk_Analysis/blob/main/NaiveRandomOversamplingResults.png)

From this snippet of code we can determine the model has the below performance metrics:
- Balanced Accuracy: 65%
- Precision: 99%
- Sensitivity: 60%

### SMOTE Oversampling

![](https://github.com/christianhargett/Credit_Risk_Analysis/blob/main/SMOTEOversamplingResults.png)

- Balanced Accuracy: 66%
- Precision: 99%
- Sensitivity: 42%

We then utlized a Machine Learning algorithm using an undersampling method: Cluster Centroids

### Cluster Centroids Undersampling

![](https://github.com/christianhargett/Credit_Risk_Analysis/blob/main/ClusterCentroidsResults.png)

- Balanced Accuracy: 55%
- Precision: 99%
- Sensitivity: 41%

We then used a cominbation of oversampling and undersampling using SMOTEEN

### SMOTEEN (Oversampling/Undersampling)

![](https://github.com/christianhargett/Credit_Risk_Analysis/blob/main/SMOTEENResults.png)

- Balanced Accuracy: 66%
- Precision: 99%
- Sensitivity: 58%

Additionally, we used two different ensemble classifiers to try and predict credit risk: Balanced Random Forest Classifier and Easy Ensemble AdaBoost Classifier

### Balanced Random Forest

![](https://github.com/christianhargett/Credit_Risk_Analysis/blob/main/RandomForestResults.png)

- Balanced Accuracy: 79%
- Precision: 99%
- Sensitivity: 87%

### Easy Ensemble AdaBoost Classifier

![](https://github.com/christianhargett/Credit_Risk_Analysis/blob/main/AdaBoostClassifierResults.png)

- Balanced Accuracy: 93%
- Precision: 99%
- Sensitivity: 94%
