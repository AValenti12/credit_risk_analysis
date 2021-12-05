# credit_risk_analysis

# Overview 

The purpose of the this project was to apply machine learning to review credit card risk. We used data provided by LendingClub, we tested various algorythims for acccuracy to see which bests predicts low and high risk applicants.

# Results

## Random Oversampling
- Acccuracy: 65% 
- Precision High Risk: 1%, recall/sensivity 66%
- Precision Low risk: 100%, recall/sensitivity 67%
![balancedaccuracyscore](https://user-images.githubusercontent.com/88061345/144730062-b1c6ed37-36b4-43f0-9acb-3f0ee88e0867.PNG)
![imbalancedclassifcationreport](https://user-images.githubusercontent.com/88061345/144730132-02a867fa-1e96-4949-a3a2-2e03b01fd3e8.PNG)

## SMOTE 
- Accuracy: 66% 
- Precision High risk: 1%, recall/sensitivity 63%
- Precision Low Risk: 100%, recall/sensitivity 66%

![smotmodel](https://user-images.githubusercontent.com/88061345/144730281-cc814b9c-e30e-4b1e-a5ae-df2638762303.PNG)

## Cluster Centoids
- Accuracy: 45%
- Precision High risk: 1%, recall/sensitivity 61%
- Precision low risk: 100%, recall/sensitivity 45%

![balancedaccuracyscore](https://user-images.githubusercontent.com/88061345/144730062-b1c6ed37-36b4-43f0-9acb-3f0ee88e0867.PNG)

## Combination (Over and Under) Sampling
- Accuracy: 54%
- Precision High Risk: 1%, recall/sensitivity 72%
- Precision Low Risk: 100%, recall/sensitivity 54%

![combination](https://user-images.githubusercontent.com/88061345/144730767-38a85b32-e68b-48d8-9271-ca506fcfd279.PNG)


## Random Forest Classifier
- Accuracy: 91%
- Precision high risk: 4%, recall/sensitivty 67%
- Precision low risk: 100%, recall/sensitivity 100%

![randomforest](https://user-images.githubusercontent.com/88061345/144730801-e5de3745-1087-45c1-98f7-81c3a1020f8c.PNG)


## Easy Ensemble AdaBoost Classifier
- Accuracy 79%
- Precision High Risk 4%, recall/sensitivity 67%
- Precision Low Risk 100%, recall/sensitiby 91%
![ensamble](https://user-images.githubusercontent.com/88061345/144731434-8bd15e4a-1dc8-45cf-98d5-0bd0f08f2057.PNG)

# Summary

Of all the models, the random forest classifier had the highest accuracy at 91%. Followed by the easy ensemble at 79%, then smote 66% closly behind that random oversampling 65%. then  Combination over and under sampling 54% and finally cluster 45%. Given these results, I would recommend using the random forest classifer model as it had the highest overall accuracy.









