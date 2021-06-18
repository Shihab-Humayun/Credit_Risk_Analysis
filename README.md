# Credit_Risk_Analysis

## Overview
The purpose of this analysis is to oversample the data using the RandomOverSampler and SMOTE algorithms and undersample the data using the ClusterCentroids algorithm. Then I will be using a combinatorial approach of over- and undersampling using the SMOTEENN algorithm. I will be using the credit card credit dataset from LendingClub, a peer-to-peer lending services company. I will compare the two new machine learning models that reduce bias, BalancedRandomForestClassifier and EasyEnsembleClassifier, to predict credit risk and make a conclusion whether to use these models to predict credit risk.

## Results
### Naive Random Oversampling
![image](https://user-images.githubusercontent.com/49353083/122617770-ddb20e80-d05a-11eb-8a92-085423f860f0.png)

- Balanced Accuracy Scores: 0.6663237827524566
- High Risk Precision: 0.01
- Low Risk Precision: 1.00
- High Risk Recall Scores: 0.70
- Low Risk Recall Scores: 0.63

### SMOTE Oversampling
![image](https://user-images.githubusercontent.com/49353083/122618368-20c0b180-d05c-11eb-8415-bdb155bdb518.png)

- Balanced Accuracy Scores: 0.6623064259185507
- High Risk Precision: 0.01
- Low Risk Precision: 1.00
- High Risk Recall Scores: 0.63
- Low Risk Recall Scores: 0.69

### Undersampling
![image](https://user-images.githubusercontent.com/49353083/122618543-739a6900-d05c-11eb-821c-efa3331b9e52.png)

- Balanced Accuracy Scores: 0.5442077123989293
- High Risk Precision: 0.01
- Low Risk Precision: 1.00
- High Risk Recall Scores: 0.69
- Low Risk Recall Scores: 0.40

### Combination (Over and Under) Sampling
![image](https://user-images.githubusercontent.com/49353083/122618609-9593eb80-d05c-11eb-89d3-1f1c3bdc0cb4.png)

- Balanced Accuracy Scores: 0.6447701423556762 
- High Risk Precision: 0.01
- Low Risk Precision: 1.00
- High Risk Recall Scores: 0.72
- Low Risk Recall Scores: 0.57

### Balanced Random Forest Classifier
![image](https://user-images.githubusercontent.com/49353083/122618696-c2e09980-d05c-11eb-9f45-5bdd68b75393.png)

- Balanced Accuracy Scores: 0.7885466545953005
- High Risk Precision: 0.03
- Low Risk Precision: 1.00
- High Risk Recall Scores: 0.70
- Low Risk Recall Scores: 0.87

### Easy Ensemble AdaBoost Classifier
![image](https://user-images.githubusercontent.com/49353083/122618743-e3a8ef00-d05c-11eb-86fb-4b9302daa1e6.png)

- Balanced Accuracy Scores: 0.9316600714093861
- High Risk Precision: 0.09
- Low Risk Precision: 1.00
- High Risk Recall Scores: 0.92
- Low Risk Recall Scores: 0.94

## Summary
Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.
There is a summary of the results
There is a recommendation on which model to use, or there is no recommendation with a justification
