# 💰 Salary Prediction Project

## 📌 Overview
This project aims to predict employee salaries based on features such as experience, education level, job title, gender, country, and race using Machine Learning regression models.

The project demonstrates data preprocessing, feature engineering, model training, evaluation, and model comparison.

---

## 🎯 Objective
Build a regression model to accurately estimate salaries and identify the key factors affecting compensation.

---

## 📊 Dataset Features
- Age
- Gender
- Education Level
- Job Title
- Years of Experience
- Country
- Race
- Salary (Target Variable)

---

## 🛠️ Project Workflow

1. Data Cleaning
   - Removed duplicates
   - Handled missing values
   - Removed unnecessary columns

2. Data Preprocessing
   - Grouped similar job titles
   - Encoded categorical features (One-Hot Encoding)
   - Outlier handling
   - Feature scaling

3. Model Training
   - Single Feature Linear Regression
   - Multiple Linear Regression
   - Ridge Regression

4. Model Evaluation
   - RMSE (Root Mean Squared Error)
   - R² Score

---

## 📈 Results
Linear Regression provided a strong baseline model.  
However, due to non-linear relationships in salary data, tree-based models such as Decision Tree and Random Forest are expected to achieve better performance.

---

## 🚀 Future Improvements
- Apply Decision Tree & Random Forest
- Hyperparameter tuning
- Feature importance analysis
- Deploy model using Streamlit or Flask

---

## 🧠 Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib / Seaborn
