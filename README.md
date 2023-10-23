This project involves clustering customers based on their age, annual income, and spending score using three different clustering algorithms: K-means, DBSCAN, and Hierarchical clustering.

The dataset used for analysis is named "Customers.csv" and it contains relevant information such as customer ID, gender, age, annual income, and spending score. The aim of this project is to identify distinct groups or clusters of customers based on their characteristics, which can provide valuable insights for targeted marketing strategies.

The focus of the clustering analysis is on the columns 'Age', 'Annual Income (k$)', and 'Spending Score (1-100)'. These columns serve as the basis for clustering the customers.

First, the K-means clustering algorithm is applied to the dataset. K-means aims to partition the data into K clusters, where each data point is assigned to the cluster with the nearest mean. For this project, K-means clustering is performed using the three specified columns.

Next, the Hierarchical clustering algorithm is employed. Hierarchical clustering builds a hierarchy of clusters by successively merging or splitting clusters based on their similarity. The result is a tree-like structure called a dendrogram. In this project, Hierarchical clustering is applied solely to the 'Age' and 'Spending Score (1-100)' columns.

Lastly, the DBSCAN clustering algorithm is utilized. DBSCAN is a density-based clustering algorithm that groups together data points based on their density. Points that are densely connected form clusters, while points with low density are considered noise or outliers. In this project, DBSCAN clustering is conducted on the three columns of interest.



To evaluate the performance of each clustering model, the silhouette score is calculated. The silhouette score measures the cohesion and separation of the clusters, indicating how well-defined and distinct they are from one another. A higher silhouette score indicates better clustering performance.

