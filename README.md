# Predictive Maintenance Classification

## Data Source

https://archive.ics.uci.edu/ml/datasets/AI4I+2020+Predictive+Maintenance+Dataset  

## Abstract

The project use data from Predictive Maintenance to predict Failure of Machines.  Logistic 
Regression is first used to compare different data transformation methods. SMOTE method 
was used to handle the imbalanced data which increased the recall up to 0.75. Random Forest 
method was used to compare the recall and accuracy  for two data transformation for Min-max 
scaling and log min-max scaling , which showed pretty similar performance in accuracy and 
recall. Comparison of SVC, Random Forest and KNN showed good accuracy with Random 
Forest. Random Forest was tuned with hyper-parameters which improved the recall to 0.84 and 
accuracy 0.96. XGB boosting doesn’t much improve accuracy and recall.

## Reports 

[Final Report](https://github.com/newton-raphson/predictive-maintenance-fuseai/blob/main/report/FUSE%20MACHINE%20ML%20PROJECT%20REPORT.pdf)