# 🛍️ Customer Segmentation using Hierarchical Clustering

A machine learning project to segment customers based on their **Annual Income** and **Spending Score** using **Hierarchical Clustering**.  This helps businesses understand their customer groups better and tailor marketing strategies accordingly. Let's dive in 🚀

---

## 📑 Index
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 📚 [Key Features & Terminologies](#-key-features--terminologies)  
4. 🔄 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)  
6. 🎯 [Key Takeaways](#-key-takeaways)  

---

## 📌 Project Overview
Customer segmentation is the practice of dividing customers into groups based on shared characteristics.  This project uses **Agglomerative Hierarchical Clustering** to group customers based on their **income** and **spending habits**.

---

## 🎯 Problem Statement
A shopping mall wants to better understand its customers to offer **personalized promotions** and **improve sales strategies**.  The task is to segment customers into distinct groups using **unsupervised learning**.

---

## 📚 Key Features & Terminologies

- **Annual Income (k$)** 💰 → Customer’s yearly income in thousands of dollars.  
- **Spending Score (1-100)** 🛒 → An internal score assigned by the mall based on customer behavior and spending nature.  
- **Hierarchical Clustering** 🔗 → A method that builds nested clusters by either merging or splitting them step-by-step.  
- **Agglomerative Clustering** 📦 → A bottom-up approach where each point starts as its own cluster and merges with others.  

---

## 🔄 Workflow Summary

1. **Data Collection & Preparation** 📂  
   - Selected **Annual Income** and **Spending Score** as the clustering features.  
   - Scaled the features for uniformity.  

2. **Model Training** 🤖  
   - Used **Agglomerative Clustering** for segmentation.  

3. **Finding Optimal Clusters** 🔍  
   - Used **Dendrograms** for visual inspection.  

4. **Cluster Analysis** 📊  
   - Compared cluster labels with percentiles of Income and Spending Score to interpret groups:  
     - **Cluster 0** → High Income, High Spending  
     - **Cluster 1** → Low Income, Low Spending  
     - **Cluster 2** → Medium Income, Medium Spending  

5. **Evaluation Metrics** 📏  
   - **Silhouette Score**: `0.462` → Moderate separation between clusters.  
   - **Davies-Bouldin Index**: `0.707` → Low score, indicating well-separated clusters.  
   - **Calinski-Harabasz Index**: `143.820` → High score, suggesting dense and well-separated clusters.  

---

## 📊 Model Evaluation

| Metric 📏                 | Score   | Interpretation 🧐 |
|---------------------------|---------|-------------------|
| **Silhouette Score**      | 0.462   | Moderate structure in the clusters. |
| **Davies-Bouldin Index**  | 0.707   | Low value indicates good separation between clusters. |
| **Calinski-Harabasz**     | 143.820 | Higher value means compact clusters with good separation. |

---

## 🎯 Key Takeaways

- Hierarchical Clustering can effectively identify **customer groups** even without predefined labels.  
- Evaluation metrics confirm that clusters are **well-separated** and **meaningful**.  
- Percentile-based interpretation helps in **labeling clusters** as high, medium, or low spenders/income.  

---

📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
