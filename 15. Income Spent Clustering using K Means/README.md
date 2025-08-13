# 💰 Income-Spend Clustering using K-Means

A machine learning project that applies **K-Means Clustering** to segment individuals based on their **income and spending habits**.  The goal is to identify meaningful customer groups for better business decision-making.  Let's dive in 🚀


---

## 📚 Index
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 🧠 [Key Features & Terminologies](#-key-features--terminologies)  
4. 🛠 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)  
6. 📌 [Cluster Interpretation](#-cluster-interpretation) 
7. 🎯 [Key Takeaways](#-key-takeaways)    

---

## 📝 Project Overview  
This project applies **K-Means Clustering** to segment individuals based on **Income** and **Spending Score**. The objective is to identify distinct customer groups for targeted decision-making in business contexts such as marketing, offers, and customer engagement.

---

## 🎯 Problem Statement  
Businesses often struggle to segment customers effectively for personalized marketing. By clustering customers based on **annual income** and **spending behavior**, companies can tailor their services and strategies more efficiently.

---

## 🧠 Key Features & Terminologies  

- **Income**: Annual earnings of an individual.  
- **Spend**: Spending score indicating purchasing tendencies.  
- **K-Means Clustering**: An unsupervised learning algorithm to group similar data points into `K` clusters.  
- **WCSS (Within-Cluster Sum of Squares)**: A metric to evaluate how close the data points are to their respective cluster centers.  
- **Elbow Method**: A technique to determine the optimal number of clusters (`K`).  

---

## 🔄 Workflow Summary  

1. **Data Loading & Exploration** 🧐  
   - Loaded `dataset.csv` containing `INCOME` and `SPEND` columns.  
   - Performed head/tail inspection and statistical summary.  

2. **Data Visualization** 📈  
   - Scatter plots to visualize data distribution.  
   - Statistical percentiles to understand income & spend segmentation.

3. **Elbow Method for Optimal K** 📊  
   - Iteratively computed **WCSS** for `K` = 1 to 10.  
   - Chose optimal K where WCSS curve bends (Elbow point).

4. **Model Training** 🤖  
   - Trained K-Means model with optimal clusters.  
   - Obtained **labels** (cluster assignments) and **centers** (cluster centroids).  

5. **Cluster Visualization** 🎨  
   - Plotted clusters with different colors.  
   - Displayed centroids for better interpretability.

---

## 📊 Model Evaluation  

- **WCSS Analysis**: Used to determine cluster compactness.  
- **Visual Validation**: Checked separation and distribution of clusters.  

---

## 📌 Cluster Interpretation  

Based on statistical percentiles and cluster centers:  

- **Cluster 0** → Medium Income, Medium Spend  
- **Cluster 1** → Low Income, Medium Spend  
- **Cluster 2** → High Income, Medium Spend  

---

## 🎯 Key Takeaways  

✅ K-Means effectively segmented the dataset into meaningful clusters.  
✅ Using percentiles helps label clusters as **low**, **medium**, or **high** for business interpretation.  
✅ Visualization alone doesn’t define cluster labels — statistical measures are essential for naming clusters.  
✅ This approach can be applied in **marketing**, **customer segmentation**, and **sales optimization**.  

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
