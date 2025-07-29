# 🛍️ Customer Purchase Prediction using Logistic Regression

This project builds a **binary classification model** to predict whether a new customer will **purchase a product** based on their **Age** and **Estimated Salary**. It demonstrates the application of **Logistic Regression** on simple demographic features to make marketing-based predictions.


## 🗂️ Index

📌 [Project Overview](#project-overview)

🚀 [Key Features & Technologies Used](#key-features--technologies-used)

🧠 [Modeling Workflow](#modeling-workflow)  

📊 [Results & Evaluation](#results--evaluation)

💡 [Key Takeaways](#key-takeaways)

---

## 📌 Project Overview

This project aims to predict whether a customer will make a purchase or not based on two input features:
  * Age
  * Estimated Salary

A Logistic Regression model is trained to classify customers into purchaser (1) or non-purchaser (0) categories. This type of prediction helps businesses target their audience more efficiently in marketing campaigns.

---

## 🚀 Key Features & Technologies Used

🔢 Binary classification using Logistic Regression

⚙️ Data scaling using StandardScaler

📊 Model evaluation using Accuracy, Precision, Recall, and F1-score

📈 Data visualization in both 2D and 3D

---

## 🐍 Libraries used:

* Python

* Pandas

* NumPy

* Matplotlib

* Scikit-learn (LogisticRegression, StandardScaler, train_test_split)

---

## 🧠 Modeling Workflow

**1. Data Preprocessing**
  * Checked for missing values
  * Scaled features using StandardScaler

**2. Splitting Data**
  * Used train_test_split() to divide the data into training and test sets

**3. Model Training**
  * Trained a LogisticRegression model using the training data

**4. Prediction & Evaluation**
  * Made predictions on the test set
  * Evaluated using confusion matrix, accuracy, precision, recall, and F1-score

**5. Visualization**
  * 2D plots for decision boundary
  * 3D scatter plot using Age, Salary, and Status

---

## **📊 Results & Evaluation**

  * ✅ Achieved an accuracy of 82.5% on the test set.
    
  **📌 Evaluated using:**
   * Confusion Matrix
   * Precision, Recall, F1-score
   * Manual Evaluation
These metrics helped assess the model’s ability to correctly classify customers who are likely to purchase the product.

---

## 💡 Key Takeaways

* Logistic Regression works well for linearly separable data.
  
* Feature scaling is essential for consistent model performance.
  
* Even with just 2 features (Age & Salary), meaningful predictions can be achieved.
