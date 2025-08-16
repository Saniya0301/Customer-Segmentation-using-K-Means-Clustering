# 🛍️ Customer Segmentation using K-Means Clustering

This project performs **Customer Segmentation** on the **Mall Customers dataset** using **K-Means Clustering**.  
The goal is to group customers into different clusters based on their **Annual Income**, **Spending Score**, and **Age** to help businesses target specific customer groups effectively.

---

## 📌 Project Overview
- Dataset: **Mall_Customers.csv**
- Features used for clustering:
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1-100)`
- Applied **K-Means clustering** algorithm to group customers.
- Visualized clusters in **2D** and **3D** for better understanding.

---

## 📊 Data Analysis & Visualization
1. **Correlation Matrix** to check relationships between variables.  
2. **Distribution Plots** of:
   - Age  
   - Annual Income  
   - Spending Score  
3. **Gender Distribution** using bar plot.  
4. **Scatter Plot** of Annual Income vs Spending Score.  

---

## 🤖 Clustering
- Used **Elbow Method (WCSS)** to find the optimal number of clusters.  
- Performed clustering in:
  - **2D space** (Annual Income vs Spending Score)  
  - **3D space** (Age, Annual Income, Spending Score)  
- Plotted clusters with distinct colors.  

---


---

## 🚀 Technologies Used
- **Python 3**
- **Libraries**:
  - pandas
  - numpy
  - matplotlib
  - seaborn
  - scikit-learn
  - mpl_toolkits (for 3D visualization)

---

## 📸 Sample Outputs
- Distribution of Age, Income, Spending Score  
- Elbow Method (WCSS curve)  
- 2D Clusters (Income vs Spending Score)  
- 3D Clusters (Age, Income, Spending Score)  

---

## 🎯 Results
- Customers were grouped into **5 clusters**:
  - Cluster 1: High income, high spending customers  
  - Cluster 2: High income, low spending customers  
  - Cluster 3: Low income, high spending customers  
  - Cluster 4: Low income, low spending customers  
  - Cluster 5: Moderate income, moderate spending customers  

This segmentation helps businesses design better **marketing strategies**, **loyalty programs**, and **personalized offers** for each customer group.

---

🙌 Acknowledgements

Dataset: Mall Customers Dataset

Inspired by customer segmentation use cases in marketing analytics.

---
📌 Author:SANIYA CHHABRA



