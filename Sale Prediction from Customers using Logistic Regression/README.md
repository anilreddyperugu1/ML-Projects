**🛍️ Customer Purchase Prediction using Logistic Regression**
This project uses Logistic Regression to predict whether a new customer will purchase a product based on their age and salary. It demonstrates a simple yet powerful approach to binary classification using a real-world-style dataset.

**📑 Table of Contents**
--> Problem Statement
--> Project Objectives
--> Dataset Information
--> Tools & Technologies Used
--> Model Workflow
--> Results
--> Key Takeaways

**📌 Problem Statement**
Given a customer's Age and Estimated Salary, predict whether they will purchase a product (Yes = 1, No = 0).

This is a classic binary classification problem commonly used in marketing analytics and customer behavior prediction.

**🔍 Project Objectives**
Analyze the relationship between customer demographics and purchasing behavior.
Apply Logistic Regression to classify potential buyers.
Evaluate model performance using appropriate metrics.
Visualize data and predictions, including 2D and 3D plots.

**📊 Dataset Information**
The dataset contains the following features:
Age: Age of the customer (numeric)
Salary: Estimated salary (numeric)
Status: Purchase status (1 = Purchased, 0 = Not Purchased)

**🧪 Tools & Technologies Used**
Python
Pandas
NumPy
Matplotlib
Seaborn
Scikit-learn (LogisticRegression, StandardScaler, train_test_split)

**📈 Model Workflow**
Data Preprocessing
Checked for missing values and cleaned data
Applied StandardScaler to normalize age and salary
Train/Test Split
Split the dataset into training and testing sets (e.g., 75% train, 25% test)
Model Training
Used LogisticRegression() from scikit-learn
Fitted the model on the scaled training data

**Model Evaluation**
Evaluated accuracy, precision, recall, and F1-score
Used confusion matrix for deeper performance insights
Visualization
Plotted decision boundary (2D)
Created a 3D scatter plot of Age, Salary, and Purchase Status

**🎯 Results**
Achieved an accuracy of 82.5% on the test set.
Model shows strong performance in identifying potential buyers based on salary and age.

**🧠 Key Takeaways**
Logistic Regression performs well when the classes are linearly separable.
Feature scaling is critical for gradient-based optimization algorithms.
Simple demographic data can offer meaningful insights into purchase behavior.
