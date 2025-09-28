# Predicting High-Value Physician Payments (CMS Open Payments 2023)

## Overview
This project predicts high-value physician payments using the CMS Open Payments 2023 dataset.  
Business goal: improve compliance monitoring by minimizing false negatives, ensuring risky cases are not overlooked.

## Methods
- **Models compared**: Logistic Regression, SVM, Random Forest, XGBoost  
- **Hyperparameter Tuning**: RandomizedSearchCV with class_weight handling imbalance  
- **Evaluation Metrics**: Recall (primary), ROC-AUC, PR-AUC, confusion matrix  

## Results
- **Best model:** Random Forest  
- **Performance:** Highest recall among tested models  
- **Takeaway:** Prioritizing recall helps avoid missing potentially non-compliant high-value payments  
