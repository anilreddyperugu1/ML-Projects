# 📘 Marks Prediction using Linear Regression

A simple Linear Regression project to predict students’ marks based on study hours, age, and internet access. Let's dive in 🚀

---

## 📑 **Index**
1. [📌 Project Overview](#-project-overview)  
2. [🎯 Problem Statement](#-problem-statement)  
3. [🧠 Key Features & Terminologies](#-key-features--terminologies)  
4. [⚙️ Workflow Summary](#️-workflow-summary)  
5. [📊 Model Evaluation](#-model-evaluation)  
6. [🔢 Key Takeaways](#-key-takeaways)  

---

## 📌 **Project Overview**
A simple **Linear Regression** project to predict students' marks based on **Hours studied, Age, and Internet access (0 or 1)**.  
The project is implemented in **two ways**:
- Without splitting data (trained on the whole dataset)  
- With train-test splitting and feature scaling for better generalization.

---

## 🎯 **Problem Statement**
The objective is to **predict students' marks** using available independent variables such as:
- Hours studied per day  
- Age of the student  
- Internet access availability (binary: 0 = No, 1 = Yes)  

The challenge is to build a regression model that can generalize well on unseen data.

---

## 🧠 **Key Features & Terminologies**
- **Linear Regression** – A supervised learning algorithm that models the relationship between dependent and independent variables using a straight line.  
- **Train-Test Split** – Dividing the dataset into training and testing parts to evaluate model performance on unseen data.  
- **Feature Scaling (Standardization)** – Transforming numerical features to have a standard scale for better model stability.  
- **Binary Variable** – A feature with only two possible values (e.g., Internet: 0 or 1).

---

## ⚙️ **Workflow Summary**
1. **Data Collection & Loading** – Imported dataset containing Hours, Age, Internet Access, and Marks.  
2. **Exploratory Data Analysis (EDA)** – Checked basic statistics and feature distributions.  
3. **Model Training** – Applied Linear Regression in two approaches:
   - Without train-test split
   - With train-test split + scaling  
4. **Model Evaluation** – Compared predictions for both approaches using evaluation metrics.  

---

## 📊 **Model Evaluation**
**For Train-Test Split Model**:
- **MAE**: 31.88  
- **MSE**: 1018.92  
- **RMSE**: 31.92  
- **R² Score**: -39.49  

---

## 🔢 **Key Takeaways**
- Both models (with and without splitting) gave similar predictions in this small dataset.  
- Scaling is more beneficial when working with algorithms sensitive to feature magnitudes or when datasets have varied scales.  
- Negative R² indicates that the dataset might not have strong linear relationships between features and marks, suggesting the need for more data or different model approaches.  

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaboration!
