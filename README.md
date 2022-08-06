# Credit_Risk_Analysis


## Overview

The purpose of this analysis is to predict credit risk using LendingClubs credit dataset with machine learning and compare multiple models in order to reduce bias.


## Results

#### Random Oversampling</br>
 ![image](https://user-images.githubusercontent.com/102704559/183259929-1e54b36e-72c9-4c70-84b2-31e7487c9bf5.png)</br>
 - Balanced Accuracy: 0.6438</br>
 - High Risk Precision is low and Low Risk is high</br>
 - Recall: High: 0.69, Low: 0.59</br>


#### SMOTE Oversampling</br>
![image](https://user-images.githubusercontent.com/102704559/183259952-0d205d59-ea93-439a-8be8-70b9f3aa949a.png)
- Balanced Accuracy: 0.6628
- High Risk Precision is low and Low Risk is high</br>
- Recall: High: 0.63, Low: 0.69

#### Undersampling</br>
![image](https://user-images.githubusercontent.com/102704559/183259959-268fc3ef-ce92-47a0-9e57-4280076fea55.png)
- Balanced Accuracy: 0.5447
- High Risk Precision is low and Low Risk is high</br>
- Recall: High: 0.69, Low: 0.40

#### Combination Over/Under Sampling</br>
![image](https://user-images.githubusercontent.com/102704559/183259994-320458c9-0376-4f9f-8b21-0964562a5edd.png)
- Balanced Accuracy: 0.6748
- High Risk Precision is low and Low Risk is high</br>
- Recall: High: 0.76, Low: 0.59


#### Balanced Random Forest Classifier</br>
![image](https://user-images.githubusercontent.com/102704559/183260032-1575363b-1c36-401b-91c4-356fbf40bfdd.png)
- Balanced Accuracy: 0.7885
- High Risk Precision is low and Low Risk is high</br>
- Recall: High: 0.70, Low: 0.87

#### Easy Ensemble Classifier</br>
![image](https://user-images.githubusercontent.com/102704559/183260049-45bd3dce-6727-4a41-ae27-fc638a8a8f22.png)
- Balanced Accuracy: 0.9316
- High Risk Precision is low and Low Risk is high</br>
- Recall: High: 0.92, Low: 0.94


## Summary

For this credit card risk dataset, the results show that the Easy Ensemble Classifier is that best model to use, with a 0.93 balanced accuracy score. Every other model had an accuracy score below 0.8. The precision scores were similar throughout all models, however the recall score for both High and Low risk for Easy Ensemble was highest at .94 and .91 respectively.
