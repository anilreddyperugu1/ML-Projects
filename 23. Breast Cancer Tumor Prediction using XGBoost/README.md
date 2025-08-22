# 🩺 Breast Cancer Tumor Prediction — Classic ML vs. XGBoost

Build a reliable classifier to distinguish benign vs. malignant tumors using multiple ML models. Compare baselines with **XGBoost** to see how gradient boosting shines on tabular, linearly separable data. Let's dive in✨

---

## 📑 Index
1. [Project Overview](#-project-overview)
2. [Problem Statement](#-problem-statement)
3. [Dataset](#-dataset)
4. [Key Features & Terminologies](#-key-features--terminologies)
5. [Libraries Used](#-libraries-used)
6. [Workflow Summary](#-workflow-summary)
7. [Models & Settings](#-models--settings)
8. [Results & Evaluation](#-results--evaluation)
9. [Confusion Matrix](#-confusion-matrix)
10. [Key Takeaways](#-key-takeaways)

---

## 📘 Project Overview
This project trains several classifiers on the **Breast Cancer Wisconsin (Original)** dataset and then applies **XGBoost** for a boosted comparison.  
You’ll find a clean pipeline: load → preprocess → train/test split (stratified) → cross-validation → metrics & plots. ✅

---

## ❓ Problem Statement
Accurately classify **breast tumor cells** as **benign (0)** or **malignant (1)** using tabular features so clinicians can prioritize follow-ups and reduce false alarms. 🎯

---

## 🗂 Dataset
- Source file: `dataset.csv` (classic **Wisconsin Breast Cancer (Original)** layout).
- Dropped non-informative ID: **`Sample code number`**.
- Original target: **`Class`** with values `{2: benign, 4: malignant}`.
- Mapped to **binary `Target`**:  
  - `0` ← Class `2` (Benign)  
  - `1` ← Class `4` (Malignant)

> ✅ Features (`X`) built from all columns **except** `Class`/`Target`.  
> ✅ Target (`y`) = `Target`.

---

## 🧩 Key Features & Terminologies

- **Cross-Validation (CV)**: estimates generalization by averaging scores over folds 🔁.
- **Classification Report**: Precision/Recall/F1 per class 📄.
- **Confusion Matrix**: TP/FP/FN/TN overview for error analysis 🔷.
- **XGBoost**: gradient boosting with tree ensembles 🚀 (strong on tabular data).

---

## 🧰 Libraries Used
- **Core**: `numpy`, `pandas`, `matplotlib`
- **Modeling**: `scikit-learn` (`train_test_split`, `StratifiedKFold`, classifiers, metrics)
- **Boosting**: `xgboost` → `XGBClassifier`

---

## 🔄 Workflow Summary
1. **Load & Inspect** 🧼  
   Read `dataset.csv`, check shape/info/head to validate schema.
2. **Preprocess** 🧹  
   Drop `Sample code number`; build `X`/`y`; map `Class`→`Target` (`0/1`).
3. **Split** ✂️  
   `train_test_split(X, y, test_size=0.2, stratify=y, random_state=32)`.
4. **Baselines** 🏁  
   Train: **LR**, **DTC**, **KNN**, **NB**, **SVC (gamma='auto')**, **LDA**.  
   Used **StratifiedKFold(n_splits=10)** + `cross_val_score(..., scoring='accuracy')`.  
   Plot mean CV accuracy per model (bar chart).
5. **XGBoost** 🚀  
   Train `XGBClassifier()` on the same split; evaluate on test; print **classification report** and plot **confusion matrix**.
6. **Compare & Conclude** 🏆  
   Contrast CV accuracy and test metrics; summarize strengths.

---

## 🤖 Models & Settings
- **Logistic Regression**: `solver='lbfgs'`, `max_iter=2000`
- **DecisionTreeClassifier**
- **KNeighborsClassifier**
- **GaussianNB**
- **SVC(gamma='auto')**
- **LinearDiscriminantAnalysis**
- **XGBClassifier** (default hyperparameters)

> 🔁 CV: `StratifiedKFold(n_splits=10)` → stable, class-balanced folds.

---

## 📈 Results & Evaluation
- **Cross-Validation (10-fold)**:  
  The notebook prints per-model mean ± std; XGBoost shows **consistently perfect scores** across folds in this setup (evidence of **linearly/perfectly separable** features). ✅
- **XGBoost Test Metrics**:  
  A **classification report** is printed (Precision/Recall/F1 per class) and a **confusion matrix** is plotted. In runs observed during development, XGBoost achieved **nearly-perfect** metrics (e.g., mean CV = **0.96**). 🥇

---

## 🧮 Confusion Matrix
The notebook renders a confusion matrix with labels `[0, 1]` (Benign, Malignant).  
Interpretation cheat-sheet:
- **Top-left (TN)**: Benign correctly predicted benign.
- **Top-right (FP)**: Benign predicted as malignant (false alarm).
- **Bottom-left (FN)**: Malignant predicted as benign (missed cancer) ⚠️
- **Bottom-right (TP)**: Malignant correctly predicted malignant.
---

## 🏁 Key Takeaways
- **XGBoost** delivered **state-of-the-art performance** on this classic dataset 🚀.
- **Stratified CV** ensured reliable estimates across folds 🔁.
- When results are **perfect**, double-check with **noise tests**, **repeated CV**, or **external validation** to confirm real-world reliability 🧠.
- The pipeline is compact and reproducible — great for learning and demos 📚.

---

## 📇 Author

Anil Reddy Perugu💝

📧 Email: peruguanilreddy6@gmail.com

📍 Feel free to reach out for queries, suggestions, or collaborations!
