# Customer Segmentation (Clustering – snsdata)
Customer segmentation using K-Means clustering with PCA visualization and data preprocessing for marketing insights.

# 📊 Customer Segmentation using K-Means Clustering

## Description
Customer segmentation using K-Means clustering with PCA visualization and data preprocessing for marketing insights.

---

## Overview
This project applies **unsupervised machine learning (clustering)** to segment customers based on their social networking data (snsdata).  

It helps identify distinct customer groups that can be used for **targeted marketing and business decision-making**.

---

## Problem Statement
Businesses need to understand customer behavior to improve engagement and targeting.

The goal is to:
- Group similar customers into clusters  
- Identify patterns in user interests  
- Enable data-driven marketing strategies  

---
## Project Workflow

### 🔹 Data Preprocessing
- Loaded dataset (`snsdata.csv`)  
- Handled missing values using median and default values  
- Selected numeric features for clustering  

---

### 🔹 Feature Scaling
- Applied **StandardScaler** for normalization  
- Ensured all features contribute equally to clustering  

---

### 🔹 Clustering Model

Applied **K-Means Clustering**

- Used **Elbow Method** to determine optimal number of clusters  
- Grouped customers into distinct segments  

---

### 🔹 Dimensionality Reduction

Applied **PCA (Principal Component Analysis)**  

- Reduced high-dimensional data to 2 dimensions  
- Visualised clusters effectively  

---

## Results

- Identified **distinct customer segments** based on behaviour  
- Visualised clusters using PCA  
- Enabled insights for targeted marketing  

---

## Tech Stack

- **Language:** Python  
- **Libraries:**
  - pandas, numpy  
  - scikit-learn  
  - matplotlib, seaborn  

---

## 📂 Project Structure
