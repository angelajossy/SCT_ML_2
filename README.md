🧠 Project Overview

This project focuses on Customer Segmentation using K-Means Clustering with the Mall Customer Dataset from Kaggle. The goal is to identify different customer groups based on their Age, Annual Income, and Spending Score, helping businesses understand their customers better and tailor marketing strategies effectively.

🔍 Objective

To apply unsupervised machine learning (K-Means Clustering) to discover natural groupings within customer data — revealing insights such as who the high spenders, budget buyers, and loyal shoppers are.

🧮 Steps Involved

Data Loading & Exploration
 .Imported the Kaggle Mall Customers dataset and explored features like Age, Gender, Annual Income, and Spending Score.

Data Preprocessing
 .Selected key numerical features for clustering.
 .Applied StandardScaler() from Scikit-learn to normalize the feature space for better distance-based clustering performance.

Finding Optimal Number of Clusters
 .Used the Elbow Method to identify the optimal number of clusters (k=5) by plotting inertia vs. cluster count.

Model Training
.Trained the KMeans model from Scikit-learn with n_clusters=5.
.Assigned cluster labels to each customer.

Visualization
.Created 2D (Annual Income vs Spending Score) and 3D (Age, Income, Spending) scatter plots using Matplotlib to visualize clear segmentation boundaries.

Insights & Interpretation
.Interpreted clusters to understand business implications:

💎 High-income, high-spending customers

💰 Moderate-income, low-spending customers

👩‍💼 Young, high-spending potential loyalists

🧓 Older, low-spending cautious buyers

These insights can support targeted marketing, personalized campaigns, and improved customer engagement.

🛠️ Tools & Libraries Used

Python

Pandas – Data handling and preprocessing

Matplotlib – Data visualization (2D/3D plots)

Scikit-learn – Machine learning (StandardScaler, KMeans)

📈 Key Takeaways

Applied unsupervised learning to uncover hidden customer patterns.

Strengthened understanding of clustering, feature scaling, and data visualization.

Demonstrated how data science can provide actionable insights for business decision-making.
