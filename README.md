# Mall Customers Clustering

This project performs customer segmentation using the K-Means clustering algorithm on the **Mall_Customers.csv** dataset. It includes data preprocessing, PCA-based visualization, optimal cluster selection using the Elbow Method, and cluster evaluation using the Silhouette Score.

## Dataset
The dataset includes customer data with the following features:
- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

## Steps Performed

1. **Load Dataset**: Read the CSV file using pandas.
2. **Feature Selection**: Selected `Age`, `Annual Income`, and `Spending Score` for clustering.
3. **Standardization**: Standardized features using `StandardScaler`.
4. **PCA Visualization**: Reduced dimensions to 2D using PCA for visualization.
5. **Elbow Method**: Determined optimal number of clusters (K) by plotting WCSS.
6. **K-Means Clustering**: Applied K-Means with optimal K (default K=5).
7. **Cluster Visualization**: Visualized clusters using a color-coded scatter plot.
8. **Evaluation**: Computed Silhouette Score to evaluate clustering quality.

## Dependencies

- pandas
- matplotlib
- scikit-learn
