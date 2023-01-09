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
<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211338408-1e2a0edc-ed91-47ed-9bca-1135452c88f3.png">


A balanced accuracy score of `0.638` represent  that `36.2%` of classes are incorrect and `63.8%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.61` represent on this model quantified the number of positive class predictions made out of all positive examples `61%` of the time.

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211338531-04c2f325-1465-4340-9f1d-1c0418ab4f7d.png">



#### SMOTE Oversampling



SMOTE oversampling on lending services company LendingClub data gave the following scores :

Balanced Accuracy: `.658`
<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211338895-43d37039-0392-4312-9740-f015f582a093.png">


A balanced accuracy score of `0.658` represent  that `34.2%` of classes are incorrect and `63.8%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.69` represent on this model quantified the number of positive class predictions made out of all positive examples `69%` of the time.

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211338976-06b2291e-8562-425c-8af6-5f1cafb50b50.png">


### Undersampling Algorithms
#### Cluster Centroid  
Cluster Centroid  undersampling on lending services company LendingClub data gave the following scores :

Balanced Accuracy: `.544`
<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211339049-2b5d7eb5-abb5-43df-84f0-af95e35d62a8.png">

A balanced accuracy score of `0.544` represent  that `45.6%` of classes are incorrect and `54.4%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.40` represent on this model quantified the number of positive class predictions made out of all positive examples `40%` of the time.
<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211339099-9d1dfc53-d4c0-461a-8e8e-a2bf490a497c.png">


### Combination Sampling


#### SMOTEENN


SMOTEENN machine learning algorithm contain SMOTE &  Edited Nearest Neighbor (ENN) algorithm. In this model once the data was balaced  on lending services company LendingClub , below are the  following scores :

Balanced Accuracy: `.666`

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211339595-445dcd08-35ff-4bdb-bca9-cb16630ab313.png">


A balanced accuracy score of `0.666` represent  that `33.4%` of classes are incorrect and `66.6%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.54` represent on this model quantified the number of positive class predictions made out of all positive examples `54%` of the time.

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211339636-ca921334-30a5-4245-b653-94effe75d579.png">


#### Balanced Random Forest Classifier

In this model once the data was balaced  on lending services company LendingClub , below are the  following scores :

Balanced Accuracy: `.788`

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211339745-2c2fd04a-4ab9-470d-b39c-a7a642395eaa.png">


A balanced accuracy score of `0.788` represent  that `21.2%` of classes are incorrect and `78.8%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.87` represent on this model quantified the number of positive class predictions made out of all positive examples `87%` of the time.

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211339804-330aee09-cf16-4cee-95d0-941782298260.png">

#### Easy Ensemble AdaBoost Classifier

In this model once the data was balaced  on lending services company LendingClub , below are the  following scores :

Balanced Accuracy: `.931`

<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211340011-74d65218-2e85-4874-ab14-14de037f3320.png">


A balanced accuracy score of `0.931` represent  that `6.9%` of classes are incorrect and `93.1%` are correct.

The average precision score of `0.99` represent on this model quantified the number of positive class predictions that actually belong to the positive class 99% of the time.

The average recall score of `0.94` represent on this model quantified the number of positive class predictions made out of all positive examples `94%` of the time.


<img width="850" alt="image" src="https://user-images.githubusercontent.com/22928255/211340070-3f1f768a-c2f8-4245-8251-7c3ce39c64b7.png">


## Summary 

Based on the data , we analyzed that the oversampling , undersampling, and combination sampling algorithms predict the similar result. For the best fit model the ensemble classifiers model predict the best result. The accuracy score for first four models (Naive, SMOTE, SMOTTEEN and  Cluster Centroid  ) is not as high as the ensemble classifiers and the recall in the oversampling/undersampling/mixed models is low respectively. Easy Ensemble AdaBoost CLassifier performed the best overall. It had a balanced accuracy score, along with high precision and recall scores. 

