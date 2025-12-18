Predicts students’ career paths using academic scores, study habits, extracurriculars, and part-time jobs with machine learning.

Dataset:
Features: gender, part_time_job, absence_days, extracurricular_activities, weekly_self_study_hours, subject scores (math, history, physics, chemistry, biology, english, geography)
Target: career_aspiration (e.g., Doctor, Lawyer, Software Engineer)

Preprocessing:

Dropped irrelevant columns

Created total_score & average_score

Encoded categorical features

Balanced dataset using SMOTE

Modeling:

Train-test split: 80-20

Feature scaling: StandardScaler

Models: Logistic Regression, SVC, Random Forest, KNN, Decision Tree, Naive Bayes, AdaBoost, Gradient Boosting, XGBoost

Best model: Random Forest (Accuracy: 82%)

Usage:

Clone the repo

Install dependencies: pandas, scikit-learn, xgboost, imblearn

Run main.py or the notebook to train/test models
