# Breast Cancer Prediction using Logistic Regression

This project aims to predict whether a tumor is malignant or benign using the Breast Cancer Wisconsin (Diagnostic) Dataset. The prediction is based on features computed from digitized images of a fine needle aspirate (FNA) of a breast mass.

## 📁 Dataset

The dataset used in this project is available on [Kaggle](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data) and includes the following:

- **ID**: Unique identifier for each patient record.
- **Diagnosis**: 'M' = Malignant, 'B' = Benign (target variable).
- **30 features**: Mean, standard error, and "worst" (largest) values for various measurements like:
  - Radius
  - Texture
  - Perimeter
  - Area
  - Smoothness
  - Compactness
  - Concavity
  - Symmetry
  - Fractal dimension

## 🔍 Objective

To build a **logistic regression model** that accurately classifies breast tumors as benign or malignant based on the input features.


## 🛠️ Technologies Used

- Python 3.x
- Pandas
- NumPy
- Matplotlib / Seaborn (for visualization)
- Scikit-learn (for model building and evaluation)
- Jupyter Notebook

## 📈 Model

The model used is **Logistic Regression**:
- Trained on standardized input features.
- Evaluated using accuracy, confusion matrix, precision, recall, and F1-score.

## ✅ Results

- The logistic regression model achieved high accuracy on the test set.
- The dataset is well-balanced and suitable for binary classification.



