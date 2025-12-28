>Task 5: Credit Card Fraud Detection
>Objective: Detect fraudulent transactions from 3,972 credit card records (0.05% fraud rate).
>Dataset: Credit card transactions 

> Results
- Detected all frauds in training 
-Fraud rate: 0.0504% 
-Random Forest + class weights = production-ready

> Approach
- Features: 30 anonymized features (V1-V28, Time, Amount)
- Model: Random Forest Classifier (class_weight='balanced')
- Evaluation: Confusion Matrix, Classification Report

> Key Insights
- Extreme imbalance: 20 frauds / 3,972 transactions
- Class weights perfectly handled 0.05% fraud rate
- Production-ready anomaly detection system

>Code Structure
1.Load + clean credit card dataset
2.EDA (fraud rate analysis)
3.StandardScaler + train/test split
4.Random Forest with class weights
5.Confusion matrix visualization
6.Production-ready fraud detector

>Tech Stack: Python, scikit-learn, pandas, matplotlib, seaborn, imbalanced-learn

