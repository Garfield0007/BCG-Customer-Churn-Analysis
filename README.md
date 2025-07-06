# 📊 PowerCo Churn Prediction – BCG Data Science Virtual Internship

![Made with Python](https://img.shields.io/badge/Made%20with-Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![Executed on Colab](https://img.shields.io/badge/Executed%20on-Google%20Colab-F9AB00?style=for-the-badge&logo=googlecolab&logoColor=white)
![Status: Completed](https://img.shields.io/badge/Status-Completed-brightgreen?style=for-the-badge)

This repository contains my solution to the [Boston Consulting Group (BCG) Data Science Virtual Experience](https://www.theforage.com/virtual-internships/prototype/R5iK7HMqCLqFJc4mO/BCG%20Data%20Science) hosted on Forage.  
The goal of this project was to analyze customer behavior, engineer insightful features, and build a model to predict customer churn.

---

## 🧠 Project Objective

To enable PowerCo to reduce customer churn by analyzing historical data and predicting churners based on behavioral, contractual, and pricing data using machine learning.

---

## 📁 Files Included

### 1. `Feature_Engineering_PowerCo_Kanishka.ipynb`
- Cleaned the dataset and removed irrelevant columns
- Parsed date columns into features like `contract_days`, `activation_year`, `month_renewal`
- Created domain-relevant features:
  - `margin_per_kWh`, `consumption_ratio`, `dual_service`, `recent_price_spike`, etc.

### 2. `PowerCo_Churn_Prediction_Kanishka.ipynb`
- Trained a **Random Forest Classifier** on the engineered dataset
- Evaluated using accuracy, classification report, and ROC AUC
- Observed class imbalance and highlighted future steps for improving recall

---

## 📈 Key Insights

- 🕒 Customers with **shorter contract durations** showed a significantly higher churn rate.  
- 🔌 Customers subscribed to **only electricity (no gas)** were more likely to churn, suggesting bundled services reduce attrition.  
- 📈 Higher **price volatility**, especially in peak pricing, was correlated with churn, implying that stable pricing could improve retention.  
- 📉 Customers contributing **lower net margins per kWh** were more likely to churn, indicating a connection between low profitability and high risk.  
- 🎯 The model achieved:
  - ✅ **Accuracy**: 90.7%  
  - 📉 **Recall for churners**: 4% (highlighting the need for class balancing techniques like SMOTE or weighted models)  
  - 📊 **ROC AUC**: 0.70

---

## ⚙️ Tools & Technologies Used

- Python, Google Colab
- `pandas`, `numpy`
- `matplotlib`, `seaborn`
- `scikit-learn` (RandomForestClassifier, train/test split, metrics)

---

## 🧾 Certificate

![BCG Certificate](https://github.com/Garfield0007/BCG-Customer-Churn-Analysis/blob/main/bcg_certificate.png?raw=true)  

🔗  [View Program on Forage](https://www.theforage.com/simulations/bcg/data-science-ccdz)
- 📜 *Certificate issued to Kanishka Chouhan upon completion*

---

## 👤 Author

**Kanishka Chouhan**  
Data Science Virtual Intern – BCG Forage  
🔗 [ LinkedIn](https://www.linkedin.com/in/kanishka07)

---

> 📌 **Note**: This project was completed as part of an educational virtual internship. The data used is synthetic and for learning purposes only.
