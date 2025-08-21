# 🛫 Airline Tweets Sentiment Analysis ✈️

✈️ A machine learning project to analyze airline tweets and classify them into positive, neutral, or negative sentiments.1🧠 The model uses TF-IDF vectorization, SMOTE for balancing, and Random Forest Classifier to predict customer sentiment effectively. Let's dive in ✨

---
## 📑 Index  
1. [📌 Project Overview](#-project-overview)  
2. [🎯 Problem Statement](#-problem-statement)  
3. [🧠 Key Features & Terminologies](#-key-features--terminologies)  
4. [⚙️ Workflow Summary](#️-workflow-summary)   
5. [📊 Model Evaluation](#-model-evaluation)
6. [🔢 Confusion Matrix](#-confusion-matrix) 
7. [🔢 Key Takeaways](#-key-takeaways)

---

## 📌 Project Overview  
This project applies **Sentiment Analysis** on airline-related tweets to classify them into **Positive, Neutral, or Negative sentiments**.  
We preprocess tweets, handle imbalanced data, and build a **Random Forest Classifier** to predict sentiment effectively.  

---

## ❓ Problem Statement  
Airline companies receive thousands of customer tweets daily. Understanding sentiment helps improve customer satisfaction and business strategies.  
The challenge is to **classify tweets accurately into sentiment categories** despite:  
- Noisy text (slang, misspellings, emojis)  
- Class imbalance in sentiment distribution  

---

## 🧾 Key Features & Terminologies  
- **TF-IDF (Term Frequency – Inverse Document Frequency):** Converts tweets into numeric vectors.  
- **SMOTE (Synthetic Minority Oversampling Technique):** Balances dataset by oversampling minority classes.  
- **Random Forest Classifier:** Ensemble model for robust sentiment classification.  
- **Confusion Matrix & Classification Report:** Evaluation metrics to analyze performance.  

---

## ⚙️ Workflow Summary  
1. 📥 **Data Loading** – Imported airline tweets dataset.  
2. 🧹 **Data Cleaning** – Removed irrelevant columns like `tweet_id`, `user_timezone`, etc.  
3. 🔤 **Text Preprocessing** –  
   - Removed punctuation, special chars, and stopwords.  
   - Applied **Stemming** using PorterStemmer.  
4. 📊 **EDA** – Checked class distribution and missing values.  
5. ✨ **Feature Extraction** – Applied **TF-IDF vectorization**.  
6. ⚖️ **Balancing Dataset** – Used **SMOTE** to handle class imbalance.  
7. 🤖 **Model Training** – Trained a **Random Forest Classifier**.  
8. 🧪 **Evaluation** – Assessed using accuracy, classification report, and confusion matrix.  

---

## 📊 Model Evaluation  
- **Accuracy Achieved:** ~0.71
- Classification report is available to check complete evaluation.    

---

## 🔢 Confusion Matrix  
The confusion matrix shows how well the model predicts each sentiment:  

| Actual \ Predicted | Negative | Neutral | Positive |
|---------------------|----------|---------|----------|
| **Negative**        | ✅ High  | ❌ Some | ❌ Few    |
| **Neutral**         | ❌ Misclassified | ✅ Moderate | ❌ Few |
| **Positive**        | ❌ Some | ❌ Some | ✅ Good    |

*(Visualization was plotted in the project using sklearn’s `ConfusionMatrixDisplay`.)*  

---

## 🌟 Key Takeaways  
- ✅ Successfully built an **end-to-end sentiment analysis pipeline**.  
- ⚖️ **SMOTE** helped balance dataset but may introduce noise.  
- 📉 Model **overfits** – can be improved by:  
  - Hyperparameter tuning (`max_depth`, `n_estimators`, `criterion`)  
  - Trying other models (Logistic Regression, SVM, XGBoost).  
- 🚀 Real-world airline companies can integrate this system for **customer feedback analysis**.  

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
