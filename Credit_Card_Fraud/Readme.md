# 💳🔍 Credit Card Fraud Detection:

## 📌 Project Overview
A new credit card company has entered the western U.S. market with a bold promise: **industry-leading transaction security**.  
As the company’s **Data Scientist**, my responsibility is to identify potentially fraudulent credit card transactions using historical transaction data.

This project focuses on building and evaluating a **fraud detection model** that prioritizes **customer safety** — even if that means occasionally flagging legitimate transactions as fraudulent.

---

##  Business Objective
Design a predictive model that:
- Accurately identifies fraudulent transactions
- **Minimizes false negatives** (missed fraud cases)
- Accepts a higher number of false positives to err on the side of caution

*In fraud detection, missing fraud is far more costly than investigating a false alert.*

---

## Dataset Description
The dataset contains anonymized credit card transaction data, including:
- Transaction-level features
- Behavioral and monetary attributes
- A target label indicating whether a transaction was fraudulent

---

## Analytical Approach

### 1) Data Understanding & Preparation
- Explored transaction distributions and class imbalance
- Handled missing values and outliers
- Scaled and transformed features where necessary

 *Fraud datasets are highly imbalanced — this was a key consideration throughout the analysis.*

---

### 2) Exploratory Data Analysis (EDA)
- Compared patterns between fraudulent and non-fraudulent transactions
- Identified features strongly associated with fraud
- Visualized distributions and correlations to guide modeling

---

### 3) Model Development
- Framed the problem as a **binary classification task**
- Tested multiple models (e.g., Logistic Regression, Tree-based models)
- Tuned decision thresholds to **favor fraud detection recall**

---

### 4) Model Evaluation
Model performance was evaluated using metrics aligned with business risk:

| Metric | Why It Matters |
|------|----------------|
| Recall (Fraud Class) | Measures how much fraud we successfully catch |
| Precision | Indicates how many flagged transactions are actually fraud |
| Confusion Matrix | Visualizes false positives vs false negatives |
| ROC-AUC | Overall classification performance |
 *Recall was prioritized over precision per business requirements.*

---

## Key Findings
- The model successfully identifies the **majority of fraudulent transactions**
- Increasing recall leads to more false positives, which aligns with the company’s safety-first strategy
- Feature patterns reveal that fraudulent transactions differ significantly in behavior and scale

---

## Business Impact
-Reduced risk of undetected fraud  
-Improved customer trust and brand safety  
-Scalable approach for real-time fraud monitoring  
-Clear tradeoff visibility for executives  

---

## Tools & Technologies
- **Python**
- **Pandas & NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn**
- **Classification metrics & model evaluation**

---

## How to Run the Project
1. Clone the repository
2. Install dependencies:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
