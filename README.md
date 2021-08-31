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

This analysis endeavored to evaluate six different machine learning models in order to determine if any of them would be useful in evaluating loans. In order to determine which model is best, we first need to understand that not only do we desire a high balanced accuracy score, but we also need to know which is more preferable, a model that is more precise or more sensitive. From a loaning perspective, it would be more desirable to have a model which is more sensitive rather than precise. A company determining whether or not to loan would reject a low risk loan rather than failing to reject a high risk loan. Therefore, when comparing the above models, sensitivity needs to be looked for. After creating these six models, we can see that the Ensemble Classifier models (Balance Random Forest and Easy Ensemble AdaBoost) performed best. Between the two however, the Easy Ensemble AdaBoost Classifier came out on top. 