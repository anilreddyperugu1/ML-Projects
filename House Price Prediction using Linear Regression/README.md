# 🏠 House Price Prediction using Linear Regression

A machine learning project to predict house prices based on area using Linear Regression.  It identifies the linear relationship between house area (sqft) and price to estimate property values accurately. Let's dive in 🚀

---

## 📑 Index

1. [📌 Project Overview](#-project-overview)  
2. [❓ Problem Statement](#-problem-statement)  
3. [🧠 Key Features & Terminologies](#-key-features--terminologies)  
4. [⚙️ Workflow Summary](#️-workflow-summary)  
5. [📊 Model Evaluation](#-model-evaluation)  
6. [🏁 Key Takeaways](#-key-takeaways)

---

## 📌 Project Overview

This project uses **Linear Regression** to model and predict house prices based on the area. It aims to understand the influence of house size (in sqft) on its selling price by analyzing historical data and building a regression line.

---

## ❓ Problem Statement

Given a dataset of houses with features such as **Area** and **Price**, predict the selling price of a house based on its area using a simple linear regression model.

---

## 🧠 Key Features & Terminologies

- **Linear Regression**: A supervised learning algorithm used to model the relationship between input and output variables by fitting a straight line.
- **Area (in sqft)**: Independent variable (feature).
- **Price (in ₹)**: Dependent variable (target).
- **Outlier Removal**: Applied using IQR method to improve model accuracy.
- **Evaluation Metrics**: MAE, MSE, RMSE, and R² score.

---

## ⚙️ Workflow Summary

1. Loaded and visualized the dataset 📊  
2. Identified and removed outliers using IQR technique 🧹  
3. Split the dataset into training and testing sets ✂️   
4. Trained the **Linear Regression** model 🏗️  
5. Evaluated the model using regression metrics 📈

---

## 📊 Model Evaluation

- **Mean Absolute Error (MAE)**: ₹44,346.12  
- **Mean Squared Error (MSE)**: ₹3,024,915,810.04  
- **Root Mean Squared Error (RMSE)**: ₹54,999.23  
- **R² Score**: 0.11  

📉 Score is low since it's not a meaningful data.


---

## 🏁 Key Takeaways

- Linear Regression is a simple yet powerful tool to analyze linear relationships.
- The model showed high error and low R² — suggesting that **area alone is insufficient** for accurately predicting price.
- Outlier removal and scaling helped reduce noise, but the dataset might need more features (like location, bedrooms, age of house, etc.) for better accuracy.

---

## 👨‍💻 Author

AnilReddy Perugu💝

📧 peruguanilreddy6@gmail.com

📌 Feel free to reach out for feedback, questions, or collaborations!

