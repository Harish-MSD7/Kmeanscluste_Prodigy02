# Task 2 - K-Means Clustering (Prodigy Infotech ML Internship)

## 📊 Problem Statement
Create a K-means clustering algorithm to group customers of a retail store based on their purchase history.

## 📂 Dataset
The dataset used: [Mall Customers Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python)  

Features:
- **CustomerID**
- **Gender**
- **Age**
- **Annual Income (k$)**
- **Spending Score (1–100)**

## ⚙️ Approach
1. Loaded dataset using Pandas.  
2. Selected **Annual Income** and **Spending Score** for clustering.  
3. Applied the **Elbow Method** to determine the optimal number of clusters (k=5).  
4. Trained **KMeans** clustering model with 5 clusters.  
5. Visualized results using scatter plots and bar charts.  

## 📈 Results & Insights

### 🔹 Cluster Interpretations
- **Cluster 0 (Red)** – Medium Income, Medium Spending → **Average Customers**  
- **Cluster 1 (Blue)** – High Income, Low Spending → **Careful Customers (Savers)**  
- **Cluster 2 (Green)** – Low Income, High Spending → **Impulsive Buyers**  
- **Cluster 3 (Cyan)** – High Income, High Spending → **Premium Customers (Best Target Group)**  
- **Cluster 4 (Magenta)** – Low Income, Low Spending → **Budget Customers**  

### 📊 Cluster Summary (Average Values)

| Cluster | Annual Income (k$) | Spending Score (1–100) | Customer Type                   |
|---------|---------------------|-------------------------|---------------------------------|
| 0       | Medium              | Medium                  | Average Customers               |
| 1       | High                | Low                     | Careful Customers (Savers)      |
| 2       | Low                 | High                    | Impulsive Buyers                |
| 3       | High                | High                    | Premium Customers (Best Target) |
| 4       | Low                 | Low                     | Budget Customers                |

### 📊 Visualizations
- **Elbow Method Plot** – shows that k=5 is optimal.  
- **Scatter Plot with Clusters & Centroids** – groups customers into 5 clusters.  
- **Bar Charts** – show the average Annual Income and Spending Score for each cluster.  

## 📌 Conclusion
The K-Means clustering algorithm successfully grouped customers into 5 distinct segments.  
- **Premium Customers (Cluster 3)** can be targeted with luxury products.  
- **Impulsive Buyers (Cluster 2)** respond well to offers and discounts.  
- **Careful Customers (Cluster 1)** need more convincing to spend.  
- **Budget Customers (Cluster 4)** are low-value customers for premium marketing.  
- **Average Customers (Cluster 0)** maintain balanced spending.  

This segmentation can help the retail store create **targeted marketing strategies** and **personalized offers**, improving overall sales and customer satisfaction.  

## 🚀 How to Run
1. Open `KMeans_Clustering.ipynb` in Google Colab.  
2. Run all cells to reproduce results.  
3. View visualizations in the `outputs/` folder.  


