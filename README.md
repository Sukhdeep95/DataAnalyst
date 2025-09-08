# 🛒 Inventory Demand Forecasting

This project aims to predict future product demand using historical sales data. It uses time-series and contextual features to train a machine learning model that helps optimize inventory planning for retail stores.

---

## 📊 Dataset

The dataset contains daily sales data for multiple stores and items over several years.

### Sample Columns:
- `date`: Date of the transaction
- `store`: Store ID
- `item`: Item ID
- `sales`: Number of items sold
- `year`, `month`, `day`: Extracted from the `date`
- `weekend`: Indicates if the day was a weekend
- `holidays`: Binary flag for holidays
- `m1`, `m2`: Additional engineered features (moving averages, etc.)

---

## 📌 Objectives

- Forecast daily sales for each item at each store
- Identify trends and patterns in sales
- Evaluate performance of various time-series forecasting techniques

---

## 🧠 Machine Learning Models Used

- Linear Regression
- Random Forest Regressor
- XGBoost
- ARIMA / SARIMA (if applicable)
- LSTM (if using deep learning)

---

## 🔧 Technologies

- Python
- Pandas & NumPy
- Matplotlib & Seaborn
- Scikit-learn
- XGBoost / LightGBM
- Jupyter Notebook

---



## 🚀 How to Run

1. Clone this repo:
   ```bash
   git clone https://github.com/Sukhdeep95/DataAnalyst.git
