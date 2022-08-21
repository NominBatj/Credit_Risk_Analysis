# Credit Risk Analysis
## Overview 

In this project we are building and evaluating machine learning models to predict customer credit risk.
The machine learning algorithms used were:
- RandomOverSampler
- SMOTE
- ClusterCentroids
- SMOTEENN Algorithms
- BalancedRandomForestClassifier
- EasyEnsembleClassifier

## Results

Followings are the results for the six machine learning models, including their respective balanced accuracy, precision, and recall scores

### Naive Random Oversampling

![naive](https://user-images.githubusercontent.com/66500222/185774403-9c8f9b81-a010-492b-9881-1b0920da3485.png)

- Balanced Accuracy: 0.6515938052705158
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.62/0.68

### SMOTE Oversampling

- Balanced Accuracy: 
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .62/.64

### Undersampling

- Balanced Accuracy: 
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .63/.40


### Combination Under-Over Sampling

- Balanced Accuracy:
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .70/.57

### Balanced Random Forest Classifier

- Balanced Accuracy: 
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .67/.91

### Easy Ensemble AdaBoost Classifier

- Balanced Accuracy:
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = .91/.94

## Summary

All models used to conduct credit risk analysis show poor accuracy in determining whether credit risk is high. The Ensemble models have made many more improvements, especially with regard to the sensitivity of high-risk loans. The EasyEnsembleClassifier model shows % recall, so it detects almost all high-risk loans. On the other hand, with low accuracy, many low-risk loans are still falsely identified as high-risk loans, which will negatively impact a bank's lending strategy and impact its earnings by missing out on these business opportunities. For these reasons, I would not recommend that a bank use any of these models to predict credit risk as it will put lenders at too much risk as they won't be able to accurately predict who the high risk customers/debtors will be.
