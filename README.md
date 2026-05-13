# 📊 Customer Retention & Churn Analysis

## 🎯 Objective

Analyze customer behavior to identify churn patterns, retention drivers, and customer lifetime trends using real-world multi-source data.

---

## 📁 Dataset

This project integrates multiple datasets:

* Accounts (customer info)
* Subscriptions (plan details)
* Churn events (actual churn labels)
* Feature usage (engagement behavior)
* Support tickets (customer issues)

---

## 🧠 Methodology

* Merged multiple datasets using `account_id`
* Engineered key features:

  * Churn (binary classification)
  * Customer lifetime (days)
  * Usage intensity
* Performed cohort analysis to track retention over time
* Conducted behavioral segmentation (usage & support activity)

---

## 📈 Key Metrics

* **Retention Rate**
* **Churn Rate**
* **Average Customer Lifetime**

---

## 🔍 Key Insights

* 📉 Majority of churn occurs within the **first 30 days**
* ⚡ Customers with **low feature usage churn significantly more**
* 💎 **Premium plans show higher retention** compared to basic plans
* 🛠 Customers with **frequent support tickets have higher churn risk**

---

## 💡 Recommendations

* Improve onboarding experience to reduce early churn
* Increase feature adoption through guided tutorials
* Enhance customer support efficiency
* Promote long-term subscription plans

---

## 📊 Visualizations

### Churn by Subscription Plan

![Churn Chart](images/churn_chart.png)

### Cohort Retention Heatmap

![Cohort Heatmap](images/cohort_heatmap.png)

---

## ▶️ How to Run

1. Clone this repository
2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```
3. Open the notebook in Jupyter or Google Colab
4. Run all cells

---

## 🛠 Tools Used

* Python (Pandas, NumPy)
* Matplotlib & Seaborn (Visualization)
* Google Colab

---

## 🚀 Future Work

* Build a machine learning model for churn prediction
* Develop an interactive dashboard using Power BI or Tableau
