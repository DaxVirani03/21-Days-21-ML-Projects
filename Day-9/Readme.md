This project builds a machine learning classification model to predict the likelihood of heart disease in a patient based on medical attributes such as age, sex, cholesterol levels, and resting blood pressure.

Early detection of heart disease is critical in healthcare, and machine learning provides a useful tool to assist in risk assessment.

📂 Dataset

File: heart_disease_data.csv

Shape: ~303 rows × 14 columns

Features include:

age → Patient age in years

sex → Gender (1 = male, 0 = female)

cp → Chest pain type (0–3)

trestbps → Resting blood pressure (mm Hg)

chol → Serum cholesterol (mg/dl)

fbs → Fasting blood sugar > 120 mg/dl (1 = true, 0 = false)

restecg → Resting ECG results (0–2)

thalach → Maximum heart rate achieved

exang → Exercise induced angina (1 = yes, 0 = no)

oldpeak → ST depression induced by exercise

slope → Slope of peak exercise ST segment

ca → Number of major vessels (0–3) colored by fluoroscopy

thal → Thalassemia (0–3)

Target column: target (1 = heart disease, 0 = no heart disease)

⚙️ Requirements

Install dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the files.

Place the dataset file heart_disease_data.csv in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook 9th.ipynb


The notebook includes:

Data preprocessing (handling missing values, feature scaling).

Exploratory Data Analysis (EDA).

Train-test split.

Model training (Logistic Regression, Decision Tree, Random Forest, KNN, SVM).

Model evaluation (Accuracy, Precision, Recall, F1-score, ROC-AUC).

📊 Results

Best performing models: Logistic Regression / Random Forest (~80–85% accuracy).

Key predictors: chest pain type (cp), maximum heart rate (thalach), ST depression (oldpeak), and cholesterol (chol).

🔮 Future Work

Apply hyperparameter tuning (GridSearchCV, RandomizedSearchCV).

Use ensemble learning methods (XGBoost, LightGBM).

Deploy as a Streamlit healthcare prediction web app.

Extend with real-world patient data for clinical applications.

👨‍💻 Author

Project developed as part of Day 9 of the Machine Learning Practice Series. 
