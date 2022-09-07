# Credit_Risk_Analysis
Solve Credit Card Risk with Machine Learning

## Overview of loan preiction risk analysis
Good loans are easily outnumbered by risky loans due to credit risk fundamental unbalanced classification problem. In this analysis, different techniques were deployed to train and evaluate models with unbalanced classes with credit card dataset from LendingClub, a peer-to-peer lending services company.

## Steps
1. Data is sampled using RandomOverSampler and SMOTE algorithms and undersampled data with ClusterCentroids algorithm.
2. Two new machine learning that reduces bias compared, BalancedRandomForestClassifier and EasyEnsembleClassifier to predict credit risk.

## Results

### RandomOverSampler
For this model (RandomOverSampler)

•	The balanced accuracy score is 66%.

•	In the high-risk for this model, the precision score is 1%,  recall score is 70% and F1 score is 2%.

•	In the low risk for this model, the precision score is 100% and recall score is 62%. Most of the100% predicted low-risk are true positive, while 62% low-risk are correct with a F1 score of 76%.


![image](https://user-images.githubusercontent.com/105121697/188295493-50395539-7569-47e4-874d-32e1f01d6d53.png)


### SMOTE
For this model (SMOTE)

•	The balanced accuracy score is 66%.

•	In the high-risk for this model, the precision score is 1%, recall score is 63% and F1 score is 2%.

•	In the low risk for this model, the precision score is 100%,  recall score is 69% and F1 score is 82%.


![image](https://user-images.githubusercontent.com/105121697/188294970-126b65cf-d3ac-4daf-87bb-2833641b62d0.png)


### SMOTEENN
For this model (SMOTEENN) 

•	The balanced accuracy score is 56%.

•	In the high-risk for this model, the precision score is 1% and recall score is 72% with F1 score of 2%.

•	In the low risk for this model, the precision score is 100% and recall score is 57% and F1 score is 72%.


![image](https://user-images.githubusercontent.com/105121697/188295373-f397674d-1a2e-4371-9df3-7bd7ef22d825.png)


### ClusterCentroids
For this model (ClusterCentroids) 

•	The balanced accuracy score is 66%.

•	In the high-risk for this model, the precision score is 1% and recall score is 55% with F1 score of 1%.

•	In the low risk for this model, the precision score is 100% and recall score is 57% and F1 score is 73%.


![image](https://user-images.githubusercontent.com/105121697/188295292-bdc489d3-0ac9-4878-bf38-c6685d75bcce.png)


### BalancedRandomForestClassifier
For this model (BalancedRandomForestClassifier) 

•	The balanced accuracy score is 91.2%.

•	In the high-risk for this model, the precision score is 96% and recall score is 87% with F1 score of 91%.

•	In the low risk for this model, the precision score is 87% and recall score is 96% and F1 score is 91%.


![image](https://user-images.githubusercontent.com/105121697/188295086-28898070-1b65-46c9-aba5-bf5f1734165c.png)


### EasyEnsembleClassifier
For this model (EasyEnsembleClassifier)

•	The balanced accuracy score is 91.2%.

•	In the high-risk for this model, the precision score is 96% and recall score is 87% with F1 score of 91%.

•	In the low risk for this model, the precision score is 87% and recall score is 96% and F1 score is 91%.


![image](https://user-images.githubusercontent.com/105121697/188295130-6980bc93-0e41-4835-a552-bf2178d58bdd.png)


### Summary of results

In summary, the precision scores for all the models are alright. I will recommend the use of EasyEnsambleClassifier and BalancedRandomForestClassifiers to predict credit risk, both performed well, provided high scores on risky loans on the analysis, predicting credit risk.


