Bengaluru House Price Prediction 🏠
📌 Overview

This project aims to build a machine learning regression model that predicts house prices in Bengaluru based on various property features such as location, number of bedrooms, bathrooms, and total square footage.

The dataset contains housing details scraped from online real-estate platforms. The goal is to preprocess the data, handle outliers, and train regression models to estimate house prices.

📂 Dataset

File: Bengaluru_House_Data.csv

Features include:

location – Location of the property

size – Number of bedrooms (e.g., 2 BHK, 4 Bedroom)

total_sqft – Total area in square feet

bath – Number of bathrooms

price – Price of the property (target variable, in lakhs)

⚙️ Requirements

Install the required Python libraries:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the files.

Place the dataset file Bengaluru_House_Data.csv in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook 3rd.ipynb


The notebook covers:

Data loading & cleaning

Feature engineering (converting categorical → numerical, handling missing values)

Outlier removal

Dimensionality reduction (if applicable)

Model training (Linear Regression, Decision Trees, Random Forest, etc.)

Model evaluation (R² score, Mean Squared Error, etc.)

📊 Results

The models are evaluated using regression metrics:

R² Score → Measures goodness of fit

Mean Squared Error (MSE) → Lower is better

Root Mean Squared Error (RMSE) → Provides error in same units as price

Typical performance:

R² Score ~ 0.80–0.85 (depending on preprocessing and model choice).

🔮 Future Work

Use advanced models like XGBoost, LightGBM, CatBoost.

Deploy as a Flask/Streamlit web app where users can input features and get predicted house prices.

Add more feature engineering (distance to city center, amenities, etc.) for better predictions.

👨‍💻 Author

Project developed as part of Day 3 of the Machine Learning Practice Series.
