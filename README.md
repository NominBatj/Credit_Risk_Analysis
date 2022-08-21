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
- Recall: High/Low risk = 0.68/0.81

### SMOTE Oversampling

![smote](https://user-images.githubusercontent.com/66500222/185774460-0bf50642-d5c8-4ada-b30c-8567e5df856b.png)

- Balanced Accuracy: 0.6241876870888075
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.66/0.80

### Undersampling

![undersampling](https://user-images.githubusercontent.com/66500222/185774496-e1d3420f-c311-4402-854e-9b70ba643c79.png)

- Balanced Accuracy: 0.5159904274991842
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.60/0.60


### Combination Under-Over Sampling

![combination](https://user-images.githubusercontent.com/66500222/185774554-d6cdc8c4-6dfb-42b4-a9f2-863c14bbede0.png)

- Balanced Accuracy: 0.6218026195454673
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.71/0.69

### Balanced Random Forest Classifier

![balanced](https://user-images.githubusercontent.com/66500222/185814066-db93a740-6ba4-4131-bf7a-48cc9e708c02.png)


- Balanced Accuracy: 0.7877672625306695
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.78/0.62

### Easy Ensemble AdaBoost Classifier


- Balanced Accuracy:
- Precision: The precision is low for High-risk loans and is high for Low-risk loans.
- Recall: High/Low risk = 0.91/0.62

## Summary

All models used to conduct credit risk analysis show poor accuracy in determining whether credit risk is high. The Ensemble models have made many more improvements, especially with regard to the sensitivity of high-risk loans. The EasyEnsembleClassifier model shows % recall, so it detects almost all high-risk loans. On the other hand, with low accuracy, many low-risk loans are still falsely identified as high-risk loans, which will negatively impact a bank's lending strategy and impact its earnings by missing out on these business opportunities. For these reasons, I would not recommend that a bank use any of these models to predict credit risk as it will put lenders at too much risk as they won't be able to accurately predict who the high risk customers/debtors will be.
