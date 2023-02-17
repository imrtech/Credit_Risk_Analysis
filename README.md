# Credit_Risk_Analysis

## Overview

The purpose of this project is to analysis all the factors in our loan dataset to help predict whether someone is a low or high credit risk.

The following analysis was performed:

- Oversampling of the data using RandomOverSampler and SMOTE algorithms.
- Undersampling the data using the ClusterCentroids algorithm.
- Combined the approach of oversampling and undersampling using the SMOTEENN algorithm.
- Two models were compared to reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier.

We used the following resources:
Dataset: https://raw.githubusercontent.com/imrtech/Credit_Risk_Analysis/main/LoanStats_2019Q1.csv

Applications:
- Python
- Jupyter Notebook


## Results

### Random Oversampling results:
![accuracy random oversampling classification report](resources/images/accuracyrandomoversampling.png)

![random oversampling classification report](resources/images/randomoversampling.png)

- The balanced accuracy score is 62%.
- The high_risk precision is about 1% with 67% sensitivity which makes a F1 score of 2%.
- The precision is almost 100% with a sensitivity of 57%.



![accuracy smote oversampling classification report](resources/images/accuracysmoteoversampling.png)

![smote oversampling classification report](resources/images/smoteoversampling.png)

![undersampling classification report](resources/images/undersamplingsampling.png)

![combination over and under sampling classification report](resources/images/combinationoverundersampling.png)

### Summary




