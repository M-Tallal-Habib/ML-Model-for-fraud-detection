# State-of-Art model for detection of fraudulent transactions

## Main objective of the Project
  The main objective of the project was to inflate the fraud rate from 2.5% (1356/54778) to 5% 
  but I achieved 6.6% (3615/54778) using K-Nearest Neighbors algorithm fined tuned with 7 neighbors using K-Fold Cross Validation
## Dataset
   The dataset belongs to a local bank in England not publically available anywhere and is confidential
## Data Exploration
  
  In this section missing values handling and transactions were identified in which most fraudulent activities occurred
  e.g 
  1) Which type merchants in transactions are flagged fradulent
  2) In Which type of entry method in transactions are flagged fradulent

## Feature Engineering and Selection
   Many useful features are created using existing features
   e.g
   1) From TERMS_VERSION feature like transaction year, day, month were created
   
## Information Value and Weight of Evidence
    For feature selection IV is used and features are ranked in descending order 
    of IV and selected according too the criterian of IV.
    
    
## Model Building

   1) Logistic Regression, XG-Boost and Random Forest were used and XG-Boost performed well on the bases of area under the curve.
   2) Hyper Parameters were tuned using Stratified cross-validation method

## Performance Measures
    Following performance measures were used
    1) Accuracy
    2) Precision
    3) Recall
    4) F1 Score
    5) ROC-AUC-Curve
    
    For best model selection ROC-AUC-Curve was used because dataset was highly imbalanced.
    
    
    
