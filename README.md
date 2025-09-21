# Loan Approval Prediction using SVM

This project predicts whether a loan application will be approved based on applicant details.

# Dataset: 
Contains demographic, financial, and loan-related features.

# Methods: 
Data cleaning, encoding, balancing with SMOTE, and training Support Vector Machine (SVM). Hyperparameter tuning was performed using GridSearchCV.

# Results:

Baseline SVM → Accuracy: ~72%, F1 (macro): 0.49

Tuned SVM (C=622, gamma=1.10, kernel='rbf') → F1-score: 0.81

# Conclusion:
Hyperparameter tuning significantly improved model performance. Future work may explore ensemble methods (Random Forest, XGBoost) and model explainability to identify key factors influencing loan approval.

👉
