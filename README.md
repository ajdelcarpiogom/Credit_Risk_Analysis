# Credit_Risk_Analysis

### Overview
Great methods data scientists use in order to evaluate risk is creating a model and then evaluate and train the models that they create. In this project we are using imbalanced-learn and scikit-learn libraries in order to build those models and evaluating them.

### Results
Random Oversampler Model
  - The balanced accuracy score is 65%.
  - The high_risk precision is about 1% only with 62% sensitivity which gives a 2% F1 score.
  - Due to the high number of the low risk population, the precision is approximately 100% with a sensitivity of 68%.
  
SMOTE Motel
  - The balanced accuracy score is 64%.
  - The high_risk precision is about 1% only with 63% sensitivity which gives a 2% F1 score.
  - Due to the high number of the low risk population, the precision is approximately 100% with a sensitivity of 66%.

ClusterCentroids Model
  - Here the balanced accuracy score is down to about 52%.
  - The high_risk precision is 1% with 63% sensitivity which gives a 1% F1 score.
  - Due to the high number of false positives, the low risk sensitivity is 40%.

SMOTEENN Model
  - The balanced accuracy score is about 62%.
  - The high_risk precision is 1% with 68% sensitivity which gives a 2% F1 score.
  - Due to the high number of false positives, the low_risk sensitivity is 57%.

Balanced Random Forest Classifier Model
  - The balanced accuracy score improved to approximately 79%.
  - The high_risk precision is 4% with 67% sensitivity which gives a F1 score of 7%.
  - Due to a lower number of false positives, the low_risk sensitivity is now 91% with 100% presicion.

Easy Ensemble Classifier
  - Now, the balanced accuracy score is high to about 93%.
  - The high_risk precision is 7% with 91% sensitivity which makes a F1 of only 14%.
  - Due to a lower number of false positives, the low_risk sensitivity is now 94% with 100% presicion!

### Summary
All the models I used in order to perform the credit risk analysis expressed weak precision in determining whether the credit risk is high.
The Ensemble models brought a lot more improvement specially on the sensitivity of the high risk credits. The EasyEnsembleClassifier model shows a recall of 92% so it detects almost all high risk credit. Between those, the best model to use if needed would be the EasyEnsembleClassifier Model.
