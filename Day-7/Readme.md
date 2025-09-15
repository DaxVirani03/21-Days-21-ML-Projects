Car Price Prediction 🚗💰
📌 Overview

This project builds a machine learning regression model to predict the selling price of used cars. The dataset is sourced from CarDekho, an Indian online marketplace for cars.

The model considers factors such as the car’s year of manufacture, kilometers driven, fuel type, seller type, transmission type, and ownership details to estimate its market value.

📂 Dataset

File: CAR DETAILS FROM CAR DEKHO.csv

Features include:

car_name → Car model name

year → Year of manufacture

selling_price → Price at which the car was sold (target variable)

km_driven → Kilometers driven

fuel → Fuel type (Petrol/Diesel/CNG/LPG/Electric)

seller_type → Dealer or Individual

transmission → Manual/Automatic

owner → Ownership status (First Owner, Second Owner, etc.)

⚙️ Requirements

Install dependencies:

pip install numpy pandas matplotlib seaborn scikit-learn

🚀 How to Run

Clone this repository or download the files.

Place the dataset file CAR DETAILS FROM CAR DEKHO.csv in the project directory.

Open and run the Jupyter Notebook:

jupyter notebook 178f407b-14e8-492c-a036-d1d7f92e2ab6.ipynb


The notebook includes:

Data cleaning & preprocessing (handling missing values, encoding categorical variables).

Exploratory Data Analysis (EDA).

Train-test split.

Model training (Linear Regression, Decision Trees, Random Forest, etc.).

Model evaluation (R² score, RMSE, MAE).

📊 Results

Performance is measured using R² score, Mean Absolute Error (MAE), and Root Mean Squared Error (RMSE).

Random Forest Regressor usually performs best for this dataset.

Key features influencing price: year, km_driven, fuel type, and transmission.

🔮 Future Work

Apply Hyperparameter tuning for better results.

Try advanced models like XGBoost, LightGBM, CatBoost.

Deploy as a Streamlit or Flask web app where users can input car details and get price predictions.

👨‍💻 Author

Project developed as part of Day 7 of the Machine Learning Practice Series.   
