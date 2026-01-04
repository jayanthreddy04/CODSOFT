# 🏦 Bank Customer Churn Prediction

## 📌 Overview
Customer churn is a major challenge for banks and subscription-based businesses.  
This project predicts whether a customer is likely to **leave the bank (churn)** or **stay**, using machine learning and historical customer data.

The project includes a trained ML model, a Streamlit-based web application, and well-documented evaluation metrics.

---

## 🎯 Problem Statement
To build a machine learning model that predicts customer churn based on demographic and banking-related features and deploy it as an interactive web application.

---

## 🚀 Features
- Real-time customer churn prediction
- Churn probability estimation
- Explainable churn reasons
- Clean and modern Streamlit UI
- Separate documentation for model evaluation metrics

---

## 🧠 Machine Learning Model
- Algorithm: Logistic Regression  
- Problem Type: Binary Classification  
- Target Variable: `Exited`  
  - `1` → Customer Churned  
  - `0` → Customer Stayed  

---

## 📊 Input Features
- Credit Score  
- Geography  
- Gender  
- Age  
- Tenure (Years)  
- Account Balance  
- Number of Products  
- Has Credit Card  
- Is Active Member  
- Estimated Salary  

---

## 🔍 Churn Explainability
The application explains churn predictions using strong contributing factors such as:
- Low credit score  
- Short customer tenure  
- Inactive membership  
- Limited product usage  
- High churn region (Germany)  
- Higher churn observed in older age groups  

This improves transparency and business interpretability.

---

## 📊 Model Metrics
Model evaluation metrics are documented separately.

See detailed metrics here:  
metrics/model_metrics.md

---

## 🛠 Tech Stack
- Python  
- Pandas, NumPy  
- Scikit-learn  
- Streamlit  
- Pickle / Joblib  

---

## 📁 Project Structure
customer_churn_app/
│
├── data/
│ └── churn.csv
│
├── model/
│ └── churn_model.pkl
│
├── metrics/
│ └── model_metrics.md
│
├── train_model.py
├── app.py
├── requirements.txt
└── README.md



## ▶️ How to Run the Project

### Step 1: Install Dependencies
pip install requirements.txt

### Step 2: Run the Application
streamlit run streamlit_app.py

### Step 3: Open in Browser
http://localhost:8501



## 🖥️ Application Output
- Customer is likely to STAY or CHURN
- Churn probability percentage
- Clear explanation of churn reasons

---

## 📈 Future Enhancements
- Improve recall using Random Forest or Gradient Boosting
- Handle class imbalance more effectively
- Add ROC–AUC evaluation
- Deploy the application on Streamlit Cloud
- Enhance UI with visual analytics
