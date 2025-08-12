# 🚗💨 Car Engine Power Output Prediction using Multiple Regression Models

A machine learning project to predict the **electrical power output** of a **Combined Cycle Power Plant** based on environmental and operational parameters. **Multiple regression** models were compared to identify the most accurate and reliable predictor. Let's dive in 🚀

---

## 📑 **Index**
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 🧠 [Key Features & Terminologies](#-key-features--terminologies)  
4. 🛠 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)  
6. 📉 [Residual Plot Insights](#-residual-plot-insights)  
7. 🎯 [Key Takeaways](#-key-takeaways)  

---

## 📌 Project Overview
A machine learning project to **predict the power output of a Combined Cycle Power Plant (CCPP)** using various regression models.  The dataset contains 9568 samples with environmental and operational features such as **Ambient Temperature (AT)**, **Exhaust Vacuum (V)**, **Ambient Pressure (AP)**, and **Relative Humidity (RH)**.  
The goal is to accurately predict the **Electrical Energy Output (PE)**.

---

## 🎯 Problem Statement
Given environmental factors from a CCPP, we aim to build regression models that can predict the **Power Output (PE)**.  
This prediction can help optimize operations and plan energy production more efficiently.

---

## 🧠 Key Features & Terminologies
- **AT (Ambient Temperature)** – Temperature in °C.  
- **V (Exhaust Vacuum)** – Vacuum pressure in cm Hg.  
- **AP (Ambient Pressure)** – Pressure in millibar.  
- **RH (Relative Humidity)** – Percentage of moisture in the air.  
- **PE (Electrical Energy Output)** – Target variable in MW.

**Regression Metrics Used:**
- **MAE (Mean Absolute Error)** – Average absolute difference between actual and predicted values.  
- **MSE (Mean Squared Error)** – Average of squared differences.  
- **RMSE (Root Mean Squared Error)** – Square root of MSE.  
- **R² Score** – Proportion of variance explained by the model.

---

## 🛠 Workflow Summary
1. **Data Loading & Exploration** 🧐  
   - Checked dataset dimensions and missing values.  
   - Dataset shape: **(9568, 5)**.  

2. **Data Preprocessing** 🧹  
   - Feature scaling applied to `X_train` and `X_test` using **StandardScaler**.  
   - Target variable `y` was not scaled.  

3. **Model Training** 🤖  
   - Trained **five regression models** in a loop:  
     - `LinearRegression`  
     - `DecisionTreeRegressor`  
     - `SVR`  
     - `KNeighborsRegressor`  
     - `RandomForestRegressor`
       
4. **Visualization**
    - Visualized using **residual** plots for every model for better insights
    - Residuals works well on regression tasks

5. **Model Evaluation** 📏  
   - Predictions made on the test set for all models.  
   - Calculated MAE, MSE, RMSE, and R² scores.  
   - Checked for **overfitting/underfitting** using `model.score()` for train and test sets.

---

## 📊 Model Evaluation
Best performing model: **RandomForestRegressor** 🌟  

**Random Forest Evaluation Metrics:**
- **MAE**: `2.34`  
- **MSE**: `10.74`  
- **RMSE**: `3.27`  
- **R² Score**: **0.98**

---

## 📉 Residual Plot Insights
- X-axis: **Predicted Values (y_pred)**  
- Y-axis: **Residuals (y_test - y_pred)**  
- Points were **fairly centered around the zero line**, indicating no major bias.  
- Few points at the **extreme top/bottom** edges → possible outliers or high-leverage points.  
- Used `axhline(y=0)` to visualize the zero-residual reference.

---

## 🎯 Key Takeaways
- **RandomForestRegressor** achieved the best accuracy, but showed slight overfitting.  
- Residual plots confirm that most predictions were close to actual values.  
- Some high-residual points may require further investigation.  
- Scaling `X` but not `y` was sufficient for this problem.  
- ROC curve is **not applicable** for regression tasks; residual analysis is more useful here.

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
