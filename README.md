# Credit_Risk_Analysis

# Overview

### Purpose
The purpose of this project is to examine and evaluate the performance of different machine learning models to analyze credit risk.

### Background
Credit risk is an inherently unbalanced classification problem, as good loans easily outnumber risky loans. We will be employing different techniques to train and evaluate models with unbalanced classes.

Our models will include: 
- Naive Random Oversampling
- SMOTE Oversampling
- Undersampling 
- SMOTEENN Over & Undersampling
- Balanced Random Forest Classification
- Easy Ensemble Classification

# Results
### Naive Random Oversampling Model
<p align="center">
  <img src="https://user-images.githubusercontent.com/70111980/213828775-84fca979-8e10-42ff-9791-c080036d17d0.png">
</p>

- Balanced Accuracy Score: 0.63 or 63% accuracy
- Precision: 0.01 (High Risk)
- Recall: 0.66 (High Risk)

### SMOTE Oversampling Model
<p align="center">
  <img  src="https://user-images.githubusercontent.com/70111980/213828802-ecc62154-97be-4844-8411-0a0a4238a6ef.png">
</p>

- Balanced Accuracy Score: 0.65 or 65%
- Precision: 0.01
- Recall: 0.62

### Undersampling Model
<p align="center">
  <img  src="https://user-images.githubusercontent.com/70111980/213828844-70fdc9a7-0bba-445a-a630-6f7e27bcdfaa.png">
</p>

- Balanced Accuracy Score: 0.53 or 53%
- Precision: 0.01 (High Risk)
- Recall: 0.67 (High Risk)

### Combination Over & Under Sampling Model
<p align="center">
  <img  src="https://user-images.githubusercontent.com/70111980/213828885-c3c0a73d-129a-4f72-9b13-b7d712e880b3.png">
</p>

- Balanced Accuracy Score: 0.64 or 64%
- Precision: 0.01 (High Risk)
- Recall: 0.72 (High Risk)

### Balanced Random Forrest Classifier
<p align="center">
  <img  src="https://user-images.githubusercontent.com/70111980/213828941-78de9e4b-be3c-47ad-a6b6-a5a647e60c8f.png">
</p>
- Balanced Accuracy Score: 0.79 or 79%
- Precision: 0.04 (High Risk)
- Recall: 0.71 (High Risk)

### Easy Ensemble Classifier
<p align="center">
  <img  src="https://user-images.githubusercontent.com/70111980/213829027-62e96e5e-2310-4d4c-bd88-655d8ff6086f.png">
</p>

- Balanced Accuracy Score: 0.93 or 93%
- Precision: 0.09 (High Risk) 
- Recall: 0.92 (High Risk)

# Summary

### Model Performance & Recommendations
Of the six models examined the best performance comes from the Easy Ensemble Classifier. It has the highest accuracy of 93% and the greatest sensitivity to both high and low risk subjects. This means that of the six models used this model has the best chance to accurately identify High Risk and Low Risk individuals. 
