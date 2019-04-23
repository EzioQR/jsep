# ReadMe
## 1. DataSets results
The five folders contains the results of each data set.The files under each folder include the value of AUC,P,R,F1 metrics,specific information for diversity analysis,and the number of defective modules (i.e., =0), which can not be identified by any of chosen CPDP methods and the number of defective modules (i.e., =1), which can be only identified by one of the chosen CPDP methods. 

## 2. Computational cost of different CPDP methods.
This file stores the time(Unit: millisecond) cost of 11 CPDP methods selected by our paper method from data preprocessing to model training completion.Notice we do not list the computational cost of the CPDP method UM4, since this method is very simple and the computational cost is negligible.
## 3. Statistics of achieving Satisfactory Recommendation Standards CPDP pairs 
This file counts the proportion of CPDP pairs on each data set that achieve two satisfaction recommendation criteria to the total number of experiments on each data set.
## 4.Summary of Diversity Analysis of Supervised Models 
This file counts the diversity analysis between the models which are belong to supervised models.

## 5.Summary of Diversity Analysis of Unsupervised Models
This file counts the diversity analysis between the models which are belong to unsupervised models.
## 6.Summary of Diversity Analysis of Supervised Models and Unsupervised Models
This file counts the diversity analysis between the supervised models and unsupervised models.