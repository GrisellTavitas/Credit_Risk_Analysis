# Credit_Risk_Analysis
Supervised Machine Learning

## Overview of the analysis.

We have been hired to help LendingClub, a peer-to-peer lending services company, in order to improve the predictions of credit risk; so that we will use the following mentioned different models of Supervised Machine Learning, till we find the model that reflects the best reliable results. 

- Resampling Models to Predict Credit Risk: 
  - Random Oversampling
  - SMOTE oversampling
  - ClusterCentroids resampling
- The SMOTEENN Algorithm to Predict Credit Risk
  - Combination (Over and Under) Sampling
- Ensemble Classifiers to Predict Credit Risk
  - Balanced random forest classifier
  - Easy ensemble AdaBoost classifier
  
## Results.


![Random_oversampling](https://user-images.githubusercontent.com/90433064/151721751-4fb9350f-a644-4630-a7fc-9867338d35a1.png)

Balanced accuracy score = 66%.
High_risk precision = 1% with sensitivity = 60% and F1 = 2% .
Low_risk precision = 100% rounded, with sensitivity = 71% and F1 = 75%

![SMOTE_oversampling](https://user-images.githubusercontent.com/90433064/151721761-840e156b-03ae-48fd-a181-b7cacecda202.png)

Balanced accuracy score = 66%.
High_risk precision = 1% with sensitivity = 63% and F1 = 2% .
Low_risk precision = 100% rounded, with sensitivity = 69% and F1 = 82%

![Undersampling](https://user-images.githubusercontent.com/90433064/151721766-445aead1-835d-4dc6-924e-570b3e3adb6a.png)

Balanced accuracy score = 54%.
High_risk precision = 1% with sensitivity = 69% and F1 = 1% .
Low_risk precision = 100% rounded, with sensitivity = 40% and F1 = 57%

![Combination_sampling](https://user-images.githubusercontent.com/90433064/151721790-9fd6d191-525d-40ee-958f-e34000a98265.png)

Balanced accuracy score = 64%.
High_risk precision = 1% with sensitivity = 72% and F1 = 2% .
Low_risk precision = 100% rounded, with sensitivity = 57% and F1 = 72%

![Balanced_random_forest_classifier](https://user-images.githubusercontent.com/90433064/151721817-1082c078-655b-4116-b45b-0f7f5bb9968f.png)

Balanced accuracy score = 77%.
High_risk precision = 3% with sensitivity = 67% and F1 = 6% .
Low_risk precision = 100% rounded, with sensitivity = 87% and F1 = 93%

![Easy_ensemble_AdaBoost_Classifier](https://user-images.githubusercontent.com/90433064/151721822-7f42a6a9-8aa5-4eda-89ab-8ab9bf8ea768.png)

Balanced accuracy score = 93%.
High_risk precision = 9% with sensitivity = 97% and F1 = 16% .
Low_risk precision = 100% rounded, with sensitivity = 94% and F1 = 97%

