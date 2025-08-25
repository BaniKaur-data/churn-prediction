# Customer Churn Prediction (Telco)

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/BaniKaur-data/churn-prediction/blob/main/Churn-Prediction/notebooks/churn_prediction.ipynb)

**Goal:** Predict which customers are likely to churn so the business can intervene.  
**Dataset:** Telco Customer Churn (7,032 rows, 21 features).

## Results (test)
- Best: **XGBoost @ threshold = 0.40**
- Accuracy ≈ 0.73 • Recall (churners) **0.72** • Precision 0.50  
- Confusion matrix: [dashboard/confusion_matrix_xgb.png](dashboard/confusion_matrix_xgb.png)

Month-to-month contract, short tenure, high monthly charges.  
**Actions:** Incentivize longer contracts, early-tenure onboarding, loyalty offers for high bills.

## Files
- Notebook: [Churn-Prediction/notebooks/churn_prediction.ipynb](Churn-Prediction/notebooks/churn_prediction.ipynb)  
- Top features CSV: [dashboard/top_features_xgb.csv](dashboard/top_features_xgb.csv)  
- Requirements: [requirements.txt](requirements.txt)

## Run locally
