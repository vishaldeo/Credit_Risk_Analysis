# Credit_Risk_Analysis

A Leading Lending firm need to analyze the credit risk data for the past trends. The data was gathered from peer-to-peer lending services company LendingClub and different machine learing models was used to predict the target value and best suited the model. For this analysis report we need to provide the best suited machine learning model based on their  accuracy score and imbalanced classification report. We also used the confusion matrix plot to show the data.
## Overview 

### Resource / Dependencies 

| Resource  |
| ----------- |  
| Jupyter Notebook  |  
| Python  |  
| Numpy |  
| Pandas |  
| SKLearn |  
| ImbalancedLearn |  

## Result 

### Oversampling Algorithms

#### Naive Random Oversampling

Naive random oversampling on lending services company LendingClub data gave the following scores:

Balanced Accuracy: `.638`

A balanced accuracy score of `0.638` represent  that `36.2%` of classes are incorrect and `63.8%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.61` represent on this model quantified the number of positive class predictions made out of all positive examples `61%` of the time.



#### SMOTE Oversampling



SMOTE oversampling on lending services company LendingClub data gave the following scores :

Balanced Accuracy: `.658`

A balanced accuracy score of `0.658` represent  that `34.2%` of classes are incorrect and `63.8%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.69` represent on this model quantified the number of positive class predictions made out of all positive examples `69%` of the time.



### Undersampling Algorithms
#### Cluster Centroid  
Cluster Centroid  undersampling on lending services company LendingClub data gave the following scores :

Balanced Accuracy: `.544`

A balanced accuracy score of `0.544` represent  that `45.6%` of classes are incorrect and `54.4%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.40` represent on this model quantified the number of positive class predictions made out of all positive examples `40%` of the time.


### Combination Sampling


#### SMOTEENN


SMOTEENN machine learning algorithm contain SMOTE &  Edited Nearest Neighbor (ENN) algorithm. In this model once the data was balaced  on lending services company LendingClub , below are the  following scores :

Balanced Accuracy: `.666`

A balanced accuracy score of `0.666` represent  that `33.4%` of classes are incorrect and `66.6%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.54` represent on this model quantified the number of positive class predictions made out of all positive examples `54%` of the time.
#### Balanced Random Forest Classifier

In this model once the data was balaced  on lending services company LendingClub , below are the  following scores :

Balanced Accuracy: `.788`

A balanced accuracy score of `0.788` represent  that `21.2%` of classes are incorrect and `78.8%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.87` represent on this model quantified the number of positive class predictions made out of all positive examples `87%` of the time.


#### Easy Ensemble AdaBoost Classifier

In this model once the data was balaced  on lending services company LendingClub , below are the  following scores :

Balanced Accuracy: `.931`

A balanced accuracy score of `0.931` represent  that `6.9%` of classes are incorrect and `93.1%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.94` represent on this model quantified the number of positive class predictions made out of all positive examples `94%` of the time.




## Summary 

Based on the data , we analyzed that the oversampling , undersampling, and combination sampling algorithms predict the similar result. For the best fit model the ensemble classifiers model predict the best result. The accuracy score for first four models (Naive, SMOTE, SMOTTEEN and  Cluster Centroid  ) is not as high as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low respectively. Easy Ensemble AdaBoost CLassifier performed the best overall. It had a balanced accuracy score, along with high precision and recall scores. 

