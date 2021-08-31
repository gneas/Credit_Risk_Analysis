# Credit_Risk_Analysis

## Overview

The purpose of this project was to analyze a dataset from a peer-to-peer lending services company and determine if the machine learning models are useful in predicting credit risk.

## Results

### Naive Random Oversampling
![NaiveRandomOversampling](/images/NaiveRandomOversampling.png "NaiveRandomOversampling")

- Balanced Accuracy Score: 0.65
- Precision Score
    - High-Risk: 0.01
    - Low-Risk: 1.00
- Recall Score
    - High-Risk: 0.73
    - Low-Risk: 0.57

### SMOTE Oversampling
![SMOTEOversampling](/images/SMOTEOversampling.png "SMOTEOversampling")

- Balanced Accuracy Score: 0.66
- Precision Score
    - High-Risk: 0.01
    - Low-Risk: 1.00
- Recall Score
    - High-Risk: 0.63
    - Low-Risk: 0.68

### Cluster Centroid Undersampling
![ClusterCentroid](/images/ClusterCentroid.png "ClusterCentroid")

- Balanced Accuracy Score: 0.54
- Precision Score
    - High-Risk: 0.01
    - Low-Risk: 1.00
- Recall Score
    - High-Risk: 0.69
    - Low-Risk: 0.40

### SMOTEEN Combination Sampling
![SMOTEEN](/images/SMOTEEN.png "SMOTEEN")

- Balanced Accuracy Score: 0.65
- Precision Score
    - High-Risk: 0.01
    - Low-Risk: 1.00
- Recall Score
    - High-Risk: 0.72
    - Low-Risk: 0.57

### Balanced Random Forest Classifier
![BalancedRandomForest](/images/BalancedRandomForest.png "BalancedRandomForest")

- Balanced Accuracy Score: 0.79
- Precision Score
    - High-Risk: 0.03
    - Low-Risk: 1.00
- Recall Score
    - High-Risk: 0.70
    - Low-Risk: 0.87

### Easy Ensemble AdaBoost Classifier
![EasyEnsembleAdaBoost](/images/EasyEnsembleAdaBoost.png "EasyEnsembleAdaBoost")

- Balanced Accuracy Score: 0.93
- Precision Score
    - High-Risk: 0.09
    - Low-Risk: 1.00
- Recall Score
    - High-Risk: 0.92
    - Low-Risk: 0.94

## Summary

