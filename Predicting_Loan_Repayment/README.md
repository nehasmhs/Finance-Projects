# 💳📈 Predicting Loan Repayment with Machine Learning

## 📌 Project Overview
Automating loan approvals enables financial institutions to make **faster, more consistent lending decisions**. However, approving loans that are not repaid can lead to significant financial losses.

In this project, we build a **machine learning classifier** to predict whether a loan will be **fully paid back**, using historical loan data from **LendingClub**.  
The analysis places strong emphasis on:
- **Class imbalance** (fewer defaulted loans)
- **Risk-sensitive evaluation**, where false negatives are more costly than false positives

---

## Business Motivation
From a lender’s perspective:
- ❌ Approving a loan that defaults = **high financial risk**
- ⚠️ Rejecting a good loan = **missed opportunity, but lower risk**

📌 Therefore, the model is designed to **minimize false negatives** — cases where a loan is predicted to be safe but is not repaid.

---

##  Dataset Description
- **Source:** LendingClub.com
- **Size:** 9,500+ loans
- **Type:** Historical loan performance data

### Data Includes:
- Loan structure (amount, interest rate, term)
- Borrower information (credit profile, income-related features)
- Loan outcome: whether the loan was **paid back in full**

---

## Problem Framing
- **Task:** Binary classification
- **Target Variable:**  
  - `Fully Paid`
  - `Not Fully Paid`
- **Key Challenge:** Severe class imbalance

---

##  Analytical Approach

### 1) Data Exploration & Preprocessing
- Explored class distribution and confirmed imbalance
- Handled missing values and feature encoding
- Scaled numerical features where required

---

### 2) Exploratory Data Analysis (EDA)
- Compared borrower and loan characteristics between:
  - Fully paid loans
  - Loans not fully paid
- Identified features strongly correlated with loan repayment risk

---

### 3) Model Development
- Trained multiple classification models
- Applied strategies to handle class imbalance:
  - Class weighting
  - Threshold tuning
- Selected models based on **business-aligned performance**, not accuracy alone

---

### 4) Model Evaluation
Evaluation focused on **risk-sensitive metrics**:

| Metric | Why It Matters |
|------|----------------|
| Recall (Not Fully Paid) | Measures how well risky loans are detected |
| Precision | Controls excessive rejection of good borrowers |
| Confusion Matrix | Highlights false negatives vs false positives |
| ROC-AUC | Overall model discrimination ability |

 *Recall for risky loans was prioritized to reduce approval of bad loans.*

---

##  Key Insights
- Loan defaults are **rare but costly**
- Certain borrower and loan features are strong predictors of repayment
- Adjusting classification thresholds significantly improves risk control
- A balanced accuracy-first approach is **not sufficient** in lending decisions

---

##  Business Impact
- Reduced risk of loan defaults  
- More consistent credit decisions  
- Scalable framework for automated approvals  
- Clear trade-off visibility for stakeholders  

---

##  Tools & Technologies
- **Python**
- **Pandas & NumPy**
- **Matplotlib / Seaborn**
- **Scikit-learn**
- **Machine Learning for Credit Risk**

---

   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
