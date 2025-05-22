# 💳 Credit Card Fraud Detection

## 📅 Project Period
March 2025

## 📘 Project Description
This project focuses on detecting fraudulent credit card transactions using machine learning models. The dataset consists of **284,807 transactions** with **31 features**, including:
- `Time`: Seconds elapsed between this transaction and the first transaction.
- `Amount`: Transaction amount.
- `Class`: Label (1 = Fraud, 0 = Non-fraud).
- `V1–V28`: PCA-transformed features for confidentiality.

The goal is to **build a robust model** that can automatically identify fraudulent transactions, even though the data is highly imbalanced (fraudulent transactions represent only ~0.17%).

## 🔍 Exploratory Data Analysis (EDA)
- Explored the overall structure of the dataset, checking for missing values and class imbalance.
- Analyzed feature distributions using histograms and boxplots to detect outliers.
- Examined correlations between features and the target variable (`Class`).
- Visualized class distribution to highlight the extreme imbalance.

## 🧹 Data Cleaning
- Removed outliers and normalized the `Amount` feature.
- Applied resampling techniques and class weighting to handle class imbalance.
- Ensured data integrity by checking data types and converting time-based columns where needed.

## 🤖 Models Implemented
To handle the class imbalance and improve fraud detection performance, several ensemble models were trained using appropriate class weighting:
- `XGBoost`
- `LightGBM`
- `Random Forest`

Each model was evaluated using:
- **Precision, Recall, F1-score**
- **Confusion Matrix**
- **AUC-ROC Curve**

## ⚙️ Techniques Used
- Class weighting to address data imbalance.
- Grid search and manual tuning of model hyperparameters.
- Performance comparison across models to select the most effective approach.

## 📁 Dataset
The dataset used is the publicly available [Credit Card Fraud Detection dataset on Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud).

---

> 🚀 *This project showcases my ability to explore complex datasets, handle imbalanced classification problems, and apply ensemble machine learning models effectively.*

