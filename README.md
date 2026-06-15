# Telco Customer Churn Prediction Pipeline

## Objective
The objective of this task is to build a reusable and production-ready machine learning pipeline for predicting customer churn.

## Dataset
Telco Customer Churn Dataset.

## Methodology
1. Loaded the Telco Churn dataset.
2. Removed customerID because it is only an identifier.
3. Converted TotalCharges into numeric format.
4. Converted Churn target column into binary values.
5. Applied preprocessing using Scikit-learn Pipeline.
6. Used ColumnTransformer for numerical and categorical columns.
7. Trained Logistic Regression and Random Forest models.
8. Used GridSearchCV for hyperparameter tuning.
9. Evaluated the best model using accuracy, precision, recall, and F1-score.
10. Exported the complete pipeline using joblib.

## Technologies Used
- Python
- Google Colab
- Pandas
- NumPy
- Scikit-learn
- Joblib

## Results
The final model was evaluated using:
- Accuracy
- Precision
- Recall
- F1-score

## Final Summary
This project demonstrates how to build an end-to-end machine learning pipeline for customer churn prediction using Scikit-learn.
