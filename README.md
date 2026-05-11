# Diabetes Prediction Analysis

This project explores whether type 2 diabetes can be predicted using simple clinical measurements from the Pima Indians Diabetes dataset. The goal is to build a clean, reproducible machine learning pipeline for preprocessing, modeling, and evaluating classification models.

## Highlights
- Full scikit-learn pipeline with preprocessing, scaling, and modeling steps.
- Comparison of Logistic Regression and Random Forest.
- Strong evaluation using Accuracy, Recall, F1-score, ROC Curve, and Cross Validation.
- Feature importance analysis to identify key predictors.

## Dataset
**Pima Indians Diabetes**  
Source: UCI Machine Learning Repository

Features include glucose levels, BMI, blood pressure, insulin, pregnancies, age, and diabetes pedigree function.

Target variable:
- 0: Non-diabetic
- 1: Diabetic

## Project Workflow

### 1. Exploratory Data Analysis (EDA)
- Distribution analysis with KDE and histograms
- Correlation heatmap
- Boxplots and scatter plots for clinical insight
- Identification of missing or medically unrealistic values

### 2. Preprocessing
- Train-test split
- Missing value imputation
- Feature scaling
- Reproducible scikit-learn Pipeline setup

### 3. Modeling
Models trained and compared:
- Logistic Regression
- Random Forest Classifier

### 4. Evaluation Metrics
- Accuracy
- Precision
- Recall
- F1-score
- Confusion Matrix
- ROC Curve and AUC
- Cross Validation for model stability

## Key Findings
- Logistic Regression and Random Forest perform similarly overall.
- Random Forest achieves slightly higher accuracy.
- Logistic Regression shows competitive AUC performance.
- Models struggle with detecting true diabetic cases due to dataset limitations.
- Feature importance reveals glucose, BMI, and age as primary contributors.

## Technologies Used
- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

## Limitations
- Small dataset size
- Class imbalance reduces Recall
- Only two models evaluated
- No hyperparameter tuning yet

## Future Improvements
- Add Gradient Boosting or SVM
- Apply hyperparameter tuning
- Handle class imbalance
- Use larger or more diverse datasets

## Medical Disclaimer
This model is for educational and analytical purposes only and is not suitable for medical diagnosis or clinical decision making.

## References
- UCI Machine Learning Repository  
- Scikit-learn Documentation  
- Pandas Documentation  
- Matplotlib Documentation  
- Seaborn Documentation

