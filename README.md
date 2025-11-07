# Credit Card Fraud Detection

This is a machine learning project to detect fraudulent credit card transactions.

## Project Details
- Dataset: Kaggle – Credit Card Fraud Detection
- ML Models: Logistic Regression, Random Forest, XGBoost
- Handling Imbalanced Data: SMOTE
- Final Output: Trained model saved as `fraud_detection_model.pkl`

## Files Included
- `notebook.ipynb` – Full code and model training
- `fraud_detection_model.pkl` – Trained model
- `classification_report.txt` – Performance results
- `confusion_matrix.csv` – Evaluation metric
- `roc_curve.png` – ROC curve graph
- `requirements.txt` – Required libraries
2. Open notebook and run all cells OR load model:
```python
import joblib
model = joblib.load("fraud_detection_model.pkl")
data source link :https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud
