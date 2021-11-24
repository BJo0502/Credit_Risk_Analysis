# Module 17 Challenge: Credit Risk Analysis

# Overview

For this project we utilize a LendingClub credit card dataset to determine the most efficient model to predict credit risk. We are asked to use several different machine learning techniques including oversampling with Random Over Sampler and SMOTE, under sampling with Cluster Centroids, and combinatorial techniques including Balanced Random Forest Classifier and Easy Ensemble Classifier algorithms.

# Results

## Naive Random Oversampling:
![Naive](https://user-images.githubusercontent.com/88041368/143320170-2279b717-4c0d-4ae5-bd08-7ca0af43d106.jpg)
Balanced Accuracy: 0.6438627638488825
Precision: High Risk: ~1%
Recall: 69%

## SMOTE:
![SMOTE](https://user-images.githubusercontent.com/88041368/143320173-68569f72-bba0-48ac-ab7d-766ac73b816b.jpg)
Balanced Accuracy: 0.6628910844779521
Precision: High Risk: ~1%
Recall: 63%

## Cluster Centroids:
![Cluster](https://user-images.githubusercontent.com/88041368/143320168-cd15e386-2d84-4ef1-8c5f-43ce804e9287.jpg)
Balanced Accuracy: 0.6628910844779521
Precision: High Risk: ~1%
Recall: 69%

## Combination SMOTEENN:
![SMOTEENN](https://user-images.githubusercontent.com/88041368/143320174-4825c434-a862-492a-8202-7ce034ddc17a.jpg)
Balanced Accuracy: 0.5447339051023905
Precision: High Risk: ~1%
Recall: 72%

## Balanced Random Forest:
![RandomForest](https://user-images.githubusercontent.com/88041368/143320171-37764620-6853-4075-b5f8-161b9e2f3775.jpg)
Balanced Accuracy: 0.7844011748069183
Precision: High Risk: ~3%
Recall: 68%

## Easy Ensemble:
*These results were provided in the starter code. Unfortunately, the bug prevented me for solving for my own results*
![EasyEn](https://user-images.githubusercontent.com/88041368/143320169-a02e42d9-4ec1-46d1-bbf8-2d2bb4882107.jpg)
Balanced Accuracy: 0.9316600714093861
Precision: High Risk: ~9%
Recall: 92%

# Results

Since we are attempting to predict credit risk we can say that precision is likely more important than sensitivity (recall) because we would want to get as close as we can to accurately predicting those that are high risk even if that means some people that may be low risk, fall through the cracks. According to our results, the Ensemble Learners approach, in particular, the Easy Ensemble Classier algorithm yielded the most promising scores.
