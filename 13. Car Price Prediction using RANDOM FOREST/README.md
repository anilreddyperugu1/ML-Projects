# 🚗 Car Price Prediction using Random Forest

A machine learning project to predict the selling price of used cars using the Random Forest Regressor. The model leverages historical car data to provide accurate and reliable price estimates for informed decision-making. Let's dive in 🚀

---

## 📑 Index
1. [📌 Project Overview](#-project-overview)  
2. [🎯 Problem Statement](#-problem-statement)  
3. [🧠 Key Features & Terminologies](#-key-features--terminologies)  
4. [⚙️ Workflow Summary](#️-workflow-summary)   
5. [📊 Model Evaluation](#-model-evaluation)  
6. [🔢 Key Takeaways](#-key-takeaways)

---

## 📌 Project Overview
A **machine learning project** to predict **used car prices** based on multiple features such as brand, fuel type, mileage, and more.  
The model is built using **Random Forest Regressor** to handle both numerical and categorical variables effectively.  

---

## ❓ Problem Statement
Accurately predicting the **selling price of a used car** can help sellers and buyers make informed decisions.  
The challenge lies in dealing with various car attributes and transforming them into a form that the model can learn from.

---

## 🛠 Key Features & Terminologies
- **Random Forest Regressor** 🌲: An ensemble learning algorithm combining multiple decision trees for better accuracy.  
- **One-Hot Encoding** 🎯: Used to convert categorical variables into numerical form.  
- **Train-Test Split** ✂️: Data split into training and testing sets for model evaluation.  
- **Evaluation Metrics** 📏: MAE, MSE, RMSE, and R² score used to measure regression performance.

---

## 🛠️ Workflow Summary
1. **Data Collection** 📥 – Gathered dataset containing car details.  
2. **Data Cleaning** 🧹 – Removed null values and duplicates.  
3. **Feature Engineering** ⚙️ – Applied `pd.get_dummies()` to handle categorical variables.  
4. **Model Training** 🏋️ – Used `RandomForestRegressor` with tuned hyperparameters.  
5. **Model Evaluation** 📈 – Measured using regression metrics.  

---

## 📊 Model Evaluation
| Metric | Score |
|--------|-------|
| **MAE**  | 1734.02 |
| **MSE**  | 6,561,627.72 |
| **RMSE** | 2561.57 |
| **R²**   | 0.8584 |

✅ **Interpretation**: The model explains about **85.8%** of the variance in car prices — strong predictive capability💪.

---

## 🏆 Key Takeaways
- **Random Forest** performed exceptionally well with **R² ~ 0.86**.  
- The model can be improved by **feature selection** and **hyperparameter tuning**.  
- One-Hot Encoding expanded features significantly, improving learning for categorical variables.  
- MAE and RMSE values are relatively low compared to price ranges, indicating good accuracy.  

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
