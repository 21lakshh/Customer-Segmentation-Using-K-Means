# Customer Segmentation using K-Means Clustering Algorithm

## Overview
This project performs customer segmentation using the **K-Means clustering algorithm**. The dataset used for this project is available on Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). The goal is to segment customers into different groups based on their purchasing behavior and other attributes.

## Dataset
The dataset contains customer information such as **Annual Income, Spending Score, Age, and Gender**. Using these attributes, we apply clustering techniques to group customers with similar characteristics.

## Steps Involved
1. **Data Preprocessing**:
   - Load the dataset and inspect the data.
   - Handle missing values if any.
   - Select relevant features for clustering.
2. **Choosing the Number of Clusters (k) using WCSS**:
   - **WCSS (Within-Cluster Sum of Squares)** is used to evaluate the optimal number of clusters.
   - The **Elbow Method** helps determine the best value of k by plotting WCSS for different cluster values.
3. **Applying K-Means Algorithm**:
   - Choose the optimal k (in this case, k=5).
   - Apply K-Means clustering.
   - Assign each data point to a cluster.
4. **Visualization of Clusters**:
   - Visualize customer segments using scatter plots.
   - Interpret different customer groups.

## Results & Insights
- The **Elbow Method** helps determine the optimal number of clusters (k=5 in this case).
- After applying K-Means, customers are grouped into **five distinct segments** based on **Annual Income** and **Spending Score**.
- This segmentation helps businesses understand customer behavior and design better marketing strategies.

## Technologies Used
- Python
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

## Conclusion
This project provides a simple yet effective implementation of **K-Means clustering** for customer segmentation. By analyzing customer data, businesses can gain valuable insights into different customer groups and optimize their marketing strategies accordingly.
