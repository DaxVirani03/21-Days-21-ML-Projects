Diabetes Prediction using Machine Learning
📌 Overview

This project focuses on building a machine learning model to predict whether a patient has diabetes, based on diagnostic medical measurements. The model is trained on the Pima Indians Diabetes Dataset, which contains health-related attributes such as glucose level, blood pressure, BMI, and age.

The objective is to use supervised learning to predict the outcome (1 = Diabetes, 0 = No Diabetes).

📂 Dataset

File: diabetes data.csv

Shape: 768 rows × 9 columns

Features include:

Pregnancies

Glucose

BloodPressure

SkinThickness

Insulin

BMI

DiabetesPedigreeFunction

Age

Target column: Outcome (0 = Non-diabetic, 1 = Diabetic)

⚙️ Requirements

Install the required dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the files.

Place the dataset file diabetes data.csv in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook 2nd.ipynb


The notebook covers:

Data loading & cleaning

Exploratory Data Analysis (EDA)

Feature scaling & preprocessing

Train-test split

Model training (Logistic Regression, Random Forest, SVM, etc.)

Model evaluation (accuracy, confusion matrix, recall, precision, F1-score)

📊 Results

The models are evaluated using multiple metrics. Typical performance:

Accuracy: ~70–80%

Logistic Regression and Random Forest generally perform well.

🔮 Future Work

Use hyperparameter tuning (GridSearchCV / RandomizedSearchCV).

Try ensemble methods (XGBoost, LightGBM).

Balance the dataset with SMOTE to handle class imbalance.

Deploy as a web app for real-world prediction.

👨‍💻 Author

Project developed as part of Day 2 of the Machine Learning Practice Series.
