# 🛒 Market Basket Analysis using ECLAT  

A project that uncovers hidden purchase patterns using the **ECLAT (Equivalence Class Clustering and bottom-up Lattice Traversal)** algorithm.  It identifies frequent itemsets in transaction data to generate meaningful association rules for decision-making.  Let's dive in 🚀

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

## 📌 Project Overview  
- This project applies **ECLAT** for **Market Basket Analysis** on a groceries dataset.  
- The goal is to identify frequently purchased items together, which can be used for:  
  - Cross-selling strategies  
  - Store layout optimization  
  - Personalized recommendations  

---

## 🎯 Problem Statement  
Retailers need to **understand customer buying behavior** to increase sales and customer satisfaction.  
The challenge is to **mine frequent itemsets** from large transactional data and derive useful rules for decision-making.  

---

## 🧩 Key Features & Terminologies  
- **Transaction**: A set of items bought by a customer at one time.  
- **Itemset**: A group of one or more items.  
- **Support**: Frequency of an itemset in all transactions.  
- **Frequent Itemsets**: Itemsets that satisfy the minimum support threshold.  
- **ECLAT**: Uses a vertical database layout and intersection to quickly find frequent itemsets.  

---

## 🔄 Workflow Summary  
1. **Data Preprocessing**  
   - Loaded the **Groceries Dataset**.  
   - Cleaned and structured transactions for analysis.  

2. **Transaction Transformation**  
   - Converted data into transaction format suitable for ECLAT.  

3. **Model Training (ECLAT Algorithm)**  
   - Applied the ECLAT algorithm using **apyori**.  
   - Extracted frequent itemsets and association rules.  

4. **Results Extraction**  
   - Converted rules into a **structured DataFrame**.  
   - Displayed top frequent rules for insights.  

---

## 📊 Model Evaluation  
Since ECLAT is unsupervised, evaluation is based on:  
- **Support** → Measures item frequency.   
- **Interpretability** → How meaningful and actionable the rules are.  

---

## 📝 Results (Rules Extracted)  
- Extracted **frequent itemsets** showing strong associations.  
- Example:  
  - `{whole milk} → {yogurt}` (high support and relevance).  
- Converted results into a DataFrame for readability.  

---

## 🚀 Key Takeaways  
- **ECLAT** is efficient for **frequent itemset mining**.  
- Helps businesses in:  
  ✅ Better marketing strategies  
  ✅ Personalized recommendations  
  ✅ Improved inventory management  

---

# 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
