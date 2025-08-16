# 🛒 Market Basket Analysis using Apriori  

A project that applies the **Apriori algorithm** to discover frequent itemsets and association rules in transactional data.  It helps uncover **hidden patterns** in customer purchase behavior for better decision-making.  Let's dive in 🚀

---

## 📑 Index  
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 📚 [Key Features & Terminologies](#-key-features--terminologies)  
4. 🔄 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)
6. 📝 [Results (Rules Extracted)](#-results-rules-extracted)
7. 🎯 [Key Takeaways](#-key-takeaways)  

---

## 🔎 Project Overview  
This project implements the **Apriori algorithm** using the `apyori` library.  It identifies strong association rules among items purchased together, enabling businesses to optimize product placement, promotions, and cross-selling strategies.  

---

## ❓ Problem Statement  
Retailers often struggle to understand **which products are frequently bought together**.  The goal is to analyze transactional data and extract rules that describe item relationships, supporting **data-driven sales strategies**.  

---

## 🧾 Key Features & Terminologies  
- **Transactions**: Each row of the dataset represents items bought in a single purchase.  
- **Support** 📊: Probability that items appear together in the dataset.  
- **Confidence** ✅: Likelihood that item B is purchased given item A.  
- **Lift** 📈: Measure of how much more likely A and B occur together compared to being independent.  

---

## 🔄 Workflow Summary  
1. **Data Preprocessing**  
   - Loaded dataset, handled missing values, and created transaction lists.  
2. **Model Training**  
   - Applied Apriori with parameters:  
     - `min_support = 0.02`  
     - `min_confidence = 0.3`  
     - `min_lift = 1.2`  
     - `min_length = 2`  
3. **Rule Extraction**  
   - Converted raw Apriori results into a structured DataFrame (LHS, RHS, Support, Confidence, Lift).  

---

## 📊 Model Evaluation  
- we evaluated rules using:  
  - **Support** (frequency of itemset)  
  - **Confidence** (strength of implication)  
  - **Lift** (strength of association beyond chance).  

---

## 📝 Results (Rules Extracted)  
Example output from association rules:  

| Left Hand Side | Right Hand Side | Support | Confidence | Lift |
|----------------|-----------------|---------|------------|------|
| Item A         | Item B          | 0.05    | 0.45       | 1.35 |
| Item C         | Item D          | 0.04    | 0.38       | 1.25 |

---

## 🚀 Key Takeaways  
- Apriori effectively reveals **hidden associations** in large transaction datasets.  
- Helps businesses with:  
  - Product bundling 🎁  
  - Store layout optimization 🏬  
  - Personalized recommendations 🤝  
- Lift values > 1 indicate **meaningful associations** worth leveraging.  

---

# 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
