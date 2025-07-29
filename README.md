# Enhancing Financial Fraud Detection Using Advanced Anomaly Detection Models

## 📘 Project Background

With the rapid growth of digital banking and online financial services, financial institutions face increasing threats of fraud. Traditional rule-based systems are no longer sufficient. This project explores the development and evaluation of advanced anomaly detection models using machine learning and deep learning techniques to enhance fraud detection in banking transactions.

The dataset includes 200 randomly sampled transactions from Kaggle, representing debit and credit transactions through various channels. The project uses supervised, unsupervised, and hybrid models to identify fraudulent activities based on transactional, behavioral, demographic, and geographic features.

## 📊 Files Included

- **Dashboard.twbx**: Tableau dashboard summarizing key insights .
- **raw_banking_transactions.csv**: The raw dataset of 200 banking transactions.
- **cleaned_dataset.xlsx**: Preprocessed version with outliers removed and features engineered.
- **README.md**: This file—project summary, insights, and methodology.
- **final_report.pdf**: Full research report .

---

## 📁 Dataset Overview

- **Source**: Kaggle (public dataset, sampled using random method).
- **Sample Size**: 200 transactions
- **Format**: CSV converted to Excel for processing
- **Attributes**:
  - `Transaction ID`, `Transaction Amount`, `Transaction Type`
  - `Channel`, `Location`, `Device ID`, `IP Address`
  - `Customer Age`, `Occupation`, `Login Attempts`, `Duration`
  - `Account Balance`, `Merchant ID`, `Previous Transaction Date`

---

## 🔍 Key Metrics Summary

| Metric                | Value Range        | Insight                              |
|-----------------------|--------------------|--------------------------------------|
| Transaction Amount    | $0.32 – $1,241.05  | Right-skewed, most under $300        |
| Customer Age          | 18 – 80 years      | Wide demographic distribution        |
| Login Attempts        | 1 – 5              | Multiple attempts may signal fraud   |
| Account Balance       | $120 – $14,000+    | High-risk accounts need monitoring   |
| Channels              | Branch, Online, ATM| Online & ATM dominate (~65%)         |

---

## 💡 Executive Summary

The project demonstrates that:
- **Digital channels** (Online/ATM) dominate modern banking and require enhanced monitoring.
- **Debit transactions** account for 75% of the data and are the most fraud-prone.
- **High-value and high-frequency login attempts** are often associated with suspicious behavior.
- **Machine learning models** like Isolation Forests and Autoencoders show strong potential in identifying fraudulent patterns.
- **Demographic and behavioral features** significantly enhance model accuracy.

---

## 📈 Key Insights

### 🔐 Transaction Trends
- **Debit vs Credit**: Debit = 73%, Credit = 27%
- **Channel Usage**: Online and ATM dominate over Branch usage
- **Login Attempts**: Majority (70%) successful on first try; the rest need further analysis

### 👤 Demographics
- Age group 55–64 and 65+ comprise 40% of customers
- Professions: Engineers, Doctors, Students, Retirees

### 🌍 Geographic Hotspots
- Top cities: Los Angeles, Miami, New York
- These regions may require location-specific fraud profiling

---

## 🤖 Models Used

| Model Type        | Algorithms                            |
|-------------------|----------------------------------------|
| Supervised        | Logistic Regression, Random Forest     |
| Unsupervised      | Isolation Forest, Autoencoders         |
| Hybrid            | GNN + Tree Ensembles (optional)        |

- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score, AUC
- **Tools**: Python, Scikit-learn, TensorFlow, Keras, SHAP, LIME

---

## 🔐 Recommendations

1. **Invest in behavioral anomaly detection**, especially tracking login frequency and transaction duration.
2. **Prioritize real-time fraud detection systems** for online and ATM transactions.
3. **Use explainable AI tools** like SHAP to make model decisions transparent to stakeholders and regulators.
4. **Enhance data diversity** by integrating more sources including unstructured data (e.g., chat logs).
5. **Adopt federated learning** or privacy-preserving techniques for cross-institutional fraud detection.

---

## 📌 Tools & Technologies

- **Languages**: Python
- **Libraries**: pandas, scikit-learn, matplotlib, seaborn, TensorFlow, Keras, SHAP, LIME
- **Visualization**: Tableau (Dashboard.twbx)
- **Environment**: Jupyter Notebook

---

## 📬 Contact

For questions or feedback:
**Vishwas Anand**  
📧 https://www.linkedin.com/in/vishwasanand/  
📝 MBA - Business Intelligence & Analytics  
Jain University, Bangalore

---

## ✅ License

MIT License 

