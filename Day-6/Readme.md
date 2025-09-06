Wine Quality Prediction 🍷
📌 Overview

This project aims to predict the quality of red wine using machine learning models. The dataset contains various physicochemical properties (like acidity, sugar, pH, alcohol content) of red wine, along with a quality score rated between 0 and 10.

The goal is to analyze the data, build models, and evaluate how well machine learning can predict wine quality.

📂 Dataset

File: winequality-red.csv

Shape: 1599 rows × 12 columns

Features include:

fixed acidity

volatile acidity

citric acid

residual sugar

chlorides

free sulfur dioxide

total sulfur dioxide

density

pH

sulphates

alcohol

Target column: quality (integer score 0–10, usually between 3–8)

⚙️ Requirements

Install required dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the files.

Place the dataset file winequality-red.csv in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook 6th.ipynb


The notebook includes:

Data preprocessing and cleaning

Exploratory Data Analysis (EDA) with visualizations

Feature selection & scaling

Train-test split

Model training (Logistic Regression, Decision Trees, Random Forest, etc.)

Model evaluation (Accuracy, Precision, Recall, F1-score if classification / RMSE, R² if regression)

📊 Results

Models are evaluated on prediction performance.

Random Forest and Gradient Boosting often perform best.

Feature importance usually highlights alcohol, volatile acidity, sulphates, and citric acid as the most significant predictors.

🔮 Future Work

Try advanced ensemble methods (XGBoost, LightGBM, CatBoost).

Balance classes for classification (since quality distribution is imbalanced).

Deploy as a wine quality prediction web app.

👨‍💻 Author

Project developed as part of Day 6 of the Machine Learning Practice Series.
