# 🎬 Movie Recommendation System using SVD

This project builds a Movie Recommendation System using Singular Value Decomposition (SVD) to suggest movies based on user preferences. It leverages the MovieLens dataset and collaborative filtering to generate personalized top-N recommendations. Lets's dive in 🚀

---

## 📑 Index
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 📚 [Key Features & Terminologies](#-key-features--terminologies)  
4. 🔄 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)  
6. 🎯 [Key Takeaways](#-key-takeaways)  
---

## 📖 Project Overview
A recommendation system designed to suggest movies to users based on their past ratings using **Singular Value Decomposition (SVD)** from the `scikit-surprise` library.  The system processes the **MovieLens dataset** and predicts top-rated movies a user is likely to enjoy.  

---

## 🎯 Problem Statement
Online platforms host thousands of movies, making it overwhelming for users to decide what to watch next.  This project aims to solve this by **personalizing movie suggestions** using **collaborative filtering**.

---

## 🧩 Key Features & Terminologies
- **Collaborative Filtering** 🤝 – Recommending based on similarities in user preferences.  
- **SVD (Singular Value Decomposition)** 🧮 – A matrix factorization technique for predicting ratings.  
- **MovieLens Dataset** 🎥 – Dataset containing `movies.dat` and `ratings.dat`.  
- **Precision in Recommendations** 🎯 – Ensuring suggestions are relevant and high-rated.  

---

## 🔄 Workflow Summary
1. **📂 Data Loading** – Read `movies.dat` & `ratings.dat` using Pandas.  
2. **🧹 Preprocessing** – Handle null values, check dataset info.  
3. **📦 Data Conversion** – Convert ratings data into `scikit-surprise` `Dataset` format using `Reader`.  
4. **✂️ Train-Test Split** – 80% training, 20% testing.  
5. **🤖 Model Training** – Apply SVD with hyperparameters (`n_factors=10, n_epochs=50, lr_all=0.006`).  
6. **📈 Predictions** – Predict ratings for unseen movie-user combinations.  
7. **⭐ Top-N Recommendations** – Extract highest-rated predicted movies for each user.  

---

## 📊 Model Evaluation
- **MAE** : 0.67
- **MSE** : 0.73
- **RMSE** : 0.85
- Manual check of predictions for a specific user and movie ID.
  
---

## 💡 Key Takeaways
- SVD is highly effective for **personalized recommendations**.  
- Collaborative filtering requires **sufficient overlap** in user-item interactions.  
- Movie titles are mapped using `movies_df` for **human-readable output**.  
- Can be extended to **real-time recommendation systems** for streaming platforms.  

---

📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!

---

✨ *This recommendation system can power platforms like Netflix or Amazon Prime!* 🍿
