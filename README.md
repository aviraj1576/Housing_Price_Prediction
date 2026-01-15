# 🏠 Housing Price Prediction using Machine Learning

## 📌 Project Overview
This project implements an **end-to-end machine learning pipeline** to predict **median house prices** using structured housing data.  
It covers the complete workflow from **data preprocessing and feature engineering** to **model training, evaluation, and inference**.

The goal of this project is to gain hands-on experience with **real-world ML pipelines**, including handling numerical and categorical features, stratified sampling, and model persistence.

---

## 🧠 Key Concepts Used
- Data preprocessing and cleaning
- Stratified train-test splitting
- Feature engineering
- Pipeline-based transformations
- Supervised learning (regression)
- Model evaluation using RMSE
- Model persistence using `joblib`

---

## 🛠️ Technologies & Libraries
- **Python**
- **pandas**, **NumPy**
- **scikit-learn**
- **RandomForestRegressor**
- **Pipeline & ColumnTransformer**
- **Joblib**

---

## 📂 Project Structure
projectX/
- │
- ├── housing.csv # Original dataset
- ├── input.csv # Test data for inference
- ├── output.csv # Model predictions
- ├── main.py # Training & inference pipeline
- ├── .gitignore 
- ├── README.md # Project documentation


---

## 🔄 Workflow Explanation

### 1️⃣ Data Preparation
- Loaded housing dataset
- Created an **income category** feature
- Used **StratifiedShuffleSplit** to maintain income distribution
- Separated features and labels

### 2️⃣ Data Preprocessing Pipeline
- Numerical features:
  - Median imputation
  - Standard scaling
- Categorical features:
  - One-hot encoding
- Combined using **ColumnTransformer**

### 3️⃣ Model Training
- Trained a **Random Forest Regressor**
- Evaluated performance using **cross-validation (RMSE)**

### 4️⃣ Model Persistence
- Saved trained model and preprocessing pipeline using `joblib`

### 5️⃣ Inference
- Loaded saved model and pipeline
- Generated predictions on unseen data
- Saved results to `output.csv`

---

## ▶️ How to Run the Project

### Step 1: Clone the repository
- Navigate to the favourable folder and run following commands in terminal
- git init
- git clone https://github.com/aviraj1576/Housing_Price_Prediction.git

### Step 2: Installing Dependencies

pip install pandas numpy scikit-learn


### Step 3: Train the model

python main.py

---

## Learning Outcomes
- Built a complete ML pipeline from scratch
- Gained experience with reusable preprocessing pipelines
- Learned how to persist and reuse trained models

---

## Author - Aviraj Singh

