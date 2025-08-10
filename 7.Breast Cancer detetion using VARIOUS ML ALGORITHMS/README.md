# 🧠 Breast Cancer Classification using Machine Learning

A machine learning project to classify tumors as malignant or benign using the 🧬 Breast Cancer Wisconsin dataset. This project compares multiple classification algorithms to determine the best-performing model based on evaluation metrics like AUC-ROC and classification reports. Let's dive in 🚀

---

## 🧾 Index

1. 📌 [Project Overview](#project-overview)  
2. ❓ [Problem Statement](#problem-statement)  
3. 🧬 [Key Features & Terminologies](#key-features--terminologies)  
4. 🔄 [Workflow Summary](#workflow-summary)  
5. 📊 [Model Evaluation](#model-evaluation)  
6. 🧮 [Confusion Matrix](#confusion-matrix)  
7. 🚀 [Key Takeaways](#key-takeaways)

---

## 📌 Project Overview

This project uses machine learning to classify breast cancer tumors as **malignant (M)** or **benign (B)**. The dataset is preprocessed, balanced, and used to train six different classification models. ROC curves and AUC scores are used to evaluate model performance.

---

## ❓ Problem Statement

To build a binary classification model that predicts whether a breast tumor is **malignant (cancerous)** or **benign (non-cancerous)** using patient data.  
🎯 The goal is to accurately detect malignant cases with minimal false negatives.

---

## 🧬 Key Features & Terminologies

- 🔺 **Malignant (M)**: Cancerous tumor (labeled as `1`)
- 🟢 **Benign (B)**: Non-cancerous tumor (labeled as `0`)
- 📈 **ROC Curve**: Receiver Operating Characteristic curve for visualizing model performance.
- 🧩 **AUC Score**: Area Under the ROC Curve — higher is better.
- 🧪 **SMOTE**: Synthetic Minority Oversampling Technique to handle class imbalance.
- 📉 **MinMaxScaler**: Normalizes data to the range [0, 1].

---

## 🔄 Workflow Summary

1. 📥 Loaded the Breast Cancer Wisconsin dataset.
2. 🔃 Converted categorical labels: `M → 1`, `B → 0`.
3. ⚖️ Performed undersampling of the majority class (Benign) for balance.
4. ✂️ Split dataset into training and testing sets.
5. ➕ Applied **SMOTE** to oversample the minority class (Malignant) in the training set.
6. ⚙️ Normalized features using **MinMaxScaler**.
7. 🤖 Trained six classifiers:
   - 📊 Logistic Regression  
   - 🚀 Support Vector Classifier (SVC)  
   - 🧭 K-Nearest Neighbors (KNN)  
   - 🧠 Naive Bayes  
   - 🌲 Decision Tree  
   - 📐 Linear Discriminant Analysis (LDA)  
8. 🧪 Evaluated models using:
   - 📈 ROC Curve  
   - 🧩 AUC Score  
   - 🧮 Confusion Matrix  
   - 📃 Classification Report

---

## 📊 Model Evaluation

| 🧠 Model                 | ⭐ AUC Score |
|--------------------------|--------------|
| Naive Bayes              | **0.99**     |
| Support Vector Machine   | 0.98         |
| Logistic Regression      | 0.98         |
| K-Nearest Neighbors      | 0.97         |
| Decision Tree            | 0.96         |
| Linear Discriminant      | 0.95         |

✅ **Naive Bayes** performed best with an AUC score of **0.99**.

---

## 🧮 Confusion Matrix (Example: Naive Bayes)

|                         | 🔮 Predicted Benign (0) | 🔮 Predicted Malignant (1) |
|-------------------------|--------------------------|----------------------------|
| ✅ Actual Benign         | 59                       | 2                          |
| ❌ Actual Malignant      | 1                        | 41                         |

**Confusion Matrices and Classification reports were generated for all the models. Please get into the project for clear insights..**

---

## 🚀 Key Takeaways

- ⚖️ Dataset had moderate class imbalance: handled using **undersampling** and **SMOTE**.
- 📈 ROC-AUC Curve was effective in comparing all classifiers.
- 🧠 **Naive Bayes** outperformed all other models in this use case.
- 🧮 Confusion Matrix and 📃 Classification Report helped evaluate both classes.
- 🔁 Looping through models worked for ROC, but caused issues with `classification_report()` — resolved by predicting manually per model.

---

## 👨‍💻 Author
Anil Reddy Perugu💝

📧 peruguanilreddy6@gmail.com

📌 Feel free to reach out for feedback, questions, or collaborations!
