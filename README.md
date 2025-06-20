# Loan_Status_Prediction
Loan Approval Prediction System using Support Vector Machine (SVM) classification

This project successfully implements a machine learning model to predict loan approval status based on applicant data.

✅ Accuracy

Training Accuracy: 80%

Test Accuracy: 79%
The model demonstrates consistent performance on both training and unseen data, indicating a good generalization capability.

📊 Confusion Matrix

True Positives (TP): 33

True Negatives (TN): 5

False Positives (FP): 10

False Negatives (FN): 0

💡 Observations

The model is more effective at correctly predicting loan approvals than denials.

False Positives (10) represent cases where ineligible applicants were predicted as approved — a critical issue in real-world finance.

📈 Recommendation

The current model can be reliably used for loan approval prediction, but caution is necessary:

False Positives must be reduced to avoid risky financial decisions.

Consider testing other algorithms (e.g., Random Forest, XGBoost) or advanced preprocessing to improve accuracy and reliability.

🔍 Further Improvements

Analyze feature importance to understand influential factors.

Enhance data preprocessing techniques (handling outliers, encoding).

Evaluate multiple ML algorithms for better performance and lower false approval rates.
