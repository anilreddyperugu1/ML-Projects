# 🧠 Digit Recognition using Random Forest

This project builds a strong model to recognize handwritten digits (0–9) 🔢 using the Random Forest algorithm. The model is trained on image data represented as pixel values 🤳. It aims to accurately classify each digit image. Let's dive in 🚀!

---

## 📚 Index
1. [Project Overview](#project-overview)
2. [Problem Statement](#problem-statement)
3. [Key Features & Terminologies](#key-features--terminologies)
4. [Libraries Used](#libraries-used)
5. [Modeling & Evaluation](#modeling--evaluation)
6. [Classification Report](#classification-report)
7. [Key Takeaways](#key-takeaways)
8. [Author](#author)

---

## 🚀 Project Overview
This project focuses on building a **handwritten digit recognition system** using the **Random Forest Classifier**. It leverages a structured dataset where each row represents a handwritten digit (flattened pixel values) along with its corresponding label (0–9).

---

## ❓ Problem Statement
The task is to accurately predict the **digit (0-9)** from an image represented as pixel values. The dataset contains 28×28 grayscale images flattened into vectors, and our goal is to build a classifier that can **learn from this pixel data** and **predict the correct digit**.

---

## 🧩 Key Features & Terminologies
- **Random Forest Classifier** 🌲: An ensemble of decision trees used for classification.
- **Pixel Features**: Flattened values from 28x28 image grid.
- **Accuracy Score**: Evaluation metric based on correct predictions.
- **Confusion Matrix**: Visual representation of prediction vs actual labels.
- **Train-Test Split**: Dataset divided for training and evaluating the model.

---

## 🛠️ Libraries Used
- `pandas`
- `numpy`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 📊 Modeling & Evaluation
- Model used: **Random Forest Classifier**
- Training data: **80%**
- Testing data: **20%**
- Evaluation Metrics: **Accuracy Score**, **Confusion Matrix**, **Classification Report**

---

## 📈 Classification Report

| Class | Precision | Recall | F1-Score | Support |
|-------|-----------|--------|----------|---------|
|   0   |   0.96    |  1.0   |   0.98   |   827   |
|   1   |   0.97    |  0.99  |   0.98   |   937   |
|   2   |   0.96    |  0.97  |   0.96   |   835   |
|   3   |   0.96    |  0.93  |   0.94   |   870   |
|   4   |   0.98    |  0.97  |   0.97   |   814   |
|   5   |   0.97    |  0.95  |   0.96   |   759   |
|   6   |   0.98    |  0.97  |   0.98   |   827   |
|   7   |   0.98    |  0.96  |   0.97   |   880   |
|   8   |   0.94    |  0.96  |   0.95   |   813   |
|   9   |   0.95    |  0.94  |   0.95   |   838   |

---

## 💡 Key Takeaways
- Random Forest provides high accuracy and is less prone to overfitting compared to a single decision tree.
- Image data can be efficiently classified using ensemble techniques.
- Visualizing confusion matrix and analyzing misclassified digits helps improve model understanding.

---

## 👨‍💻 Author

**Anil Reddy💝**  
📧 peruguanilreddy6@gmail.com  
📌 *Feel free to reach out for feedback, questions, or collaborations!*

---
