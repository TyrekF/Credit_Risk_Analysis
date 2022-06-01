# Credit_Risk_Analysis

## Overview of the loan prediction risk analysis:
* In 2019, more than 19 million Americans had at least one unsecured personal loan. That's a record-breaking number! Personal lending is growing faster than credit card, auto, mortgage, and even student debt. With such incredible growth, FinTech firms are storming ahead of traditional loan processes. By using the latest machine learning techniques, these FinTech firms can continuously analyze large amounts of data and predict trends to optimize lending.

## Purpose:
* Explain how a machine learning algorithm is used in data analytics.Create training and test groups from a given data set. Implement the logistic regression, decision tree, random forest, and support vector machine algorithms. Interpret the results of the logistic regression, decision tree, random forest, and support vector machine algorithms. Compare the advantages and disadvantages of each supervised learning algorithm. Determine which supervised learning algorithm is best used for a given data set or scenario. Use ensemble and resampling techniques to improve model performance.

## Results
### Naive Random Oversampling

![Naiver Random Oversampling](https://user-images.githubusercontent.com/96156893/171494264-cb7faa98-203a-4ded-9605-96e91158384d.png)

* Balanced Accuracy: 0.6413263312262552
* Precision: High-risk 0.01 | Low-risk = 1.00
* Recall: High-risk = 0.60  | Low-risk = 0.68


### SMOTE Oversampling
![smote oversampling](https://user-images.githubusercontent.com/96156893/171494307-bae35e9c-7eca-456c-b540-c0fae335c6cd.png)

* Balanced Accuracy: 0.6374415316001305
* Precision: High-risk 0.01 | Low-risk = 1.00
* Recall: High-risk = 0.60  | Low-risk = 0.68


### Undersampling
![Undersampling](https://user-images.githubusercontent.com/96156893/171494318-99ae413a-46c1-48cc-9984-48ce1cb1a52a.png)

* Balanced Accuracy: 0.5291858539710166
* Precision: High-risk 0.01 | Low-risk = 1.00
* Recall: High-risk = 0.61  | Low-risk = 0.45      


### Combination Under-Over Sampling
![combination](https://user-images.githubusercontent.com/96156893/171494386-82332499-adb6-4280-9484-cd92470efff0.png)

* Balanced Accuracy: 0.6376117496807152
* Precision: High-risk 0.01 | Low-risk = 1.00
* Recall: High-risk =  0.70 | Low-risk = 0.57


### Balanced Random Forest Classifier
![Balanced](https://user-images.githubusercontent.com/96156893/171494825-f7b518f2-5389-4734-b1c2-cbe902340f7a.png)

* Balanced Accuracy: 0.7959971556458013
* Precision: High-risk 0.04 | Low-risk = 1.00
* Recall: High-risk =  0.68 | Low-risk = 0.91


### Easy Ensemble AdaBoost Classifier
![Easy Ada](https://user-images.githubusercontent.com/96156893/171494453-cb86de98-89a3-4844-8eaa-b4bfe02ba84e.png)

* Balanced Accuracy: 0.9252521040566293
* Precision: High-risk 0.07 | Low-risk = 1.00
* Recall: High-risk =  0.91 | Low-risk = 0.94


## Summary:
There are multiple types of machine learning models to use. After completing the credit analysis for high and low risk loan application. The Easy Ensemble AdaBoost Classifier is the best model to choose with its .92 balanced accuracy. Also the balanced random forest classifier had a Balanced accuracy score of 0.79. The other machine learning models did not exceed 0.65. The ensemblers are the best model to use for the loan application.

