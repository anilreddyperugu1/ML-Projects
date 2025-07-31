# 🧠 Salary Estimation using K-Nearest Neighbors (KNN)

## 📚 Index

- [📌 Project Overview](#-project-overview)
- [📊 Problem Statement](#-problem-statement)
- [🧰 Tech Stack](#-tech-stack)
- [📦 Libraries Used](#-libraries-used)
- [🗂️ Dataset Description](#️-dataset-description)
- [🧼 Data Preprocessing](#-data-preprocessing)
- [🧠 Model Details](#-model-details)
- [📈 Results](#-results)

---

## 📌 Project Overview

This project demonstrates a **classification task** using the **K-Nearest Neighbors (KNN)** algorithm. The goal is to estimate whether a person earns **more than $50K or less than $50K per year** based on specific personal and financial features.

---

## 📊 Problem Statement

Given a dataset containing the following features:
- `Age`
- `Education Level`
- `Capital Gain`
- `Working Hours per Week`

The objective is to predict the **Income Category**:
- `<=50K`
- `>50K`

---

## 🧰 Tech Stack

- **Language**: Python
- **Libraries**:
  - `pandas`
  - `numpy`
  - `matplotlib`, `seaborn`
  - `scikit-learn`

---

## 📦 Libraries Used

```python
import pandas as pd
import numpy as np
import matplotlib.pyplot as plt
import seaborn as sns
from sklearn.model_selection import train_test_split
from sklearn.preprocessing import LabelEncoder, StandardScaler
from sklearn.neighbors import KNeighborsClassifier
from sklearn.metrics import classification_report, confusion_matrix

---

## 🗂️ Dataset Description

| Feature        | Description                            |
|----------------|----------------------------------------|
| `age`          | Age of the individual                  |
| `education`    | Educational attainment (categorical)   |
| `capital_gain` | Capital gains from investment income   |
| `hours_per_week` | Average working hours per week      |
| `income`       | Target label (`<=50K` or `>50K`)        |

---

## 🧼 Data Preprocessing

- Label encoding or one-hot encoding applied to categorical features
- Normalization or feature scaling to make KNN distance-based computation fair
- Splitting dataset into training and test sets

---

## 🧠 Model Details

- **Algorithm**: K-Nearest Neighbors (KNN)
- **Hyperparameters Tuned**:
  - Number of neighbors (`k`)
  - Distance metric (default: Euclidean)
- **Evaluation Metrics**:
  - Accuracy
  - Precision, Recall, F1-Score
  - Confusion Matrix

---

## 📈 Results

- Final model tested on unseen data
- Achieved:
  - **Accuracy**: XX%
  - **F1-Score**: XX%
- Model showed balanced performance across both income classes

---
