# Titanic Survival Prediction
Predicting passenger survival on the Titanic using machine learning and feature engineering.

# Overview
This project uses the Titanic dataset to build a predictive model for passenger survival. It demonstrates a complete machine learning pipeline — from data preprocessing and feature engineering to model training, evaluation, and deployment.

# Project Structure
notebook.ipynb: Main Jupyter notebook containing all code, analysis, and results

submission.csv: Final predictions for the test set, ready for Kaggle submission

README.md: Project documentation

# Features Engineered
FamilySize: Total number of family members aboard (SibSp + Parch + 1)

IsAlone: Binary feature indicating if the passenger was traveling alone

# Model Used
Random Forest Classifier from scikit-learn

Hyperparameter tuning via GridSearchCV

Evaluation using Stratified K-Fold Cross-Validation

# Performance
Cross-validated accuracy: Reported in notebook

Best parameters: Selected via grid search

# Deployment
Predictions were generated on the test set and exported to submission.csv, simulating a real-world deployment pipeline for batch inference.





