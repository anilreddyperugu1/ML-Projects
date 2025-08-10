# 📈 Stock Price Prediction using Support Vector Regression (SVR) 💹

This project uses Support Vector Regression (SVR) to predict stock prices based on historical data. SVR’s📈 ability to model complex, non-linear relationships makes it ideal for tackling the volatility of stock markets. Let's dive in 🚀

---

## 📝 Index  
1. [📌 Project Overview](#-project-overview)  
2. [🎯 Problem Statement](#-problem-statement)  
3. [🧠 Key Features & Terminologies](#-key-features--terminologies)  
4. [⚙️ Workflow Summary](#️-workflow-summary)  
5. [📊 Model Evaluation](#-model-evaluation)  
6. [🔢 Key Takeaways](#-key-takeaways)  

---

## 📋 Project Overview  
This project focuses on predicting stock prices using **Support Vector Regression (SVR)** with an RBF kernel📊. The goal is to build a model that accurately forecasts stock prices based on historical data, helping investors and analysts make informed decisions. SVR is chosen because it can capture complex non-linear relationships in the data, making it suitable for volatile stock market predictions✅.

---

## ❓ Problem Statement  
Predicting stock prices is a challenging task due to market volatility and noise in data📉. This project aims to leverage SVR to capture non-linear patterns and trends for better price prediction accuracy✅.

---

## 🧠 **Key Features & Terminologies** 
- **SVR (Support Vector Regression):** A regression technique that uses support vectors to predict continuous values✅.  
- **RBF Kernel:** A kernel function that handles non-linear relationships by mapping data into higher-dimensional space🔥.  
- **C Parameter:** Regularization parameter controlling the trade-off between fitting the data well and keeping the model simple®️.  
- **MAE (Mean Absolute Error):** Average of absolute errors between predicted and actual values🧨📋.  
- **MSE (Mean Squared Error):** Average of squared errors, penalizes larger errors more heavily⚡.  
- **RMSE (Root Mean Squared Error):** Square root of MSE, gives error in same units as target📐.  
- **R² Score (Coefficient of Determination):** Measures how well the model explains variability in the data 💫👌.

---

## 🛠️ Workflow Summary  
1. **Data Preparation:**  
   - Loaded dataset containing features `X` and target `y` (stock prices).  
   - Checked and handled any null/missing values. ✅  

2. **Data Splitting:**  
   - Divided data into training and testing sets for unbiased evaluation. 🔀  

3. **Model Training:**  
   - Trained SVR model using default parameters and noted R² score (~0.82).  
   - Tuned SVR with **RBF kernel** and **C=100**, improving R² score to **0.918**. 🚀  

4. **Model Evaluation:**  
   - Evaluated using metrics: MAE, MSE, RMSE, and R² score for comprehensive insight. 📊  

---

## 📊 Model Evaluation  
| Metric                   | Value        | Description                                             |  
|--------------------------|--------------|---------------------------------------------------------|  
| Mean Absolute Error (MAE) | 1.39         | Average absolute difference between predicted and actual values. |  
| Mean Squared Error (MSE)  | 3.36         | Average squared difference, penalizes large errors.    |  
| Root Mean Squared Error (RMSE) | 1.83    | Square root of MSE, in original units.               |  
| R² Score                  | 0.918        | Model explains 91.8% of the variance.                   |

---

## ✨ Key Takeaways  
- Tuning SVR parameters like **C** and kernel choice significantly improves performance. ⚙️  
- SVR with **RBF kernel** can effectively capture complex stock price patterns. 📈  
- Evaluating multiple metrics provides a complete view of model accuracy. 📉  
- This approach can be extended and enhanced with more features or alternative models. 💡  

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaboration!
