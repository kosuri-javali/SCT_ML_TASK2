Task 2: Customer Segmentation Using K-Means Clustering
This task involves performing customer segmentation using K-Means Clustering in Python. The goal is to divide customers into groups based on their Annual Income and Spending Score, enabling businesses to better understand customer behavior.

Steps Involved:
Importing Libraries:

Required libraries such as pandas, matplotlib.pyplot, and KMeans from sklearn.cluster are imported.

Loading the Dataset:

A dataset from a URL is loaded into a pandas DataFrame.

The first few rows are displayed using .head().

Basic Data Exploration:

Dataset information, null checks, and statistical summaries are generated using .info() and .describe().

Feature Selection:

The features ‘Annual Income (k$)’ and ‘Spending Score (1-100)’ are selected for clustering.

Elbow Method:

The Elbow Method is applied to determine the optimal number of clusters.

A line plot of Within-Cluster-Sum-of-Squares (WCSS) vs. number of clusters shows the "elbow" point.

K-Means Clustering:

KMeans is applied with the optimal number of clusters (5 in this case).

Data points are labeled according to their clusters.

Visualization:

A scatter plot visualizes customer segments in 2D space using different colors for each cluster.

Cluster centroids are highlighted.

Output:
The final output shows distinct customer segments, helping identify patterns in customer income and spending behavior.

