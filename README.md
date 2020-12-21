# Credit_Risk_Analysis

## Overview of Analysis
Analysing credit risk renders unbalanced classification problems, as suitable loans tend to outnumber uncertain loans. In order to address this in my analysis I must employ a variety of techniques to train and evaluate models with unbalanced classes. 

#Purpose
Machine learning is a useful yet complex skill, I have been tasked with applying these skills to assess the credit card credit dataset from LendingClub. I have employed numerous techniques from the imbalanced-learn and scikit-learn libraries to evaluate the models using resampling. The primary algorithms I have chosen to use are RandomOverSampler and SMOTE, to under sample the data using the ClusterCentroids algorithm. As well as a combinational approach of under and oversampling employing SMOTEEN. Lastly, I compared the BalancedRandomForestClassifier, and EasyEnsembleClassifier to determine which is more proficient in reducing bias to predict credit risk. 

## Results
•	The **Naïve Random Oversampling model** rendered a balanced accuracy score of 67.4%, a precision score of 99%, and a recall score of 61%.
•	The **SMOTE Oversampling model** showed a balanced accuracy score of 66.2%, a precision score of 99%, and a recall score of 61%.
•	The **ClusterCentroids Undersampling model** signified a balanced accuracy score of 54.7%, a precision score of 99%, and a recall score of 41%. 
•	The **SMOTEEN combination (Over and Undersampling) model** indicated a balanced accuracy score of 64.5%, a precision score of 99%, and a recall score of 57%. 
•	The **BalancedRandomForest Classifier** illustrated a balanced accuracy score of 72.9%, a precision score of 99%, and a recall score of 87%.
•	Lastly, the **Easy Ensemble AdaBoost Classifier** showed a balanced accuracy score of 68.8%, a precision score of 100%, and a recall score of 100%.

## Summary 
As the statistical data provided above illustrates the Naïve Random Oversampling provided the most accurate results among the four sampling algorithms in the credit risk resampling. Additionally, the Easy Ensemble AdaBoost Classifier maintained the best-balanced accuracy, precision, and recall score in the credit risk ensemble. 

Based on our observations, I would recommend using the BalancedRandomForest Classifier, as Logistic Regression models are not the most efficient models in predicting high credit risk for loans. Although its recall score is lesser than the alternative classifier it does indicate a higher balanced accuracy score which is important to determine the precision of the results. 
