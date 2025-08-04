# 🌸 Iris Flower Classification

This project demonstrates a classification task using the Decision tree algorithm. The goal is to classify a flower 🌸 into one of the three known species (Setosa, Versicolor, Virginica). Let's dive in 🚀

---

## 📌 Index
- [Project Overview](#project-overview)
- [Problem Statement](#problem-statement)
- [Key Features & Terminologies](#key-features--terminologies)
- [Libraries Used](#libraries-used)
- [Model Details](#model-details)
- [Results & Evaluation](#results--evaluation)
- [Key Takeaways](#key-takeaways)
- [Author](#author)

---

## 📖 Project Overview
This project focuses on building a machine learning model that classifies Iris flowers into three species — Setosa, Versicolor, and Virginica — based on flower features such as petal and sepal length and width.

---

## ❓ Problem Statement
Given the measurements of flower petals and sepals, classify the Iris flower into one of the three known species. This is a classic supervised classification problem in machine learning.

---

## 🧠 Key Features & Terminologies
- **Sepal Length & Width**
- **Petal Length & Width**
- **Target Labels**: Setosa, Versicolor, Virginica
- **Classification Algorithm**
- **Accuracy, Precision, Recall, F1-Score**

---

## 🛠️ Libraries Used
- `numpy`
- `pandas`
- `matplotlib`
- `seaborn`
- `scikit-learn`

---

## 🤖 Model Details

- ✅ **Dataset**: Iris dataset (`sklearn.datasets.load_iris()`)
- ✅ **Best Performing Model**: Decision Tree Classifier (`criterion="entropy"`)
- ✅ **Hyperparameter Tuning**: Visualized performance vs. `max_depth` to select optimal depth
- ✅ **Train-Test Split**: 80-20
- ✅ **Evaluation Used**:
  - Confusion Matrix
  - Classification Report (shown below)

---

## 📊 Results & Evaluation

### 🔢 Classification Report

| Class | Precision | Recall | F1-score | Support |
|-------|-----------|--------|----------|---------|
| 0     | 1.00      | 1.00   | 1.00     | 10      |
| 1     | 0.91      | 1.00   | 0.95     | 10      |
| 2     | 1.00      | 0.90   | 0.95     | 10      |
|       |           |        |          |         |
| **Accuracy**     |        |        | **0.97** | 30      |
| **Macro Avg**    | 0.97   | 0.97   | 0.97     | 30      |
| **Weighted Avg** | 0.97   | 0.97   | 0.97     | 30      |

---

## 🔑 Key Takeaways

- Decision Tree performed best with entropy and optimal depth selection.
- Achieved high classification accuracy of **97%**.
- Learned to use visualization for hyperparameter tuning.
- Gained insights on interpreting precision, recall, and F1-score.

---

## 👨‍💻 Author

- **Name**: Anil Reddy  
- **Email**: [peruguanilreddy6@gmail.com]  
- 💬 Feel free to reach out for suggestions or collaboration!

---

