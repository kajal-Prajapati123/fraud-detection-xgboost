# Project Title
  fraud-detection-xgboost

# Problem Statement
  This project builds a machine learning model to detect fraudulent credit card transactions using an imbalanced dataset from Kaggle.

# Dataset 
- Kaggle creditcard.csv
- 284,807 transections 
- Highly imbalanced 
- features V1-v28 are PCA transformed

# Model Used 
- XGBoost classifier
- Scaled amount feature
- Threshold tuning support 

# Model Performance (Fraud Class)
- Fraud Precision: 0.66
- Fraud Recall: 0.86 
- (High recall ensures most frauds are detected)
- Fraud F1-Score: 0.74

# How to Run
- pip install -r requirnment.txt
- streamlit run app.py

# Deployment Link
   https://fraud-detection-xgboost-arpnh9cybsadfy9ammllp7.streamlit.app/
  
