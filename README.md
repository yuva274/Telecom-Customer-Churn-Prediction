# Telecom Customer Churn Prediction Using Machine Learning

## Project Overview
This project analyzes telecom customer data to understand customer churn patterns and build machine learning classification models to predict customer churn.

## Objectives
- Perform Exploratory Data Analysis (EDA).
- Clean and preprocess the dataset.
- Apply feature engineering and encoding.
- Build and compare multiple machine learning models.
- Evaluate model performance using classification metrics.

## Dataset
- Total records: 243,553+
- Problem type: Binary Classification
- Target: Customer Churn

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn
- XGBoost
- Jupyter Notebook

## Machine Learning Models
1. Logistic Regression
2. Decision Tree
3. Random Forest
4. XGBoost
5. Naive Bayes
6. K-Nearest Neighbors (KNN)
7. Linear Support Vector Classifier (Linear SVC)

## Model Evaluation
Models were compared using:
- Accuracy
- Precision
- Recall
- F1-Score
- ROC-AUC

XGBoost was selected based on the comparative evaluation. However, the models showed limited ability to identify churn customers, highlighting the impact of class imbalance.

## Future Improvements
- Apply SMOTE or other resampling techniques.
- Use class-weighted models.
- Tune classification thresholds.
- Improve minority-class recall and F1-score.

## Author
Yuvasree M
