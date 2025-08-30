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

VISUALIZATION:

<img width="540" height="393" alt="image" src="https://github.com/user-attachments/assets/e95ad837-74f0-4583-ac1f-d5d9f0c59482" />

<img width="924" height="695" alt="image" src="https://github.com/user-attachments/assets/07ddf8ee-1bf6-4c30-8a2d-20c6d40337aa" />

<img width="686" height="470" alt="image" src="https://github.com/user-attachments/assets/0379c83b-feb7-4f43-8c07-ced22009e886" />

<img width="1005" height="547" alt="image" src="https://github.com/user-attachments/assets/7008644e-02ac-4f9b-974b-03361dcb272a" />

<img width="996" height="547" alt="image" src="https://github.com/user-attachments/assets/46029980-ba1e-4ede-8a10-a0506a0690af" />

<img width="536" height="547" alt="image" src="https://github.com/user-attachments/assets/34c6d2d6-df74-4c93-938e-8b9f18184e1e" />






