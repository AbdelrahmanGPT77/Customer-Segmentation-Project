# Customer-Segmentation-Project
Retail Customer Segmentation &amp; Sales Prediction using Machine Learning (RFM Analysis, K-Means Clustering, PCA, and Linear Regression).

# 🛒 Retail Transactions Segmentation & Analysis

![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)
![Scikit-Learn](https://img.shields.io/badge/Library-Scikit--Learn-orange.svg)
![Pandas](https://img.shields.io/badge/Library-Pandas-150458.svg)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen.svg)

## 📌 Project Overview
This project focuses on analyzing retail transaction data to perform **Customer Segmentation** and **Sales Prediction**. By identifying key purchasing patterns and grouping customers into meaningful clusters, businesses can optimize targeted marketing strategies, improve customer retention, and forecast sales behavior effectively.

---

## 🛠️ Tech Stack & Libraries
- **Language:** Python
- **Data Manipulation:** `Pandas`, `NumPy`, `datetime`
- **Data Visualization:** `Matplotlib`, `Seaborn`
- **Machine Learning & Analytics:** 
  - `Scikit-Learn` (K-Means Clustering, PCA, Linear Regression, StandardScaler)
  - Metrics: `Silhouette Score`, `R² Score`, `MSE`, `MAE`

---

## 📊 Dataset Structure
The dataset (`retail_transactions_segmentation.csv`) contains **3,663 transaction records** with the following features:

| Column Name | Type | Description |
| :--- | :--- | :--- |
| `customer_id` | Integer | Unique identifier for each customer |
| `transaction_date` | Object/Date | Date when the purchase was made |
| `amount` | Float | Transaction monetary value |
| `product_category` | Object | Category of the purchased item |

---

## 🚀 Workflow & Pipeline

### 1. Data Cleaning & Exploration (EDA)
- Inspected missing values and verified zero null entries across all attributes.
- Conducted **Outliers Analysis** using Interquartile Range (IQR) and visual Boxplots to detect extreme transaction amounts.

### 2. Feature Engineering & Preprocessing
- Processed date features for temporal aggregation.
- Applied **StandardScaler** to normalize feature scales for ML modeling.
- Dimension reduction using **Principal Component Analysis (PCA)** to capture dominant feature variance.

### 3. Customer Segmentation (Clustering)
- Implemented **K-Means Clustering** to aggregate customers into distinct behavioral segments.
- Evaluated optimal cluster quality using **Silhouette Score**.

### 4. Regression & Predictive Modeling
- Built a **Multiple Linear Regression** model to predict transaction amounts and sales trends.
- Evaluated performance using **R² Score**, **Mean Squared Error (MSE)**, and **Mean Absolute Error (MAE)**.

---

## 📈 Key Findings & Impact
- Identified high-value customer clusters for personalized loyalty programs.
- Highlighted transactional distribution across different product categories.
- Provided a foundation for inventory planning based on predicted sales trends.
