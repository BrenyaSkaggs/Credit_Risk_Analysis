## Overview

Using Machine Learning (imbalanced-learn and sickit-learn libraries) to evaluate models to determine credi card risk. We will be using credit card data 
from LendingClue, a peer-to-peer lending services company.




## Results  

*Random Over Sampler
![This is an image](https://raw.githubusercontent.com/BrenyaSkaggs/Credit_Risk_Analysis/main/Resources/oversampling_naive%20random.png)


-Balanced accuracy score: 57%
-Precision score
    high_risk: 1%
    low_risk: 100%
-Recall score
    high_risk: 63%
    low_risk:  69%




*SMOTE
![This is an image](https://raw.githubusercontent.com/BrenyaSkaggs/Credit_Risk_Analysis/main/Resources/SMOTE.png)


-Balanced accuracy score:  66%
-Precision score
    high_risk: 1%
    low_risk:  100%
-Recall score
    high_risk: 63%
    low_risk:  69%




*Cluster Centroids
![This is an image](https://raw.githubusercontent.com/BrenyaSkaggs/Credit_Risk_Analysis/main/Resources/Undersampling_ClusterCentroids.png)


-Balanced accuracy score:  57%
-Precision score
    high_risk: 1%
    low_risk:  100%
-Recall score
    high_risk: 69%
    low_risk:  40%




*SMOTEENN
![This is an image](https://raw.githubusercontent.com/BrenyaSkaggs/Credit_Risk_Analysis/main/Resources/SMOTEENN.png)


-Balanced accuracy score: 54%
-Precision score
    high_risk: 1%
    low_risk:  100%
-Recall score
    high_risk:  72%
    low_risk:   75%




*Balanced Random Forest Classifier
![This is an image](https://raw.githubusercontent.com/BrenyaSkaggs/Credit_Risk_Analysis/main/Resources/_balancedrandomforest.png)


-Balanced accuracy score:  78%
-Precision score
    high_risk: 4%
    low_risk:  100%
-Recall score
    high_risk: 67%
    low_risk:  91%



*Easy Ensemble Classifier
![This is an image](https://raw.githubusercontent.com/BrenyaSkaggs/Credit_Risk_Analysis/main/Resources/easyensemble_adaboost.png)


-Balanced accuracy score: 92%
-Precision score
    high_risk: 7%
    low_risk:  100%
-Recall score
    high_risk:  91%
    low_risk:   94%



## Summary  There is a recommendation on which model to use, or there is no recommendation with a justification

The Balanced RAndom Forest Classifier and Easy Ensemble Classifier had the two highest balanced accuracy scores and recall score. The low risk 
precision score was the same for all models. After reviewing the models above i would not recommend any of them to assist with credit risks given the similar outcome 
for most of the models. 

