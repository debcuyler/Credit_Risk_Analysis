# Credit Risk Analysis

## Overview
Our task was to apply machine learning to solve for credit card risk. We are asked to use multiple models to evaluate, such as RandomOverSampler, SMOTE, ClusterCentroids, SMOTEENN, BalancedRandomForestClassifier and EasyEnsembleClassifier

## Results
- ### Naive Random Sampling
	- Accuracy Score - 64%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.69
	- High-Risk F1 - 0.02
	
![Naive Random Oversampling](https://user-images.githubusercontent.com/80215894/124478722-7ba01b80-dd73-11eb-9aee-940625ba137b.png)
	
- ### SMOTE Oversampling
	- Accuracy Score - 66%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.63
	- High-Risk F1 - 0.02

![SMOTE Oversampling](https://user-images.githubusercontent.com/80215894/124478847-9c687100-dd73-11eb-96bf-286a6ab80ac7.png)
	
- ### Undersampling
	- Accuracy Score - 54%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.69
	- High-Risk F1 - 0.01

![Undersampling](https://user-images.githubusercontent.com/80215894/124478881-a7bb9c80-dd73-11eb-981e-755f9c82f2a9.png)
	
- ### Combination
	- Accuracy Score - 64%
	- High-Risk Prescision - 0.01
	- High-Risk Recall - 0.72
	- High-Risk F1 - 0.02

![Combination Sampling using SMOTEENN](https://user-images.githubusercontent.com/80215894/124478922-b0ac6e00-dd73-11eb-9b5d-b57df1ab6842.png)
	
- ### Balanced Random Forest Classifier
	- Accuracy Score - 79%
	- High-Risk Prescision - 0.03
	- High-Risk Recall - 0.70
	- High-Risk F1 - 0.06

![Balanced Random Forest Classifier](https://user-images.githubusercontent.com/80215894/124478954-b904a900-dd73-11eb-88c1-a7b0324cd678.png)
	
- ### Easy Ensemble AdaBoost Classifier
	- Accuracy Score - 93%
	- High-Risk Prescision - 0.09
	- High-Risk Recall - 0.92
	- High-Risk F1 - 0.16

![Easy Ensemble AdaBoost Classifier](https://user-images.githubusercontent.com/80215894/124478971-c0c44d80-dd73-11eb-9837-3a0cbd840467.png)
	
## Summary
Naive Random Sampling, SMOTE Oversampling, Undersampling, and Combination all did well predicting low-risk credit but none were very good at predicting high-risk credit and their accuracy scores were below 70%. The balanced Random Forest Classifier did better with an accuracy score of 79% and sensitivity (recall) of 0.7. The Easy Ensemble AdaBoost Classifier did the best job with an accuracy score of 93% and a sensitivity (recall) rate of 0.92. I would recommend using this method going forward.
