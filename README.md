# Credit Risk Analysis

## Overview
* This analysis was performed using Machine Learning in Jupyter Notebook. The types of tests performed were: Naive Random Oversampling, SMOTE, Cluster Centroids, SMOTEENN, Balanced Random Forest Classifier, and Easy Ensemble Classifier. Based on the results of these test a recommendation was made on which model would predict credit risk the best.

## Results

### Naive Random Oversampling

<p align="center">
  <img 
    src=Resources/naive.png
  >
</p>

* Balanced Accuracy Score: **63%**
* Precision Score:
    * High Risk: **1%**
    * Low Risk: **100%**
* Recall Score: 
    * High Risk: **57%**
    * Low Risk: **68%**

### SMOTE

<p align="center">
  <img 
    src=Resources/smote.png
  >
</p>

* Balanced Accuracy Score: **63%**
* Precision Score:
    * High Risk: **1%**
    * Low Risk: **100%**
* Recall Score: 
    * High Risk: **62%**
    * Low Risk: **63%**

### Cluster Centroids Algorithm

<p align="center">
  <img 
    src=Resources/cluster.png
  >
</p>

* Balanced Accuracy Score: **53%**
* Precision Score:
    * High Risk: **1%**
    * Low Risk: **100%**
* Recall Score: 
    * High Risk: **61%**
    * Low Risk: **45%**

### SMOTEENN

<p align="center">
  <img 
    src=Resources/smoteenn.png
  >
</p>

* Balanced Accuracy Score: **62%**
* Precision Score:
    * High Risk: **1%**
    * Low Risk: **100%**
* Recall Score:
    * High Risk: **70%**
    * Low Risk: **54%**

### Balanced Random Forest Classifier

<p align="center">
  <img 
    src=Resources/brfc.png
  >
</p>

* Balanced Accuracy Score: **79%**
* Precision Score:
    * High Risk: **4%**
    * Low Risk: **100%**
* Recall Score:
    * High Risk: **67%**
    * Low Risk: **91%**


### Easy Ensemble AdaBoost Classifier

<p align="center">
  <img 
    src=Resources/eec.png
  >
</p>

* Balanced Accuracy Score: **93%**
* Precision Score:
    * High Risk: **7%**
    * Low Risk: **100%**
* Recall Score:
    * High Risk: **91%**
    * Low Risk: **94%**


## Summary 
* The recommended model is the Easy Ensemble Classifier. This model had a **93%** accuracy score. The precision scores for high risk was very low for each model, however, the model recommended has the highest precision scores, recall scores, and balanced accuracy scores of all of the models tested.

## Questions

* You can contact me via email or GitHub!

    * Email: emilyporter920@gmail.com
    * GitHub Profile: Emily Porter || github.com/emilyporter920 
