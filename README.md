# Credit_Risk_Analysis

## Overview
Machine learning can make accurate, quick, and reliable selections for loan applicants. We will evaluate multiple machine learning models to decide which one will give us the best results for predicting credit risk.

## Results: balanced accuracy scores and the precision and recall scores of all six machine learning models.

### Naive Random Oversampling
![naive_random_oversampling](https://user-images.githubusercontent.com/98570777/188262694-836df0a7-20a7-4951-8993-cd8d9b7ab27f.jpg)
Balanced Accuracy Score: 62.5%

### SMOTE Oversampling
![smote_oversampling](https://user-images.githubusercontent.com/98570777/188262821-0607292d-df2f-4ace-a5d9-f75a73c48887.jpg)
Balanced Accuracy Score: 65.1%

### Undersampling: ClusterCentroids resampler
![clustercentroids_undersampling](https://user-images.githubusercontent.com/98570777/188262846-2b012384-600e-4e9f-a62f-ab417e732be2.jpg)
Balanced Accuracy Score: 51.6%

### Combination Sampling: SMOTEENN 
![combo_sampling](https://user-images.githubusercontent.com/98570777/188262894-172f1ee4-898e-419b-be82-255f2c63483b.jpg)
Balanced Accuracy Score: 64.0%

### Balanced Random Forest Classifier
![brfc](https://user-images.githubusercontent.com/98570777/188262934-f4e11da7-ef05-46b5-81e1-1be070a36b70.jpg)
Balanced Accuracy Score: 67.2%

### Easy Ensemble AdaBoost Classifier
![adaboost](https://user-images.githubusercontent.com/98570777/188262946-2d9da15c-1b3c-409e-8415-25abc874e297.jpg)
Balanced Accuracy Score: 92.5%

## Summary: Summarize the results of the machine learning models, and include a recommendation on the model to use, if any. If you do not recommend any of the models, justify your reasoning.

In high stakes data like credit risk, a high recall and precision scores are important. A high recall allows us to measure the ability for the model to find positive samples. A high precision tells how reliable the model is at classifing positive samples.

The easy ensemble AdaBoost classifier was the best at predicting low risk loan applications. This can be determined by the high precision, recall and accuracy scores. The precision for the high risk loan applicants is very low - 7%. This can be made up for by the high recall. If the high risk applicants can at least be found, it can be flagged and a decision can be made from that point. By either another algorithm or a person working at the company. </br> Using a couple different models can be beneficial to a problem such as evaluating credit risk so that no bad applicants slip through. 
