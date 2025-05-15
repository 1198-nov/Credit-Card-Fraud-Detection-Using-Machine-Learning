# 💳 Credit Card Fraud Detection Using Machine Learning

## 📌 Abstract
Credit card fraud causes billions of dollars in losses each year. In this project, we aim to detect fraudulent credit card transactions using machine learning algorithms. By analyzing historical transaction data, the models are trained to identify patterns and anomalies that indicate fraud. This project leverages various machine learning techniques including K-Nearest Neighbors, Support Vector Machine, Logistic Regression, and Decision Tree classifiers.

---

## 📈 Project Overview

With the global number of credit card users reaching 2.8 billion in 2019 and a sharp rise in fraud reports (up 44.7% in 2020 in the U.S.), it has become crucial to ensure transaction security. This project uses supervised machine learning techniques to classify credit card transactions as fraudulent or non-fraudulent. The comparative analysis helps determine the most effective model in detecting fraudulent activities in real-world scenarios.

---

## 🎯 Project Goals

- Detect fraudulent credit card transactions accurately.
- Compare multiple machine learning algorithms.
- Visualize and analyze model performance.
- Suggest future improvements and real-world applicability.

---

## 📊 Dataset

- **Source**: [Kaggle Credit Card Fraud Dataset](https://www.kaggle.com/mlg-ulb/creditcardfraud)
- **Size**: 284,808 transactions
- **Features**: 31 attributes (28 anonymized using PCA, 3 original: `Time`, `Amount`, and `Class`)
- **Class Distribution**: Highly imbalanced, with only ~0.17% fraudulent transactions

| Feature | Description |
|--------|-------------|
| Time | Seconds elapsed between this and the first transaction |
| Amount | Transaction amount |
| Class | Target variable (0 = non-fraud, 1 = fraud) |

---

## 🧠 Algorithms Used

- 🔹 K-Nearest Neighbors (KNN)
- 🔹 Logistic Regression
- 🔹 Support Vector Machine (RBF Kernel)
- 🔹 Decision Tree

---

## 📊 Model Performance

| Model               | Accuracy | Precision | Recall  | F1-Score | ROC-AUC |
|---------------------|----------|-----------|---------|----------|---------|
| **KNN**             | 99.94%   | 88.67%    | 82.94%  | -        | -       |
| **Logistic Regression** | 85.71%   | 91.37%    | 93.54%  | 88.77%   | 93.5%   |
| **Decision Tree**   | 91.09%   | 99.91%    | 74.28%  | 75.91%   | 95.1%   |
| **SVM (RBF Kernel)**| 75.09%   | 93.58%    | 95.87%  | 96.8%    | 90.73%  |

> ✅ KNN and Decision Tree achieved the highest accuracy but differ in recall, an important metric for fraud detection.

---

## 🔮 Future Work

- Apply models to larger and more diverse datasets
- Integrate location data using telecom datasets for enhanced fraud detection
- Improve data preprocessing and feature engineering for better performance
- Deploy as a real-time fraud detection API or system

---

## ✅ Conclusion

This project demonstrates the application of various machine learning techniques for detecting fraudulent credit card transactions. Among the models tested, **KNN** and **Decision Tree** delivered the best results in terms of accuracy. The analysis helps improve customer experience and trust in digital transactions by enhancing fraud detection capabilities.

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy, Scikit-learn
- Matplotlib, Seaborn
- Jupyter Notebook

---

## 📁 Project Structure

