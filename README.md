# _Mall Customer Segmentation using K-Means Clustering_

## _Author: **Muhammad Taimoor Khan**_

### Project Overview

This project aims to segment mall customers based on their Annual Income and Spending Score using K-Means Clustering. By identifying distinct clusters, businesses can tailor marketing strategies and services to better meet the diverse needs of different customer groups.

---

### Project Structure

**1. Importing Dependencies**

- Numpy, pandas, matplotlib, seaborn, and scikit-learn libraries are imported for data manipulation, visualization, and machine learning.

**2. Data Collection and Analysis**

- The dataset, `Mall_Customers.csv` is loaded and analyzed.
- Basic information about the dataset, such as the number of rows and columns, is displayed.
- Focus on the `Annual Income` and `Spending Score` columns.

**3. Determining The Number of Clusters**

- Elbow Method is utilized to find the optimal number of clusters (K).
- `Within Clusters Sum of Squares (WCSS)` is calculated for different K values.
- The Elbow Point Graph is plotted to identify the point of diminishing returns, suggesting the optimal K value. In this case, `K = 5`.

**4. Training K-Means Clustering Model**

- K-Means Clustering model is instantiated with `K = 5`.
- The `fit_predict` method is used to assign cluster labels to each data point.

**5. Visualizing The Clusters**

- A custom function, plot_clusters, is defined to visualize the clusters and centroids.
- The `centroids` and `labels` are extracted from the trained model.
- Scatter plots are generated to display the clusters and centroids, providing insights into customer segmentation based on `Annual Income` and `Spending Score`.

---

## Conclusion

This project successfully utilizes K-Means Clustering to categorize mall customers into distinct segments. The visualization of clusters and centroids provides a clear understanding of customer distribution, enabling businesses to make informed decisions for targeted marketing and service strategies.

---

## How to Use

**1. Clone the repository:**

   ```bash
   git clone https://github.com/MTaimoorK/mall-customer-segmentation.git
  ```

## Future Enhancements
Explore avenues for further analysis, such as customer behavior within specific clusters, to derive actionable insights for personalized marketing strategies.

## Contribution
Feel free to contribute by forking the repository and submitting pull requests. Bug fixes, feature enhancements, and additional analyses are all welcome!
