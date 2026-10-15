# Explainable AI-Based Personalized Health Risk Assessment System

## About the Project

This project is an Explainable AI-based health risk assessment system that predicts an individual's overall health risk as **High Risk** or **Low Risk** using physical, lifestyle, and behavioural parameters.

The system compares five machine learning algorithms: Logistic Regression, Random Forest, XGBoost, LightGBM, and CatBoost. CatBoost is selected as the final prediction model based on its performance.

To improve interpretability, **SHAP (SHapley Additive exPlanations)** is used to identify the factors contributing to individual predictions. The system also provides personalized general wellness recommendations based on the user's characteristics and contributing risk factors.

The project demonstrates how machine learning, explainable AI, and personalized recommendations can be integrated into a unified health risk assessment framework.

## Key Features

- Overall health risk classification (High Risk / Low Risk)
- Comparison of five machine learning models
- Model evaluation using accuracy, precision, recall, F1-score, and ROC-AUC
- SHAP-based global and individual prediction explanations
- Personalized general wellness recommendations

## Technologies Used

- Python
- Pandas and NumPy
- Scikit-learn
- XGBoost
- LightGBM
- CatBoost
- SHAP
- Jupyter Notebook

## Dataset

The project uses a synthetically generated health and lifestyle dataset containing physical, demographic, and behavioural features.

**Note:** This system is intended for general health awareness and research purposes. It does not diagnose diseases or replace professional medical advice. Since the current experiments use synthetic data, the results do not establish clinical validity.

## Future Scope

Future work may include validation using real-world health datasets, disease-specific risk prediction, and integration of a generative AI-based assistant for more interactive explanations and recommendations.
