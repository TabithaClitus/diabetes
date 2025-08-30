🩺 Diabetes Prediction using XGBoost

This project builds a machine learning model to predict the likelihood of diabetes in patients based on health data.
It uses XGBoost Classifier for training and evaluation, and a Streamlit web app for interactive prediction.

📂 Dataset

The dataset used is the Pima Indians Diabetes Dataset (commonly used for diabetes prediction tasks).

Rows: 768

Columns: 9 (8 features + 1 target)

Target variable: Outcome

0 → No Diabetes

1 → Diabetes

Features:
Feature	Description
Pregnancies	Number of times pregnant
Glucose	Plasma glucose concentration
BloodPressure	Diastolic blood pressure (mm Hg)
SkinThickness	Triceps skinfold thickness (mm)
Insulin	2-Hour serum insulin (mu U/ml)
BMI	Body Mass Index (weight in kg/(height in m)^2)
DiabetesPedigreeFunction	Diabetes pedigree function (genetic risk)
Age	Age in years
Outcome	Class variable (0: Non-diabetic, 1: Diabetic)

🚀 Model Training

The model is trained using XGBoost Classifier with cross-validation and hyperparameter tuning.

Steps:

Data preprocessing (handle imbalance, clean outliers if needed).

Train XGBoost with tuned hyperparameters (max_depth, learning_rate, n_estimators).

Evaluate using Accuracy, Precision, Recall, F1-score, ROC-AUC.

Save trained model as pickle file (diabetes_model.pkl).

📊 Example Results

Accuracy: ~74%

Precision: ~65%

Recall: ~57%

F1-score: ~61%

ROC-AUC: ~0.81

