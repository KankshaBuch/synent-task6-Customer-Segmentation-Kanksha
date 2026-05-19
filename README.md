# synent-task6-Customer-Segmentation-Kanksha
# Customer Segmentation using K-Means Clustering

## Overview
This project focuses on customer segmentation using the K-Means Clustering machine learning algorithm on the Mall Customer dataset. The goal is to group customers based on purchasing behavior.

## Objective
- Segment customers based on behavior
- Analyze spending patterns
- Apply unsupervised machine learning
- Visualize customer groups

## Technologies Used
- Python
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

## Dataset Features
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Steps Performed

### 1. Data Understanding
Performed:
- head()
- info()
- describe()
- isnull()
- duplicated()

to understand dataset structure and quality.

### 2. Feature Selection
Selected:
- Annual Income
- Spending Score

for customer behavior analysis.

### 3. Data Visualization
Created scatter plots to analyze customer distribution and identify visible grouping patterns.

### 4. Elbow Method
Applied the Elbow Method to determine the optimal number of clusters using WCSS values.

### 5. K-Means Clustering
Implemented K-Means Clustering algorithm with:
- optimal K value = 5

### 6. Cluster Visualization
Visualized:
- customer segments
- cluster centroids
- customer behavior groups

## Key Insights
- Customers were successfully divided into distinct segments.
- High-income high-spending customers represented premium customers.
- Some customers had high income but low spending behavior.
- Different customer groups can help businesses improve targeted marketing strategies.

## Conclusion
This project demonstrated:
- unsupervised machine learning,
- clustering techniques,
- feature selection,
- customer behavior analysis,
- and data visualization concepts.

It also provided practical understanding of K-Means Clustering and business-oriented customer segmentation.
