# 🎯 Ads Recommendation using Upper Confidence Bound (UCB)

A machine learning project implementing the **Upper Confidence Bound (UCB)** algorithm to optimize ad recommendations.  The goal is to maximize user clicks by balancing **exploration** of new ads and **exploitation** of known high-performing ads.   Let's dive in 🚀

---

## 🧭 Index
1. 📌 [Project Overview](#-project-overview)  
2. 🎯 [Problem Statement](#-problem-statement)  
3. 🗝️ [Key Features & Terminologies](#-key-features--terminologies)  
4. 🔄 [Workflow Summary](#-workflow-summary)  
5. 📊 [Model Evaluation](#-model-evaluation)
6. 🎯 [Key Takeaways](#-key-takeaways)

---

## 🚀 Project Overview
This project implements the **Upper Confidence Bound (UCB)** algorithm to solve an **ad recommendation** (multi-armed bandit) problem.  
Given multiple ads with unknown click-through rates, UCB balances **exploration vs. exploitation** to **maximize total clicks (rewards)** over time.

The notebook loads a dataset (`dataset.csv`), runs UCB over **N rounds** and **d = 10 ads**, and visualizes how often each ad was selected.

---

## 🧩 Problem Statement
- You have **10 ads** (`d = 10`).  
- For each of **N users/rounds**, you must choose **one ad** to show.  
- After showing an ad, you observe a **binary reward**: `1` if clicked, `0` otherwise.  
- Goal: **maximize cumulative reward** (total clicks) by learning which ad works best while still exploring others.

---

## 🧩 Key Features & Terminologies 
- **Multi-Armed Bandit:** Framework where each “arm” (ad) yields stochastic rewards.
- **Reward:** Click (`1`) or no click (`0`) from the displayed ad.
- **Exploration vs. Exploitation:** Try less-known ads vs. use the current best ad.
- **Cumulative Reward:** Sum of all observed clicks.
- **Regret (conceptual):** Gap between achieved reward and reward of always picking the optimal ad.

---

## 🔁 Workflow Summary
- **Libraries:** `numpy`, `pandas`, `math`, `matplotlib`.
- **Data Loading & Quick EDA:**
- **Core UCB Implementation:**

---

## 📏 Model Evaluation
Since this is an **online bandit** (not a classifier), we focus on reward-centric metrics:
- **Total/Cumulative Reward:** sum(sum_of_rewards) → total clicks obtained.
- **Per-Ad Rewards:** Vector printed as Rewards by ads = [120, 47, 7, 38, 1675, 1, 27, 236, 20, 7]
- **Selection Distribution:** From the histogram; the algorithm should increasingly favor the best ad(s).
- **Average Reward:** total_reward / N (proxy for CTR across all rounds).

---

## 🧠 Key Takeaways
- ✅ UCB provides a principled way to balance exploration/exploitation using confidence bounds.
- 📈 The algorithm quickly converges to high-performing ads while still sampling others occasionally.
- 🧪 Early rounds prioritize exploration (infinite UCB for unseen ads); later rounds exploit the best ad(s).
- ⚡ Simple, fast, and effective for recommendation settings where user feedback arrives online.

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
