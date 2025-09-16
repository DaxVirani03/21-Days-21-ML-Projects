Gold Price Prediction
📌 Project Overview

This project aims to predict the price of Gold (GLD) using historical market data. By leveraging machine learning regression models, we identify patterns in financial indicators (such as SPX, USO, SLV, and EUR/USD) to forecast gold prices.

📂 Dataset

File: gld_price_data.csv

Features:

Date → Timestamp of the record

SPX → S&P 500 Index value

USO → United States Oil Fund price

SLV → Silver price

EUR/USD → Euro to Dollar exchange rate

GLD → Gold ETF price (target variable)

🛠️ Technologies Used

Python 🐍

Pandas, NumPy → Data preprocessing

Matplotlib, Seaborn → Data visualization

Scikit-learn → Model building & evaluation

Jupyter Notebook

🔑 Steps Performed

Data Preprocessing

Handled missing values

Converted dates & dropped unused columns

Train-test split

Exploratory Data Analysis (EDA)

Correlation heatmaps

Trend visualization of features vs. gold price

Model Building

Implemented Random Forest Regressor

Compared with Linear Regression (optional)

Hyperparameter tuning for better performance

Evaluation Metrics

Mean Absolute Error (MAE)

Mean Squared Error (MSE)

R² Score

📊 Results

Random Forest achieved high accuracy in predicting gold prices

Strong positive correlation observed between GLD and SLV

🚀 Future Improvements

Include more macroeconomic indicators (e.g., inflation, interest rates)

Try advanced models like XGBoost, LSTM (for time series forecasting)

Deploy as a web app (Flask/Streamlit + React for UI)
