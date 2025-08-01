# 🔢 Handwritten Digits Recognition using SVM

Welcome to the Digit Recognition project! 🧠 This project leverages the popular `load_digits()` dataset from `scikit-learn` to classify handwritten digits (0–9) using a Support Vector Machine with an RBF kernel. Let's dive in! 🚀

---

## 📚 Index

1. [📌 Project Overview](#-project-overview)  
2. [❓ Problem Statement](#-problem-statement)  
3. [🔍 Key Features & Terminologies](#-key-features--terminologies)  
4. [🧰 Libraries Used](#-libraries-used)  
5. [📈 Results & Evaluation](#-results--evaluation)
6. [🧪 Model Comparison](#-model-comparison)
7. [🧠 Key Takeaways](#-key-takeaways)

---

## 📌 Project Overview

This project demonstrates handwritten digit recognition using classical machine learning techniques. We apply a **Support Vector Machine (SVM)** with an **RBF (Radial Basis Function) kernel** on the `load_digits()` dataset from `sklearn.datasets`. The goal is to train the model to identify digits based on pixel values from 8x8 grayscale images.

---

## ❓ Problem Statement

➡️ **Objective:**  
To accurately classify handwritten digits (0–9) based on their pixel intensity values using SVM with an RBF kernel.

➡️ **Challenges Addressed:**
- High-dimensional input data
- Multi-class classification
- Choosing optimal kernel for SVM

---

## 🔍 Key Features & Terminologies

- **`load_digits()` Dataset** 🧮  
  Contains 1,797 samples of handwritten digits represented as 8x8 grayscale images (64 features per sample).

- **Support Vector Machine (SVM)** 📏  
  A supervised learning algorithm used for classification, especially effective in high-dimensional spaces.

- **Kernel Trick** 🧠  
  Transforms data into higher dimensions where it becomes linearly separable.

- **Confusion Matrix** 🔀  
  A performance metric showing correct and incorrect predictions by the classifier.

- **Hyperparameter Tuning** 🎛  
  Adjusting `C`, `gamma`, and kernel type to optimize accuracy.
  
---

## 🧰 Libraries Used

python

import numpy as np

import pandas as pd

import matplotlib.pyplot as plt

import seaborn as sns

from sklearn.datasets import load_digits

from sklearn.svm import SVC

from sklearn.model_selection import train_test_split

from sklearn.metrics import accuracy_score, classification_report, confusion_matrix, ConfusionMatrixDisplay

---

## 📈 Results & Evaluation
**Train-Test Split:** 80% data used for training, 20% for testing

**Model Used:** SVM with RBF kernel

**Evaluation Metrics:**

  📊 Confusion Matrix

  🧮 Classification Report (Precision, Recall, F1-score, Accuracy)
  
  📈 Accuracy Achieved: 98%🎯

---

## 🧪 Model Comparison

We evaluated multiple SVM models using different kernels and hyperparameters to identify the most accurate configuration.

| Model   | Kernel       | C        | Gamma     | Accuracy   |
| ------- | ------------ | -------- | --------- | ---------- |
| Model 1 | **RBF**      | 1.0      | ‘scale’   | ✅ **0.98** |
| Model 2 | Linear       | 1.0      | –         | ✅ **0.98** |
| Model 3 | Linear       | 1.0      | ‘scale’   | ✅ **0.98** |
| Model 4 | RBF          | **1.0**  | **0.01**  | 0.75       |
| Model 5 | RBF          | **0.01** | **0.01**  | 0.75       |

📌 Note: Best results were observed with the RBF kernel using C=1.0, gamma='scale'.

---

## 🧠 Key Takeaways

✅ SVM with RBF kernel performs exceptionally well on image-like data such as digits.

🖼 The dataset is clean, balanced, and small — great for beginners to experiment with ML models.

🎯 High accuracy (~98%) was achieved even with only 80% training data, showing the power of SVM.

🧪 Confusion matrix is a great way to interpret model performance on multi-class problems.



