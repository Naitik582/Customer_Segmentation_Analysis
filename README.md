<h1>Customer Segmentation Analysis</h1>

**Project Overview**

This project focuses on segmenting customers based on their purchasing behavior using clustering techniques. By analyzing customer data, businesses can create targeted marketing strategies and improve customer satisfaction.

**Key Objectives**

1. Data Cleaning & Exploration: Handle missing values and understand data distribution.

2. Feature Engineering: Select relevant features for clustering.

3. Clustering (K-Means): Group customers into meaningful segments.

4. Visualization: Use PCA for cluster visualization.

5. Insights & Recommendations: Understand customer behavior for business decisions.


**Technologies Used**

• Python (Pandas, NumPy, Scikit-Learn, Matplotlib, Seaborn)

• Google Colab (for data analysis & visualization)


**Dataset Details**

File: ifood_df.csv

Features: Income, Recency, Total Spending, Age, Purchase Frequency, Website Visits

Size: Medium dataset (~2000+ customers)


**Key Steps**

1. Data Cleaning & Feature Engineering

2. Removed unnecessary columns

3. Selected important features like Income, Recency, Total Spending, etc.

4. Scaled the data using StandardScale

**Clustering with K-Means**

1. Used the Elbow Method to find the optimal number of clusters

2. Applied K-Means Clustering with K=4

3. Assigned cluster labels to each customer


**Cluster Visualization**

1. Used PCA (Principal Component Analysis) to reduce dimensions and plot clusters

2. Created Boxplots to analyze spending patterns in each cluster


**Insights & Recommendations**

1. High-Income Customers: Spend the most, prefer premium products

2. Frequent Shoppers: Make smaller but more frequent purchases

3. Low-Income Customers: Spend cautiously, respond well to discounts

4. Inactive Customers: Need re-engagement strategies (emails, discounts, ads)


**Data Visualizations**

1. Customer Segmentation Scatter Plot (PCA)

2. Income vs Spending Analysis (Boxplot)

3. Cluster-wise Spending Behavior


