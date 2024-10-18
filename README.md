# RFM Segmentation

## Project Overview

This project focuses on RFM (Recency, Frequency, Monetary) analysis to segment customers based on their purchasing behavior. The goal is to identify key customer segments that contribute significantly to revenue and tailor marketing strategies accordingly.

## Table of Contents

- [Project Overview](#project-overview)
- [What is RFM Analysis?](#what-is-rfm-analysis)
- [Data Cleaning](#data-cleaning)
- [RFM Analysis and Clustering](#rfm-analysis-and-clustering)
- [Customer Segmentation](#customer-segmentation)
- [Market Recommendations](#market-recommendations)
- [Conclusions and Recommendations](#conclusions-and-recommendations)
- [Contributors](#contributors)

## What is RFM Analysis?

RFM analysis is a method used to segment customers by examining three key factors:
- **Recency**: How recently a customer made a purchase.
- **Frequency**: How often a customer makes a purchase.
- **Monetary Value**: How much money a customer spends.

These metrics help in understanding customer behavior, affecting lifetime value and retention.

## Data Cleaning

The dataset contains 541,909 rows and 8 columns with missing values in 'Description' and 'CustomerID'. Key steps include:
- Removing rows with missing 'CustomerID' as it is essential for identifying unique customers.
- Dropping duplicate rows.
- Excluding cancelled orders from the analysis to focus on successful transactions.

After cleaning, the dataset has 392,732 rows and 8 columns.

## RFM Analysis and Clustering

Using the Elbow Method and Silhouette Scores, the optimal number of clusters was determined to be 3. The clusters are visualized using scatter plots focusing on Recency and Frequency dimensions.

## Customer Segmentation

### Cluster Profiles:
- **Cluster 0**: Customers who have not shopped recently, are infrequent buyers, and spend less.
- **Cluster 1**: Highly engaged, high-spending customers who have made purchases very recently.
- **Cluster 2**: Regular and moderately recent customers with moderate spending.

Boxplots display the distribution of Recency, Frequency, and Monetary values within each cluster.

## Market Recommendations

### Cluster 0
- **Characteristics**: Infrequent buyers who spend less.
- **Strategies**: Reactivation campaigns, personalized offers, market research.

### Cluster 1
- **Characteristics**: Highly engaged and high-spending customers.
- **Strategies**: Exclusive memberships, upselling opportunities, early access to new products.

### Cluster 2
- **Characteristics**: Regular customers with moderate spending.
- **Strategies**: Loyalty programs, targeted promotions, engagement campaigns.

## Conclusions and Recommendations

Focus on re-engaging 'At Risk' customers through personalized marketing strategies. Nurture 'Best Customers' and 'Big Spenders' with loyalty programs. Expand the 'Loyal Customers' base by enhancing customer loyalty initiatives.

## Contributors

- Vikramadithya Pabba
- Dheeraj Kumar Goli
- Laawanyaa Sai Thota
- Rohan Reddy Pathi
- Udhay Chityala
