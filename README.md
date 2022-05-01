# Credit_Risk_Analysis

## OverView of analysis

This analysis focuses on credit risk based on a dataset provided by Lending Club. A total of six machine learning methods were tested to see if there is a method that proves to be statistically accurate in predicting credit risk for individuals applying through Lending Club.

## Results:

#### Naïve Random Oversampling calculations:
* Balanced accuracy score: 0.644 (64.4%)

  ![image](https://user-images.githubusercontent.com/26393180/166168097-66204dce-f38a-4ddd-8595-3c5868b92d22.png)

* Precision: 0.01 (1%)
* Recall scores: 0.69 (69%)

  ![image](https://user-images.githubusercontent.com/26393180/166168108-e30df2bf-d36d-4dfc-bcd2-db81a4cb81ae.png)

#### SMOTE Oversampling Calculations:
* Balanced accuracy score: 0.663 (66.3%)

  ![image](https://user-images.githubusercontent.com/26393180/166168127-433724a7-667b-4d40-959c-798ecdcc15b3.png)

* Precision: 0.01 (1%)
* Recall scores: 0.63 (63%)

  ![image](https://user-images.githubusercontent.com/26393180/166168141-cf84f6fc-9aa2-4480-af7c-00384d56c5ae.png)

#### Under sampling Calculations:
* Balanced accuracy score: 0.589 (58.9%)

  ![image](https://user-images.githubusercontent.com/26393180/166168160-ed063015-eb3b-4ed8-bc35-bd891e67ffdc.png)

* Precision: 0.01 (1%)
* Recall scores: 0.63 (63%)

  ![image](https://user-images.githubusercontent.com/26393180/166168175-5ff33e86-1ed7-48e7-a91c-06ad74385e61.png)

#### SMOTEENN (Combination over and under sampling) calculations:
* Balanced accuracy score:0.645 (64.5%)

  ![image](https://user-images.githubusercontent.com/26393180/166168189-475d6e4e-1949-415b-9b60-985f41f102a7.png)

* Precision:0.01 (1%)
* Recall scores: 0.72 (72%)

  ![image](https://user-images.githubusercontent.com/26393180/166168196-6aa29db3-3d9b-4518-b6a7-83b915b730f4.png)

#### Balanced Random Forest Classifier Calculations:
* Balanced accuracy score: 0.678 (67.8%)

  ![image](https://user-images.githubusercontent.com/26393180/166168206-7549608c-953b-434b-b3ee-43126c5667f4.png)

* Precision: 0.95 (95%)
* Recall scores: 0.36 (36%)

  ![image](https://user-images.githubusercontent.com/26393180/166168242-238400f8-bb45-4546-a5bd-8b372bfdf7c5.png)

#### Easy Ensemble AdaBoost Classifier Calculations:
* Balanced accuracy Score: 0.930 (93.0%)

  ![image](https://user-images.githubusercontent.com/26393180/166168259-3d2e2df1-8fda-426c-bb95-44a62e083e80.png)

* Precision: 0.08 (8%)
* Recall scores: 0.92 (92%)

  ![image](https://user-images.githubusercontent.com/26393180/166168271-cf356e56-28e5-48f7-8ca5-c0b0fc41014e.png)

## Summary

Based on the results above, there are some models that statically show to be a better fit for performing credit risk analysis for the dataset compared to others. The oversampling, under sampling and combination sampling algorithms had low balance accuracy scores compared to the others. Even though the balanced random forest classifier scored high for accuracy at about 68%, the accuracy score for the Easy Ensemble AdaBoost Classifier algorithm surpassed all the other algorithms with an accuracy score of about 93%. With its high accuracy and high recall (92%) score, I would recommend using the Easy Ensemble AdaBoost Classifier algorithm to perform credit risk analysis calculations for Lending Key applicants. 




