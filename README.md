
# Credit Card Fraud Detection (ML Pipeline)

This project demonstrates an end-to-end machine learning pipeline for detecting
fraudulent credit card transactions using:

- Data preprocessing
- Handling class imbalance with SMOTE
- Train/Test split + cross validation
- Logistic Regression classifier
- Evaluation using ROC-AUC

The script uses a **synthetic dataset** so it can run without downloading anything.
You can later replace it with the Kaggle credit card dataset if needed.

## How to run

1. Install dependencies:
   pip install -r requirements.txt

2. Run:
   python fraud_detector.py

A trained model will be saved as `fraud_model.pkl`.
