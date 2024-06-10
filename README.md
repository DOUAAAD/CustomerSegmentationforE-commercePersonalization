Customer Segmentation Project

Overview

This project aims to perform customer segmentation based on purchasing behavior within an e-commerce dataset. By utilizing K-means clustering and PCA (Principal Component Analysis), distinct groups of customers with similar preferences and behaviors are identified. The segmentation results enable personalized marketing strategies and recommendations to enhance customer engagement and satisfaction.

Dataset
The dataset used in this project is the Online Retail Dataset

Project Steps
Data Preparation:
Handle missing values, clean the data, and transform it into a suitable format.
Extract relevant features reflecting customer behavior.
Dimensionality Reduction with PCA:
Apply PCA to reduce the dimensionality of the feature space while retaining informative features.
K-means Clustering:
Perform K-means clustering to assign customers to clusters based on their feature values.
Cluster Profiling:
Profile each cluster to understand its characteristics and behaviors.
Evaluation:
Assess clustering quality using metrics such as silhouette score and within-cluster sum of squares (WCSS).
Personalization and Recommendations:

Devise personalized marketing strategies and recommendations for each customer segment.
Documentation and Reporting:
Document insights, interpretations, and findings in a clear and concise manner.
Requirements

Libraries: scikit-learn, pandas, numpy, matplotlib, seaborn

Results (Personalization and Recommendations ):
Cluster 0:

Recency: 40.31 days
Frequency: 64.36 purchases
Monetary: 0.008846 (normalized value)
Interpretation: Customers in this cluster have made purchases fairly recently (around 40 days ago on average) and have a moderate purchase frequency. The monetary value indicates these customers have a moderate total spend.
Action: These are moderately active customers. Engage them with regular promotions to maintain their activity level and potentially increase their spend.
Cluster 1:

Recency: 246.04 days
Frequency: 17.79 purchases
Monetary: 0.002582 (normalized value)
Interpretation: This cluster represents customers who haven't made purchases in a long time (almost 250 days) and have a relatively low frequency and spend.
Action: These are at-risk customers. Implement re-engagement campaigns such as win-back offers or personalized communication to reactivate their interest.
Cluster 2:

Recency: 0.67 days
Frequency: 2580.67 purchases
Monetary: 0.248754 (normalized value)
Interpretation: This cluster has the most recent purchases (almost daily) and the highest purchase frequency and spend.
Action: These are your most valuable customers. Focus on retaining them with loyalty programs, exclusive deals, and personalized experiences.
Cluster 3:

Recency: 45.00 days
Frequency: 446.89 purchases
Monetary: 0.725050 (normalized value)
Interpretation: These customers have a recent purchase history (about 45 days ago) with high frequency and high spend.
Action: These are also valuable customers, similar to Cluster 2 but slightly less frequent. Maintain their engagement with periodic rewards and high-value offers.
Leveraging the Insights
Targeted Marketing Campaigns:

Cluster 0: Offer regular promotions and discounts to keep them engaged and increase their spending.
Cluster 1: Send personalized re-engagement emails, special discounts for returning customers, and surveys to understand why they have lapsed.
Cluster 2: Focus on high-value, personalized loyalty programs, exclusive early access to new products, and premium customer service.
Cluster 3: Provide consistent high-value offers, loyalty rewards, and ensure excellent customer service to maintain their loyalty.
Product Recommendations:

Use the clustering data to recommend products that are popular within each segment. For example, high-frequency buyers might appreciate recommendations for complementary products.
Customer Support Prioritization:

Prioritize support for high-value clusters (Cluster 2 and Cluster 3) to ensure any issues they face are resolved quickly and efficiently.
Inventory Management:

Adjust inventory levels based on the purchasing patterns of different clusters. Ensure high-demand items are always in stock for frequent buyers (Clusters 2 and 3).
Customer Feedback:

Collect feedback specifically from Cluster 1 to understand their reasons for inactivity and use this information to improve products or services.
