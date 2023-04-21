# Credit_Risk_Analysis

## Overview
This project uses the credit card credit dataset from LendingClub, a peer-to-peer lending services company to analyse credit risk for LendingClub. Using oversampling and undersampling algorithms, we resampled the dataset, viewed the count of the target classes, trained a logistic regression classifier, calculated the balanced accuracy score, and generated a confusion matrix.
Specifically, we:
 - oversampled the data using the RandomOverSampler and SMOTE algorithms.
 - Undersampled the data using the ClusterCentroids algorithm.
 - Used a combinatorial approach of oversampling and undersampling with the SMOTEENN algorithm.
 - Compared two machine learning models that reduce bias: BalancedRandomForestClassifier and EasyEnsembleClassifier.
 
## Results
The results of each analysis are listed below:

1. Naive Random Oversampling
![Screenshot NaiveRandomOversampling.](Credit_Risk_Analysis/Images/Naive_Random_Oversampling.png)

2. SMOTE Oversampling
![Screenshot SMOTE.](Credit_Risk_Analysis/Images/SMOTE_Oversampling.png)

3. Undersampling
![Screenshot under.](Credit_Risk_Analysis/Images/Undersampling.png)

4. Combination Sampling
![Screenshot Combo.](Credit_Risk_Analysis/Images/Combination_Sampling.png)

5. Balanced Random Forest Classifier
![Screenshot BRFC.](Credit_Risk_Analysis/Images/Balanced_Random.png)

6. Easy Ensemble AdaBooster Classifier
![Screenshot EEAC.](Credit_Risk_Analysis/Images/Easy_Ensemble.png)

## Summary
