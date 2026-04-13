# 📊 Customer Segmentation & Prediction

## 🚀 Project Overview

This project performs customer segmentation using unsupervised machine learning techniques and builds predictive models for each segment. The goal is to identify meaningful customer groups and provide actionable business insights to improve retention, engagement, and revenue.

---

## 🎯 Objectives

- Segment customers using clustering algorithms
- Identify behavioral patterns across segments
- Build prediction models for each segment
- Provide business recommendations based on insights

---

## 🛠️ Tech Stack

- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- SciPy

---


📂 Project Structure

<img width="708" height="427" alt="image" src="https://github.com/user-attachments/assets/137ff0f8-32fa-487a-abe3-12cc46ea70d4" />



📊 Methodology

🔹 1. Data Preprocessing

Removed missing values
Converted categorical variables using encoding
Standardized features using StandardScaler

🔹 2. Clustering Techniques

📌 K-Means Clustering
Used to segment customers into distinct groups
Optimal clusters determined using Elbow Method
📌 Hierarchical Clustering
Used dendrogram to visualize cluster relationships
📌 DBSCAN
Identifies noise and outliers
Does not require predefined cluster count

--

📈 Visualizations

🔹 Elbow Method (Optimal Clusters)

<img width="726" height="571" alt="image" src="https://github.com/user-attachments/assets/8dfee571-67c8-4b38-a51b-1fbd2483080b" />


The Elbow Method helps determine the optimal number of clusters by analyzing WCSS.

🔹 PCA Cluster Visualization

<img width="711" height="570" alt="image" src="https://github.com/user-attachments/assets/dbf7eabd-d7e2-4a65-b554-83a5273be334" />


Dimensionality reduction using PCA to visualize clusters in 2D space.

🔹 Hierarchical Clustering (Dendrogram)

<img width="836" height="556" alt="image" src="https://github.com/user-attachments/assets/b8d693f6-ee00-4f54-9896-f617d7e2fa4c" />


Shows how clusters are formed step by step.

🔹 DBSCAN Clustering

Highlights dense regions and identifies noise points.

--


📊 Results

🔹 Customer Segments

<img width="842" height="260" alt="image" src="https://github.com/user-attachments/assets/3f3d6979-3730-4783-9134-d4da3394743e" />

🔹 Model Performance

<img width="875" height="227" alt="image" src="https://github.com/user-attachments/assets/25959e85-9952-4307-8c0b-e835d63717ac" />

🧠 Technical Details

🔹 Algorithms Used

K-Means Clustering
Hierarchical Clustering
DBSCAN
Random Forest (for prediction)

🔹 Feature Engineering

One-hot encoding for categorical variables
Scaling using StandardScaler

🔹 Evaluation Metrics

Accuracy
Precision
Recall
F1 Score

--


💼 Business Recommendations

🔹 Budget Customers
Offer discounts and retention campaigns
Provide affordable pricing plans

🔹 Premium Customers

Loyalty programs and VIP benefits
Upselling premium services

🔹 Moderate Customers

Targeted marketing campaigns
Upgrade incentives

--


📊 Business Impact

📈 Improved customer retention

💰 Increased revenue through upselling

🎯 Better marketing targeting

📊 Data-driven decision making

--


🧪 Testing & Validation

Test Case	Result

Data preprocessing	✅ Passed

Encoding	✅ Passed

Clustering	✅ Passed

Model training	✅ Passed

Evaluation metrics	✅ Passed

--


🔮 Future Improvements

Implement advanced clustering (GMM)

Deploy model using Streamlit/Flask

Real-time segmentation system
