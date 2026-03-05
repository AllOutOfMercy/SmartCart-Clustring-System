# SmartCart-Clustring-System
## Description: 


### Problem Statement

SmartCart is a growing e-commerce platform serving customers across multiple
countries. The company collected extensive customer data consisting of 2240
customer records and 22 attributes including demographics, purchase behaviour,
website activity, and response.

Currently, SmartCart uses generic marketing and engagement strategies for all
customers, without clearly understanding different customer behaviour patterns.
This results in inefficient marketing, missed opportunities to retain high-value
customers, and delayed identification of churn-prone users.

To solve this, SmartCart aims to build an intelligent customer segmentation
system using unsupervised machine learning. The system
analyse historical
customer transaction data and group customers into meaningful clusters based
on purchasing behaviour, engagement levels, and loyalty indicators.

You are hired as an AI/ML Engineer to develop this system using clustering
algorithms to discover hidden patterns in customer behaviour and support data-
driven decision-making for personalised marketing and customer retention.

## Project Summary
* **Data Preprocessing & Feature Engineering:** Cleaned the dataset by handling missing values (e.g., imputing `Income` with the median) and engineered meaningful new features such as `Age`, `Total_Spending`, `Total_Children`, `Customer_Tenure_Days`, and simplified categories for `Education` and marital status (`Living_With`). 
* **Dimensionality Reduction:** Applied Principal Component Analysis (PCA) to reduce the dimensionality of the dataset, capturing the most important variance for optimal cluster separation.
* **Model Evaluation & Optimal K:** Evaluated clustering performance using the Elbow Method (Within-Cluster Sum of Square - WCSS) alongside Silhouette Scores, identifying **4** as the ideal number of customer segments.
* **Clustering Algorithm:** Successfully implemented the **K-Means clustering** algorithm (`n_clusters=4`) on the PCA-transformed data to group the customer base.

## Conclusion
The SmartCart Customer Segmentation System successfully utilized unsupervised machine learning to uncover hidden patterns in the dataset, organizing the 2,240 customer records into 4 distinct and meaningful clusters. This segmentation provides a clear, data-driven understanding of diverse customer purchasing behaviors, engagement levels, and demographics. As a result, SmartCart is now equipped to transition away from generic campaigns and implement highly targeted, personalized marketing strategies. This will ultimately optimize marketing efficiency, improve the retention of high-value customers, and help proactively identify churn-prone users.

