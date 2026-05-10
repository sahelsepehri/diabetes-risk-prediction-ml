# Diabetes Risk Prediction Using Machine Learning

## Project Overview

This project explores how machine learning models can be used to predict diabetes using basic clinical measurements.
The goal is to build a clear and reproducible machine learning workflow including data cleaning, preprocessing, model training, and evaluation.

Three classification models were implemented and compared to understand how well they can identify patients at risk of diabetes.

---

## Dataset

This project uses the **Pima Indians Diabetes Dataset** from the UCI Machine Learning Repository.

### Dataset Characteristics

- 768 patient records  
- 8 clinical features:
  - Pregnancies
  - Glucose
  - BloodPressure
  - SkinThickness
  - Insulin
  - BMI
  - DiabetesPedigreeFunction
  - Age

### Target Variable

- `0` = No Diabetes  
- `1` = Diabetes  

---

## Research Questions

This project investigates the following questions:

- Can machine learning models predict diabetes using basic clinical measurements?
- Which physiological features are the most important predictors of diabetes?
- Which model performs better on this dataset?
- How well can the models identify true diabetes cases?

---

## Methods

The following steps were implemented:

- Data cleaning and handling medically invalid values
- Exploratory Data Analysis (EDA)
- Building a preprocessing pipeline (imputation and feature scaling)
- Training multiple classification models
- Model evaluation using:
  - Accuracy
  - Precision
  - Recall
  - F1-score
  - ROC-AUC
  - Confusion Matrix
- Cross-validation for model stability
- Model interpretability using feature importance

---

## Models

The following machine learning models were trained and evaluated:

- Logistic Regression  
- Random Forest  
- Support Vector Machine (SVM)

---

## Results

The models showed comparable performance on this dataset. Random Forest achieved slightly better overall performance, but all models had difficulty identifying all positive diabetes cases, reflected in relatively low recall values.

This highlights an important challenge in medical prediction tasks: minimizing missed diagnoses.

---

## Project Structure
```text
diabetes-risk-prediction-ml
│
├── data
│   └── pima_diabetes.xlsx
│
├── diabetes_prediction.ipynb
├── requirements.txt
└── README.md
