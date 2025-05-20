# Credit Card Fraud Detection 🛡️💳

This project is a machine learning-based approach to detect fraudulent credit card transactions using various supervised learning techniques. The dataset used in this notebook is a popular anonymized dataset from Kaggle, which contains European card transactions.

## 📌 Project Overview

Credit card fraud detection is a classic imbalanced classification problem. This project aims to:

- Explore and understand the dataset through visualizations and preprocessing.
- Handle imbalanced class distributions effectively.
- Train and evaluate multiple machine learning models.
- Use performance metrics like confusion matrix, ROC-AUC, precision-recall, and F1 score for validation.

---

## 🧠 Technologies Used

- **Python**  
- **Jupyter Notebook**
- **NumPy & Pandas** – Data manipulation
- **Matplotlib & Seaborn** – Data visualization
- **Scikit-learn** – Machine learning models and metrics
- **Imbalanced-learn (SMOTE)** – Handling class imbalance

---

## 📊 Dataset

- Source: [Kaggle - Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- Total transactions: 284,807  
- Fraudulent transactions: 492 (~0.172%)

The dataset features are anonymized using PCA, except for `Time`, `Amount`, and `Class`.

---

## ⚙️ How to Run

1. Clone this repository:
   git clone https://github.com/Siddharth372/Credit-Card-Fraud-Detection.git
   
2. Install dependencies:
   pip install -r requirements.txt
   
3. Download the Dataset:
   from the link download and save it as creditcard.csv
   
5. Launch the notebook:
   jupyter notebook Credit_card_fraud_detection.ipynb
   
