# 📈 Polynomial Regression Project: Salary Prediction Based on Level 💼💰

This project predicts employee salaries based on their level using 📈 Polynomial Regression to capture the non-linear relationship. It compares linear ➖ and polynomial ✨ models to demonstrate improved accuracy in salary estimation 💰. Let's dive in 🚀

---

## 🗂️ Index

1. [📌 Project Overview](#-project-overview)  
2. [❓ Problem Statement](#-problem-statement)  
3. [🧠 Key Features & Terminologies](#-key-features--terminologies)  
4. [⚙️ Workflow Summary](#️-workflow-summary)  
5. [📊 Model Evaluation](#-model-evaluation)  
6. [🏁 Key Takeaways](#-key-takeaways)

---

## 🚀 Project Overview  
This project focuses on predicting an employee's salary based on their level in a company using **Polynomial Regression** 📊. The dataset contains two features: *Level* and *Salary*. Initially, a linear regression model is fitted to observe the baseline performance, followed by polynomial regression to better capture the non-linear relationship ✨.

---

## 🎯 Problem Statement  
Predict the salary 💰 for a given level 🧑‍💼 in the organization. Since salary growth is often non-linear with respect to employee level, polynomial regression helps in capturing the curve more effectively compared to linear regression ➖.

---

## 🔑 Key Features & Terminologies  
- **Level:** Numeric feature representing the employee's rank or level 🎚️.  
- **Salary:** Target variable indicating the salary corresponding to the level 💵.  
- **Linear Regression:** A simple model that assumes a linear relationship between features and target ➖.  
- **Polynomial Regression:** Extends linear regression by adding polynomial features (like Level², Level³, etc.) to model non-linear patterns ✨.

---

## 🛠️ Workflow Summary  
1. **Data Loading:** Import the dataset containing 'Level' and 'Salary' 📥.  
2. **Linear Regression:** Fit a linear regression model to get baseline predictions ➖.  
3. **Polynomial Feature Transformation:** Transform the 'Level' feature into polynomial features of degree 4 (or chosen degree) 🔄.  
4. **Polynomial Regression Model:** Fit a linear regression model on these polynomial features ✨.  
5. **Prediction & Testing:** Manually test the model predictions on specific input levels to observe predicted salaries 🧪.  
6. **Visualization:** Plot both linear and polynomial regression curves to compare fit 📉📈.

---

## 📊 Model Evaluation  
- Linear regression results showed a poor fit due to the non-linear trend in salary progression ➖❌.  
- Polynomial regression achieved a much closer fit, accurately modeling the curve in salary growth ✨✅.  
- Visualizations clearly demonstrate how polynomial regression better captures the relationship 🎨.

---

## 🌟 Key Takeaways  
- Polynomial regression is powerful for modeling non-linear relationships 🔥.  
- Simply increasing model complexity (degree of polynomial) can improve fit but beware of overfitting ⚠️.  
- Visual comparison between linear and polynomial fits is crucial for understanding model performance 👀.  
- Manual testing of specific input values helps validate prediction logic ✔️.

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaboration!

---

Thank you for checking out this project! Feel free to experiment with different polynomial degrees to see how the model adapts 🎉🚀.
