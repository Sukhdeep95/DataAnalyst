# 📊 Customer Churn Analysis and Prediction

This project focuses on analyzing and predicting customer churn using machine learning techniques. The goal is to identify patterns and behaviors that lead to churn and use those insights to help reduce customer attrition in the telecom industry.

---

## 📁 Project Structure

This project resides in the `customer-churn` branch of the `DataAnalyst` repository.

- `Customer_churn_.predictionipynb` — Main Jupyter notebook for data analysis and model building
- `Telco-Customer-churn` — Dataset used for analysis 

---

## 📌 Objective

To build a machine learning model that predicts whether a customer will **churn (leave the service)** based on their attributes like internet service, contract type, payment method, etc.

---

## 📊 Dataset Overview

The dataset contains the following customer attributes:

| Column | Description |
|--------|-------------|
| `customerID` | Unique ID of the customer |
| `gender` | Male / Female |
| `SeniorCitizen` | 1 = Yes, 0 = No |
| `Partner` | Whether the customer has a partner |
| `Dependents` | Whether the customer has dependents |
| `tenure` | Number of months the customer has stayed |
| `PhoneService` | Yes / No |
| `MultipleLines` | Multiple phone lines |
| `InternetService` | DSL, Fiber optic, No |
| `OnlineSecurity`, `OnlineBackup`, `DeviceProtection`, etc. | Various services used |
| `Contract` | Month-to-month, One year, Two year |
| `PaymentMethod` | Electronic check, Mailed check, etc. |
| `MonthlyCharges` | Monthly bill amount |
| `TotalCharges` | Total amount billed |
| `Churn` | Yes = Churned, No = Stayed |

---

## 🔍 Key Steps in the Notebook

1. **Data Preprocessing**
   - Handling missing values
   - Encoding categorical variables

2. **Exploratory Data Analysis (EDA)**
   - Churn distribution
   - Service usage patterns

3. **Model Building**
   - Random Forest Classifier
   - Model evaluation using accuracy_score function,precision, recall and accuracy using a confusion matrix

4. **Prediction**
   - Predicting churn probability for new customers

---

## 🧠 ML Techniques Used

- **Train-Test Split**
- **Label Encoding**
- **Random Forest Classifier
- **Confusion Matrix and Accuracy Score**

---


