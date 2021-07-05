# Credit Risk Analysis

## Overview
Our task was to apply machine learning to solve for credit card risk. We are asked to use multiple models to evaluate, such as RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results
- ### Naive Random Sampling
	- Accuracy Score - 64%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.69
	- High-Risk F1 - 0.02
	
	
- ### SMOTE Oversampling
	- Accuracy Score - 66%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.63
	- High-Risk F1 - 0.02
	
	
- ### Undersampling
	- Accuracy Score - 54%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.69
	- High-Risk F1 - 0.01
	
	
- ### Combination
	- Accuracy Score - 64%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.72
	- High-Risk F1 - 0.02
	
	
- ### Balanced Random Forest Classifier
	- Accuracy Score - 79%
	- High-Risk Prescision - 0.03
	- High-Risk Recall - 0.70
	- High-Risk F1 - 0.06
	
	
- ### Easy Ensemble AdaBoost Classifier
	- Accuracy Score - 93%
	- High-Risk Prescision - 0.09
	- High-Risk Recall - 0.92
	- High-Risk F1 - 0.16
	
	
	
## Summary
Naive Random Sampling, SMOTE Oversampling, Undersampling, and Combination all did well predicting low-risk credit but none were very good at predicting high-risk credit and their accuracy scores were below 70%. The balanced Random Forest Classifier did better with an accuracy score of 79% and sensitivity (recall) of 0.7. The Easy Ensemble AdaBoost Classifier did the best job with an accuracy score of 93% and a sensitivity (recall) rate of 0.92. I would recommend using this method going forward.