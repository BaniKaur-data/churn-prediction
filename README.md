
# Customer Churn Prediction (Telco)

**Goal:** Predict which customers are likely to churn so the business can intervene.  
**Dataset:** Telco Customer Churn (7,032 rows, 21 features).

## Results (test)
- Best model: **XGBoost @ threshold = 0.40**
- Accuracy ≈ 0.73  
- Recall (churners) **0.72** • Precision 0.50  
- Confusion matrix image: [`Churn-Prediction/dashboard/confusion_matrix_xgb.png`](Churn-Prediction/dashboard/confusion_matrix_xgb.png)

## Key Drivers
Month-to-month contract, short tenure, high monthly charges.  
**Actions:** incentivize longer contracts, early-tenure onboarding, loyalty offers for high bills.

## Files
- Notebook: [`Churn-Prediction/notebooks/churn_prediction.ipynb`](Churn-Prediction/notebooks/churn_prediction.ipynb)  
- Top features CSV: [`Churn-Prediction/dashboard/top_features_xgb.csv`](Churn-Prediction/dashboard/top_features_xgb.csv)  
- Requirements: [`Churn-Prediction/requirements.txt`](Churn-Prediction/requirements.txt)

## Run locally

