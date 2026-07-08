# SmartCart Customer Segmentation using K-Means Clustering

## Overview

This project implements an intelligent customer segmentation system for **SmartCart**, an e-commerce platform. Using **unsupervised machine learning**, customers are grouped into meaningful segments based on their purchasing behavior, demographics, and engagement patterns. These insights can help businesses improve personalized marketing, customer retention, and loyalty programs.

## Problem Statement

Traditional marketing strategies often treat all customers similarly, resulting in inefficient campaigns and missed opportunities. This project applies **K-Means Clustering** to identify hidden customer segments and provide data-driven business insights.

## Dataset

The dataset contains **2,240 customer records** with demographic, purchasing, and behavioral information.

### Features

- Customer Demographics
  - Year of Birth
  - Education
  - Marital Status
  - Income
  - Number of Children
  - Customer Enrollment Date

- Purchase Behavior
  - Wine, Fruits, Meat, Fish, Sweets, Gold Products

- Purchase Frequency
  - Web Purchases
  - Store Purchases
  - Catalog Purchases
  - Deal Purchases
  - Monthly Website Visits

- Customer Activity
  - Recency
  - Complaint Status

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Workflow

1. Data Cleaning
2. Exploratory Data Analysis (EDA)
3. Feature Engineering
4. Data Preprocessing
5. Feature Scaling
6. Principal Component Analysis (PCA)
7. K-Means Clustering
8. Elbow Method & Silhouette Score
9. Cluster Visualization
10. Customer Segment Analysis

## Machine Learning Techniques

- K-Means Clustering
- Principal Component Analysis (PCA)
- StandardScaler
- Elbow Method
- Silhouette Score

## Results

The model successfully grouped customers into distinct clusters based on spending habits, purchasing frequency, and customer engagement. These customer segments can be used for:

- Personalized Marketing
- Customer Retention
- Loyalty Programs
- Targeted Promotions
- Business Decision Making

## Repository Structure

```
SmartCart-Customer-Segmentation/
│
├── smartcart.ipynb
├── smartcart_customers.csv
├── README.md
└── images/
```

## Future Improvements

- Compare K-Means with Hierarchical Clustering and DBSCAN
- Deploy the model as a web application
- Build an interactive dashboard using Streamlit or Power BI
- Automate customer segmentation for new customer data

## Author

**Ferdous-M**

- LinkedIn: https://linkedin.com/in/ferdous-m
- GitHub: https://github.com/Ferdous-M
