# 🛡️ Online Payment Fraud Detection using Machine Learning

![Project Banner](opfd.png)

## 📌 Project Overview

Online payment systems process millions of transactions every day, making them attractive targets for fraudulent activities. Detecting fraud quickly and accurately is essential for reducing financial losses and improving transaction security.

This project analyzes online payment transaction data and builds a Machine Learning model to identify fraudulent transactions using transaction details, account balances, and transaction types.

The project includes:

* 🧹 Data Cleaning & Preprocessing
* 📊 Exploratory Data Analysis (EDA)
* ⚙️ Feature Selection
* 🤖 Machine Learning Model
* 📈 Model Evaluation
* 📊 Data Visualization
* 💡 Fraud Pattern Analysis

---

# 🎯 Project Objectives

* Analyze online payment transaction patterns
* Identify characteristics associated with fraudulent transactions
* Build a machine learning model for fraud detection
* Evaluate model performance using classification metrics
* Generate insights to support fraud prevention strategies

---

# 🗂️ Dataset Information

* **Dataset:** Online Payments Fraud Detection Dataset
* **Source:** Kaggle
* **Records:** 6.3 Million+ Transactions
* **Target Variable:** isFraud
* **Features:** Transaction Type, Amount, Account Balances, Destination Balances, Fraud Indicators

📌 **Note:** The dataset contains both legitimate and fraudulent online payment transactions and is widely used for fraud detection research and learning purposes.

---

# 🛠️ Technologies Used

| Category             | Tools               |
| -------------------- | ------------------- |
| Programming Language | Python              |
| Data Analysis        | Pandas, NumPy       |
| Data Visualization   | Matplotlib, Seaborn |
| Machine Learning     | Scikit-learn        |
| Environment          | Google Colab        |

---

# 🔄 Project Workflow

## 📥 1. Data Collection

* Loaded Online Payment Fraud Detection dataset

## 📊 2. Exploratory Data Analysis (EDA)

* Dataset Preview
* Dataset Structure Analysis
* Statistical Summary
* Missing Value Analysis
* Fraud Distribution Analysis

## 🧹 3. Data Preprocessing

* Removed unnecessary columns
* Checked duplicate records
* Encoded categorical variables
* Prepared data for machine learning

## ⚙️ 4. Feature Selection

Selected relevant features for fraud prediction:

* Transaction Type
* Transaction Amount
* Account Balances
* Destination Account Balances
* Fraud Indicators

## 🤖 5. Machine Learning Model

* Random Forest Classifier

## 📈 6. Model Evaluation

* Accuracy Score
* Precision
* Recall
* F1-Score
* Confusion Matrix

## 📊 7. Visualization & Analysis

* Fraud vs Non-Fraud Transactions
* Transaction Type Distribution
* Fraud Transactions by Type
* Feature Importance Analysis
* Correlation Heatmap
* Confusion Matrix Heatmap

---

# 📌 Key Insights

* 🚨 Fraudulent transactions were primarily associated with **CASH_OUT** and **TRANSFER** transaction types.
* 💰 Transaction amount and account balance information were among the most important features.
* 📊 The dataset was highly imbalanced, with fraudulent transactions representing a very small percentage of total transactions.
* 🤖 The Random Forest model successfully identified most fraudulent activities while maintaining a very low false positive rate.

---

# 🚀 Model Performance

| Metric            | Score      |
| ----------------- | ---------- |
| Accuracy          | **99.97%** |
| Precision (Fraud) | **99%**    |
| Recall (Fraud)    | **77%**    |
| F1-Score (Fraud)  | **87%**    |

---

# 📊 Results

* Achieved **99.97% accuracy** on the test dataset.
* Correctly detected **1,257 fraudulent transactions**.
* Maintained a very low false positive rate.
* Successfully identified important fraud-related transaction patterns.
* Demonstrated the effectiveness of Machine Learning for fraud detection.

---

# 💡 Business Impact

This project can help financial institutions:

* 🛡️ Detect suspicious transactions early
* 💰 Reduce fraud-related financial losses
* 📈 Improve payment security
* 👥 Enhance customer trust
* 📊 Support data-driven fraud prevention strategies

---

# 📂 Repository Structure

```text
online-payment-fraud-detection/
│
├── README.md
├── Online_Payment_Fraud_Detection.ipynb
└── opfd.png
```

---

# 🔮 Future Improvements

* ⚖️ Handle class imbalance using SMOTE
* 🚀 Compare XGBoost and LightGBM models
* 🌐 Deploy using Streamlit
* 📊 Create an interactive Power BI dashboard
* 🔔 Real-time fraud detection system

---

## 👨‍💻 Author

**Ritik Kumar Yadav**

M.Tech Student | Aspiring Data Analyst

* LinkedIn: https://www.linkedin.com/in/ritik-kumar-yadav-70a81435a/
* GitHub: https://github.com/RKYEngineering

---

## ⭐ If you found this project useful, consider giving it a star!
