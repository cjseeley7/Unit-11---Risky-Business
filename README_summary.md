# Unit 11 - Risky Business
 
 In this assignment, the following machine learning techniques were used and analysed to determine credit risk.


1. [Resampling](#Resampling)
2. [Ensemble Learning](#Ensemble-Learning)

- - -

## Summary

- - -

## Resampling

### 1) Simple Logistic Regression
* Balanced Accuracy Score: 0.9543211898288821
* Average Recall Score: 0.99
* Geometric Mean Score: 0.95

### 2) Random Oversampling
* Balanced Accuracy Score: 0.9946414201183431
* Average Recall Score: 0.99
* Geometric Mean Score: 0.99

### 3) SMOTE Oversampling
* Balanced Accuracy Score: 0.9946680739911509
* Average Recall Score: 0.99
* Geometric Mean Score: 0.99

### 4) Cluster Centroids Undersampling
* Balanced Accuracy Score: 0.9932813049736127
* Average Recall Score: 0.99
* Geometric Mean Score: 0.99

### 5) Combination (Over and Under) Sampling 
* Balanced Accuracy Score: 0.9946680739911509
* Average Recall Score: 0.99
* Geometric Mean Score: 0.99

## Ensemble

In this section, I compared two different ensemble classifiers to predict loan risk and evaluate each model. The Balanced Random Forest Classifier and the Easy Ensemble Classifier. 

* The Balanced Random Forest Classifier had a Balanced Accuracy Score of 0.7887512850910909, while The Easy Ensemble Classifier had a Balanced Accuracy Score of 0.931601605553446. 

* The Easy Ensemble Classifier also had the better average recall score of 0.94, compared with the Balanced Random Forest Classifier's recall score of 0.87.

* The Easy Ensemble Classifier had the best Average Geometric Score of 0.93, compared with a score of 0.78 for the Balanced Random Forest Classifier.

* The top three features for the data set were;
1) total_rec_prncp
2) total_pymnt 
3) total_pymnt_inv


