# 🚢 Titanic Survival Prediction using Naive Bayes

Welcome to the Digit Recognition project! 🧠 This project leverages the Titanic dataset to predict survival using Naive Bayes. Let's dive in! 🚀

---

## 📚 Index

1. 📌 [Project Overview](#project-overview)
2. ❓ [Problem Statement](#problem-statement)
3. 🔍 [Key Features & Terminologies](#key-features--terminologies)
4. 💼 [Libraries Used](#libraries-used)
5. 📊 [Results & Evaluation](#results--evaluation)
6. 🧪 [Classification_Report](#classification_report)
7. 🧠 [Key Takeaways](#key-takeaways)

---

## 📌 Project Overview

This project aims to predict whether a passenger survived the Titanic disaster based on features such as Pclass, Sex, Age, and Fare.

---

## ❓ Problem Statement

Can we accurately predict survival on the Titanic using machine learning techniques?

The goal is to:
- Understand the impact of features like **Sex**, **Pclass**, and **Age** on survival.
- Build a model using **Naive Bayes** to make survival predictions.
- Handle missing values and perform preprocessing steps effectively.

---

## 🔍 Key Features & Terminologies

**Titanic Dataset 🚢**  
Contains demographic and travel information of passengers aboard the Titanic, such as age, sex, fare, and class.

**Naive Bayes Classifier 📊**  
A probabilistic machine learning algorithm based on Bayes’ Theorem, assuming independence between features.

**Label Encoding 🔢**  
A technique used to convert categorical text data (like "male", "female") into numerical form.

**Skewness in Data 📉**  
Describes the asymmetry in data distribution, helping decide whether to use mean or mode for imputing missing values.

**Classification Report 📋**  
Includes precision, recall, and F1-score to evaluate the model’s performance across different classes.

---

## 💼 Libraries Used

- `pandas` 🐼
- `numpy` 🔢
- `matplotlib` 📉
- `seaborn` 🎨
- `sklearn` 🧠

---

## 📊 Results & Evaluation

- Used **Gaussian Naive Bayes** classifier
- Filled missing `Age` values using **mean imputation** (based on distribution analysis)
- Visualized age distribution using **histplot**
- Converted categorical values using **Label Encoding**
- Evaluated using **Classification Report** and **Confusion Matrix**

---

### ✅ Classification Report

| Metric          | Precision | Recall | F1-Score | Support |
|-----------------|-----------|--------|----------|---------|
| **Class 0**     | 0.83      | 0.85   | 0.84     | 110     |
| **Class 1**     | 0.76      | 0.72   | 0.74     | 69      |
| **Accuracy**    |           |        | **0.80** | 179     |
| **Macro Avg**   | 0.79      | 0.79   | 0.79     | 179     |
| **Weighted Avg**| 0.80      | 0.80   | 0.80     | 179     |

---

## 🧠 Key Takeaways

- Data cleaning (especially handling missing values) significantly affects model performance.
- `Sex` and `Pclass` were the most important predictors for survival.
- Naive Bayes works surprisingly well on structured datasets even with assumptions of independence.
- Visualizations helped determine data distribution and guided preprocessing steps.
