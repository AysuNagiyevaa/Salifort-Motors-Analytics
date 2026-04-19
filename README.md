# Salifort-Motors-Analytics
Capstone project from Google Advanced Data Analytics

# 🚘 Employee Churn Analysis | Salifort Motors

## 🔍 About the Project

As part of the **Google Data Analytics Capstone**, this project focuses on analyzing employee behavior at Salifort Motors to better understand why employees leave and how to predict potential churn in advance.

The approach combines exploratory data analysis with machine learning to support data-driven HR decisions.

---

## 📉 What the Data Reveals

* Employees assigned to **7 projects consistently leave** the company.
* There is a noticeable spike in turnover around the **4-year tenure mark**.
* Employees working **extreme monthly hours (250+)**, even if high-performing, are more likely to resign.
* The final **Random Forest model** delivers strong performance with a **95% F1-score**, capturing **91% of employees at risk**.

---

## ⚙️ Tech Stack

* **Methodology:** PACE framework
* **Language:** Python
* **Core Libraries:**

  * Pandas (data manipulation)
  * Seaborn (visualization)
  * Scikit-learn (Random Forest, Logistic Regression)

---

## 🧠 Actionable Insights

* Avoid assigning more than **5 concurrent projects** per employee
* Focus retention efforts on employees nearing **4 years at the company**
* Keep track of workloads and take action when hours exceed **~220 per month**
