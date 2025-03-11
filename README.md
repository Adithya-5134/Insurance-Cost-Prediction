# 🌟 Insurance Cost Prediction 🚀

## 📌 Project Overview
Welcome to the **Insurance Cost Prediction** project! This machine learning model predicts insurance charges based on various factors such as age, BMI, smoking habits, gender, dependents, and region.


## 📂 Dataset Information
- **📄 File:** Insurance.csv
- **📊 Features:**
  - 🏆 age: Age of the insured individual
  - 👫 sex: Gender of the insured individual
  - ⚖️ bmi: Body Mass Index
  - 👶 children: Number of children covered by insurance
  - 🚬 smoker: Smoking status (yes/no)
  - 🌍 region: Residential region of the insured individual
  - 💰 charges: Insurance charges (Target Variable)

## 🔍 Model Implementation

- **📜 File:** INSURANCE_COST_PREDICTION_final.ipynb
- 
- **🛠️ Steps Followed:**
- 
  1. 🏗️ **Data Preprocessing** - Handling missing values, encoding categorical data

  2. 📊 **Exploratory Data Analysis (EDA)** - Identifying correlations and distributions

  3. 🤖 **Model Selection** - Training different regression models

  4. 📈 **Model Evaluation** - Comparing accuracy and performance metrics

## 🤖 Models Used

- 🔹 **Linear Regression**
  
- 🔹 **Decision Tree Regressor**
  
- 🔹 **Random Forest Regressor**
  
- 🔹 **Gradient Boosting Regressor**
  
- 🔹 **XGBoost Regressor**
  
- 🔹 **K-Nearest Neighbors (KNN) Regressor**


## 📉 Metrics Used

- 📌 **R² Score**
  
- 📌 **Mean Absolute Error (MAE)**
  
- 📌 **Mean Squared Error (MSE)**

- 📌 **Root Mean Squared Error (RMSE)**

## 🔍 Hyperparameter Tuning & Optimization
- Used **GridSearchCV** and **RandomizedSearchCV** for fine-tuning model hyperparameters.
- Applied **cross-validation** techniques to improve model generalization.

## 🔑 Key Insights
- 🚬 **Smoking** has a significant impact on insurance costs, with smokers being charged much higher.
- 📈 **BMI and Age** also strongly influence the predicted cost.
- 🌍 **Region** has minimal effect on insurance costs compared to other factors.

## 🎯 Conclusion
This project successfully predicts insurance charges using multiple regression models. The **Random Forest Regressor** performed the best among the models tested. The findings highlight that smoking, BMI, and age are crucial factors in determining insurance costs.


