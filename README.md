# 💳 Credit Card Fraud Detection using Machine Learning

<p align="center">

![Python](https://img.shields.io/badge/Python-3.11-blue?style=for-the-badge&logo=python)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-black?style=for-the-badge&logo=pandas)
![NumPy](https://img.shields.io/badge/NumPy-Scientific%20Computing-blue?style=for-the-badge&logo=numpy)
![Scikit-Learn](https://img.shields.io/badge/Scikit--Learn-ML-orange?style=for-the-badge&logo=scikit-learn)
![XGBoost](https://img.shields.io/badge/XGBoost-Gradient%20Boosting-green?style=for-the-badge)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-orange?style=for-the-badge&logo=jupyter)

</p>

---

## 📌 Project Overview

Credit card fraud has become one of the biggest challenges in digital banking due to the massive volume of online transactions.

This project develops an intelligent fraud detection system capable of identifying fraudulent transactions using Machine Learning while minimizing false positives.

The complete workflow covers:

- Data Cleaning
- Exploratory Data Analysis (EDA)
- Feature Engineering
- Handling Class Imbalance
- Model Training
- Performance Evaluation

---

# 🎯 Business Problem

Financial institutions lose billions of dollars every year because of fraudulent transactions.

The objective is to build a predictive model that accurately distinguishes between:

✅ Genuine Transactions

❌ Fraudulent Transactions

while reducing financial risk.

---

# 📂 Dataset

**Source**

Kaggle Credit Card Fraud Detection Dataset

https://www.kaggle.com/datasets/nelgiriyewithana/credit-card-fraud-detection-dataset-2023

The dataset contains:

- Customer Transactions
- Transaction Amount
- Transaction Time
- Fraud Labels
- Engineered Features

---

# 🛠 Technologies Used

| Category | Tools |
|----------|------|
| Programming | Python |
| Data Analysis | Pandas, NumPy |
| Visualization | Matplotlib, Seaborn |
| Machine Learning | Scikit-Learn, XGBoost |
| Notebook | Jupyter |

---

# 📊 Project Workflow

```
Data Collection
        │
        ▼
Data Cleaning
        │
        ▼
Exploratory Data Analysis
        │
        ▼
Feature Engineering
        │
        ▼
Class Imbalance Handling
        │
        ▼
Model Training
        │
        ▼
Performance Evaluation
        │
        ▼
Fraud Prediction
```

---

# 🔍 Exploratory Data Analysis

Performed:

- Missing Value Analysis
- Duplicate Detection
- Distribution Analysis
- Correlation Analysis
- Fraud vs Non-Fraud Comparison
- Feature Relationships
- Outlier Detection

---

# ⚖ Handling Imbalanced Data

Since fraudulent transactions represent only a small percentage of all transactions, multiple techniques were explored:

- SMOTE
- Random Under Sampling
- Class Weight Adjustment

This improves the model's ability to detect minority-class fraud cases.

---

# 🤖 Machine Learning Models

Implemented multiple algorithms:

- Logistic Regression
- Decision Tree
- Random Forest
- XGBoost

Each model was evaluated and compared.

---

# 📈 Evaluation Metrics

Performance measured using:

- Accuracy
- Precision
- Recall
- F1 Score
- ROC-AUC Score
- Confusion Matrix

Special emphasis was placed on **Recall**, as detecting fraudulent transactions is more important than maximizing overall accuracy.

---

# 📊 Results

The trained model successfully learned patterns that distinguish legitimate and fraudulent transactions.

Key achievements:

✔ High Fraud Detection Capability

✔ Reduced False Positives

✔ Strong Generalization Performance

✔ Suitable for Real-world Banking Applications

---

# 📁 Repository Structure

```
credit-card-fraud-detection/
│
├── ccfd_code.ipynb
├── README.md
├── images/
├── models/
└── dataset/
```

---

# 🚀 How to Run

Clone the repository

```bash
git clone https://github.com/yourusername/credit-card-fraud-detection.git
```

Move into the project

```bash
cd credit-card-fraud-detection
```

Install dependencies

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook

```bash
jupyter notebook
```

Run

```
ccfd_code.ipynb
```

---

# 📌 Future Improvements

- Deep Learning (ANN)
- AutoEncoder based Fraud Detection
- Real-time Fraud Prediction
- Streamlit Web Application
- Explainable AI (SHAP)

---

# 👨‍💻 Author

**Saksham Sharma**

📧 Email: sakshamsharma0905@gmail.com

💼 LinkedIn:
https://linkedin.com/in/saksham-sharma-bb5923253

🌐 GitHub:
https://github.com/Saksham9041

---

⭐ If you found this project useful, consider giving it a star.
