# Car Claim Fraud – Experimental Pipeline

Full pipeline for fraud detection on imbalanced car-claim data (Carclaimtxt, AICD):
- Preprocessing + feature engineering  
- Repeated Stratified 5×3 CV (15 runs)  
- Resampling  
- Metrics: Accuracy, Precision, Recall, F1, ROC-AUC, PR-AUC, FP/TP  

## Install

```bash
pip install numpy pandas scikit-learn==1.2.2 scikeras tensorflow \
            xgboost lightgbm catboost imbalanced-learn \
            matplotlib seaborn scipy openpyxl
