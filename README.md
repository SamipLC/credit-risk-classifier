# Credit Risk Classifier

## Overview
A logistic‐regression based credit‐risk pipeline built in Python.  
This project generates synthetic borrower data, applies feature engineering and scaling, tunes hyperparameters with `GridSearchCV`, and evaluates performance via 5-fold cross-validation.

## TECHNIQUES USED
- **Synthetic data generation** with `make_classification`
- **Feature engineering** (creating realistic borrower features)
- **Data scaling** using `StandardScaler`
- **Model training** with `LogisticRegression`
- **Hyperparameter tuning** via `GridSearchCV`
- **Evaluation** using **5-fold cross-validation**

## Requirements
- Python 3.7 or higher  
- pandas  
- numpy  
- scikit-learn  

## Install Dependencies
```bash
pip install -r requirements.txt
