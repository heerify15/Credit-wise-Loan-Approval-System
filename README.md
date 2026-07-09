# 💳 CreditWise – Loan Approval Prediction System

## 📌 Overview

CreditWise - Loan Approval System is a Machine Learning-based classification project that predicts whether a loan application is likely to be **approved** or **rejected** based on an applicant's financial and demographic information.

This project demonstrates an end-to-end machine learning workflow, from data preprocessing and exploratory data analysis to model training, evaluation, and comparison.

---

## ✨ Features

* Data Cleaning and Preprocessing
* Exploratory Data Analysis (EDA)
* Missing Value Imputation
* Feature Encoding
* Feature Scaling
* Binary Classification
* Model Performance Comparison
* Confusion Matrix Visualization
* Classification Report Generation

---

## 🛠️ Tech Stack

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Scikit-learn
* Jupyter Notebook

---

## 📊 Exploratory Data Analysis

The project includes comprehensive EDA to understand the dataset and identify meaningful patterns through:

* Missing Value Analysis
* Duplicate Value Detection
* Univariate Analysis
* Bivariate Analysis
* Correlation Heatmap
* Feature Distribution Visualization
* Loan Approval Distribution
* Income and Loan Amount Analysis

---

## ⚙️ Data Preprocessing

The following preprocessing techniques were applied before model training:

* Missing Value Imputation
* Label Encoding for Categorical Features
* Feature Scaling using StandardScaler
* Train-Test Split

---

## ⚙️ Feature Engineering

* Added new Features for better model performance
* Transformed features to reduce skewness & penalise heavily

---

## 🤖 Machine Learning Models

Three classification algorithms were implemented and compared:

* Logistic Regression
* K-Nearest Neighbors (KNN)
* Gaussian Naive Bayes

---

## 📈 Model Evaluation

Model performance was evaluated using:

* Accuracy
* Precision
* Recall
* F1-Score
* Classification Report
* Confusion Matrix

A comparative analysis was performed to identify the best-performing model based on classification metrics.

---

## 📁 Project Structure

Below is the layout of the repository and the naming conventions used for the project outputs:
```text
├── Dataset/
│   ├── loan_approval_data.csv
│   └── dataset_description.txt
├── Notebook/
│   └── CreditWise_LoanApproval.ipynb
├── Output/
│   ├── eda_filename.jpg          # EDA Outputs
│   ├── eval_before_filename.jpg  # ML Output (Before Feature Engineering)
│   └── eval_after_filename.jpg   # ML Output (After Feature Engineering)
└── README.md
```

---

### 🔍 Naming Conventions for the `output/` Folder:
*   **`eda_`**: Prefixed for all Exploratory Data Analysis graphs and plots.
*   **`eval_before_[filename]`**: Prefixed for Machine Learning evaluation reports and matrices generated **before** feature engineering.
*   **`eval_after_[filename]`**: Prefixed for Machine Learning evaluation reports and matrices generated **after** feature engineering.

---

## 🚀 Future Enhancements

* Model Deployment using Streamlit or Flask
* Explainable AI using SHAP or LIME

---

## 👩‍💻 Author

**Heer Shah**

Aspiring AI & Machine Learning Engineer

---

⭐ If you found this project useful, consider giving it a **Star** on GitHub!

