# Credit-Risk-Analysis

## Overview of Analysis
The purpose of this analysis is to classify credit risk using six different supervised mechine learing models and then evaluate them to compare model accuracy.

## Results
- Native Random Oversampling
  - Accuracy Score = 64.38%
  - Precision = 99%
  - Recall = 60%

![Random Sampling](https://user-images.githubusercontent.com/117960721/235575110-92cf1119-6f54-43f4-8cdc-f366c42121ac.png)


- SMOTE Oversampling
  - Accuracy Score = 66.28%
  - Precision = 99%
  - Recall = 69%

![Smote](https://user-images.githubusercontent.com/117960721/235575069-131bbdbc-9521-4393-83d0-6892ac42530a.png)


- Undersampling
  - Accuracy Score = 54.47%
  - Precision = 99%
  - Recall = 40%

![Undersampling](https://user-images.githubusercontent.com/117960721/235575042-9a724e56-b23d-4ae3-8bb5-dc6c00b2cbe9.png)


- Combination Over and Undersampling
  - Accuracy Score = 67.48%
  - Precision = 99%
  - Recall = 59%

![combo](https://user-images.githubusercontent.com/117960721/235575023-91354de5-315f-488f-8626-c2477f730e8f.png)


- Balanced Random Forest Classifier
  - Accuracy Score = 78.85%
  - Precision = 99%
  - Recall = 87%

![random forest](https://user-images.githubusercontent.com/117960721/235575000-5084e3b7-a319-4a3a-abab-56a671bda239.png)


- Easy Ensaemble AdaBoost
  - Accuracy Score = 93.16%
  - Precision = 99%
  - Recall = 94%

![AdaBoost](https://user-images.githubusercontent.com/117960721/235577020-eacb23d5-6c35-4202-b95f-2e43d7467931.png)



## Summary
The balanced accuracy helps us determine the overall best model.  Comparing the balanced accuracy scores of our six model we find the the Easy Ensaemble AdaBoost has the highest score.  The accuracy scores of the other models are between 54% and 78%.  The AdaBoost has an accuracy score of 93.16%, a 99% average precision score and a 94% average recall score.  On there own these scores are higher then any of the other models and in combination show that the Easy Ensamble AdaBoost is the the best supervised machine learning model to use when preforming the credit card analysis.
