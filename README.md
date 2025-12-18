Student Career Prediction System
Overview

Predicts students’ career paths based on academic scores, study habits, extracurricular activities, and part-time jobs using machine learning.

Dataset

Features: gender, part_time_job, absence_days, extracurricular_activities, weekly_self_study_hours, subject scores (math, history, physics, chemistry, biology, english, geography)

Target: career_aspiration (e.g., Doctor, Lawyer, Software Engineer)

Preprocessing

Dropped irrelevant columns: id, first_name, last_name, email

Created total_score and average_score

Encoded categorical features

Balancing Dataset

Applied SMOTE to handle class imbalance

Model Training

Train-test split: 80-20

Feature scaling: StandardScaler

Models used: Logistic Regression, SVC, Random Forest, KNN, Decision Tree, Naive Bayes, AdaBoost, Gradient Boosting, XGBoost

Results

Random Forest Classifier achieved the best accuracy: 82%

Usage

Clone the repo

Install dependencies (pandas, scikit-learn, xgboost, imblearn)

Run main.py (or your Jupyter notebook) to train and test models
