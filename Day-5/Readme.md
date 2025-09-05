Loan Approval Prediction 💳
📌 Overview

This project builds a machine learning classification model to predict whether a loan application will be approved based on applicant information such as gender, marital status, income, loan amount, and credit history.

The task is a binary classification problem:

Y → Loan Approved

N → Loan Not Approved

📂 Dataset - https://www.kaggle.com/datasets/ninzaami/loan-predication

File: train_u6lujuX_CVtuZ9i (1).csv

Rows: ~614 entries

Columns include:

Loan_ID → Unique loan identifier

Gender → Male/Female

Married → Applicant’s marital status

Dependents → Number of dependents

Education → Graduate/Not Graduate

Self_Employed → Yes/No

ApplicantIncome → Income of the applicant

CoapplicantIncome → Income of the co-applicant

LoanAmount → Loan amount (in thousands)

Loan_Amount_Term → Loan term (in days)

Credit_History → 1.0 (meets guidelines) / 0.0 (does not meet)

Property_Area → Urban/Semiurban/Rural

Loan_Status → Target variable (Y = Approved, N = Not Approved)

⚙️ Requirements

Install the required dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the files.

Place the dataset train_u6lujuX_CVtuZ9i (1).csv in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook Day-5.ipynb


The notebook includes:

Data loading & preprocessing (handling missing values, encoding categorical data).

Exploratory Data Analysis (EDA).

Splitting dataset into training and testing sets.

Model training (Logistic Regression, Decision Trees, Random Forest, KNN, etc.).

Model evaluation (accuracy, precision, recall, F1-score).

📊 Results

Models are evaluated on accuracy and classification reports.

Logistic Regression and Random Forest usually achieve the best performance (~75–80% accuracy).

🔮 Future Work

Use hyperparameter tuning (GridSearchCV, RandomizedSearchCV).

Apply SMOTE to balance loan approval data.

Try advanced ensemble methods like XGBoost, LightGBM.

Deploy as a web application for real-time loan approval prediction.

👨‍💻 Author

Project developed as part of Day 5 of the Machine Learning Practice Series.
