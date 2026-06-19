# 🛒 SmartCart Customer Segmentation System

A Machine Learning project that analyzes customer purchasing behavior and segments customers into distinct groups using K-Means Clustering. The system helps businesses understand customer patterns, improve marketing strategies, and deliver personalized recommendations.

---

## 📌 Project Overview

Customer segmentation is an important business strategy that helps organizations identify groups of customers with similar purchasing behaviors.

This project uses **K-Means Clustering** to segment customers based on demographics, income, spending habits, and purchasing activities.

The optimal number of clusters is determined using:

- Elbow Method
- Knee Point Detection
- Silhouette Score Analysis

---

## 🎯 Objectives

- Analyze customer demographics and spending behavior
- Identify meaningful customer segments
- Determine optimal cluster count
- Visualize customer groups
- Support targeted marketing campaigns

---

## 📊 Dataset Features

### Customer Information

| Feature | Description |
|----------|------------|
| ID | Unique Customer ID |
| Year_Birth | Customer Birth Year |
| Education | Education Level |
| Marital_Status | Marital Status |
| Income | Annual Income |
| Kidhome | Number of Children at Home |
| Teenhome | Number of Teenagers at Home |
| Dt_Customer | Date of Customer Enrollment |
| Recency | Days Since Last Purchase |

### Product Spending Features

| Feature | Description |
|----------|------------|
| MntWines | Amount Spent on Wines |
| MntFruits | Amount Spent on Fruits |
| MntMeatProducts | Amount Spent on Meat Products |
| MntFishProducts | Amount Spent on Fish Products |
| MntSweetProducts | Amount Spent on Sweet Products |
| MntGoldProds | Amount Spent on Gold Products |

### Purchase Behavior Features

| Feature | Description |
|----------|------------|
| NumDealsPurchases | Purchases Made with Discount |
| NumWebPurchases | Purchases Through Website |
| NumCatalogPurchases | Purchases Through Catalog |
| NumStorePurchases | Purchases Through Store |
| NumWebVisitsMonth | Monthly Website Visits |

### Campaign Features

| Feature | Description |
|----------|------------|
| Complain | Customer Complaint Indicator |
| Response | Marketing Campaign Response |

---

## ⚙️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-Learn
- Jupyter Notebook

---

## 🤖 Machine Learning Algorithms

### 1. K-Means Clustering

Used to divide customers into distinct groups based on similar characteristics.

### 2. Elbow Method

Used to identify the optimal number of clusters by analyzing Within Cluster Sum of Squares (WCSS).

### 3. Knee Point Detection

Used to automatically detect the turning point in the Elbow Curve.

### 4. Silhouette Score

Evaluates cluster quality by measuring how similar a customer is to its own cluster compared to other clusters.

---

## 📈 Workflow

1. Data Collection
2. Data Cleaning
3. Exploratory Data Analysis (EDA)
4. Feature Engineering
5. Data Scaling
6. Elbow Method Analysis
7. Knee Point Detection
8. Silhouette Score Evaluation
9. K-Means Clustering
10. Cluster Visualization
11. Customer Segment Interpretation

---

## 🚀 Business Applications

- Personalized Marketing
- Customer Retention
- Product Recommendations
- Loyalty Programs
- Customer Lifetime Value Analysis
- Targeted Advertising

--- 

## 📊 Results

The model successfully grouped customers into meaningful segments based on:

- Spending Habits
- Income Levels
- Purchase Frequency
- Product Preferences
- Marketing Campaign Responses

These insights can help businesses make data-driven marketing decisions and improve customer engagement.

---

## 👨‍💻 Author

Mahendra Pawar

Computer Engineering Student | Machine Learning Enthusiast

