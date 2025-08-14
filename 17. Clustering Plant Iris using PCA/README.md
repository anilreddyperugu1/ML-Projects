# 🌸 Clustering the Iris Dataset using PCA & Logistic Regression 🌿  

A 🌼 machine learning project that applies **Principal Component Analysis (PCA)** for dimensionality reduction and then uses **Logistic Regression** for classification.  This project demonstrates how PCA can simplify high-dimensional data while preserving its essence 💡 for effective classification. Let's dive in 🚀

---

## 📜 Index  
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 📚 [Key Features & Terminologies](#-key-features--terminologies)  
4. 🔄 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)  
6. 🎯 [Key Takeaways](#-key-takeaways)  
---

## 📌 Project Overview  
The goal 🎯 of this project is to **cluster** the famous Iris dataset 🌸 into meaningful groups using **unsupervised learning**.  
We first reduce the dataset from 4️⃣ features to 2️⃣ principal components using PCA 🎨 and then apply **Logistic Regression** 🤖 for classification.

---

## ❓ Problem Statement  
The Iris dataset has **four features** 📏 (sepal length, sepal width, petal length, petal width).  
Visualizing and clustering directly in 4D is hard 🌀, so we need a method to reduce the complexity without losing key patterns 🌟.  
PCA helps us convert these 4D data points into **2 principal components** 🔍 for easy visualization and better clustering.

---

## 📚 Key Features & Terminologies  
- PCA (Principal Component Analysis) 🗜️ → Reduces the number of features while retaining most of the data's variance 📉.

- Logistic Regression 🤖 → A supervised learning algorithm for classification problems 📚.

- Explained Variance Ratio 📊 → Shows how much information (variance) each principal component holds.

- Confusion Matrix 🧮 → Gives insight into correct vs incorrect predictions.

- Accuracy, Precision, Recall, F1-Score 📏 → Metrics to evaluate classification performance.

---

## 🔄 Workflow Summary  

1. **📥 Load Data**  
   - Imported the **Iris dataset** 🌸 from `sklearn.datasets`.  

2. **🧹 Data Preprocessing**  
   - Scaled features using **StandardScaler** ⚖️ to give equal weight to all measurements.

3. **🔍 Apply PCA**  
   - Reduced from 4️⃣ features → 2️⃣ principal components 📉.  
   - First component captures 🌟 maximum variance, second captures the next most variance.  
   - Explained variance ratio showed **how much info we kept** (~95% retained 📊).    

5. **📈 Visualization**  
   - Scatter plot 🎨 of principal components with colors 🎨 for clusters.  
   - Highlighted **cluster centers** ✨ for better understanding.  

---

## 📊 Model Evaluation
Accuracy 🏆: 0.9✅

---

## 🎯 Key Takeaways  
- PCA 🎨 is a **helper tool** that reduces complexity and makes clustering easier & more accurate 🚀.  
- High explained variance ratio 💯 means PCA kept most of the original data’s information.   
- Visualization in 2D becomes much more interpretable after PCA 📉.

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!

