Problem Statement: K-Means Clustering on Synthetic Data
The goal of this project is to apply the K-Means clustering algorithm to a synthetic dataset generated using make_blobs from sklearn. The dataset consists of 200 data points with 3 distinct clusters. Using the K-Means algorithm, we aim to group the data points into 3 clusters, identify the cluster centers, and visualize the results.
Objective:
Generate a synthetic dataset with 3 centers using make_blobs.
Apply the K-Means clustering algorithm to the dataset to find 3 clusters.
Visualize the clustered data points with distinct colors and highlight the centers of the clusters.
Key Steps:
Data Generation: Create a synthetic dataset with 200 samples and 3 centers using the make_blobs function from sklearn.
K-Means Clustering: Apply the K-Means clustering algorithm from sklearn with the following parameters:
n_clusters=3 (targeting 3 clusters)
n_init=10 (number of times the algorithm will run with different initializations)
random_state=42 (ensuring reproducibility)
Visualization:
Plot the data points with colors representing the assigned clusters.
Plot the cluster centers using red 'x' markers.
Add appropriate titles and labels to the plot for clarity.
Expected Outcome:
The data points will be grouped into 3 clusters, with each cluster assigned a unique color.
The centers of the clusters will be marked with red 'x' markers, visually indicating the centroids of each cluster.
The plot will give insights into how well the K-Means algorithm has grouped the data points.
Technologies Used:
Python
scikit-learn (for K-Means clustering and data generation)
matplotlib (for data visualization)
Use Case:
This type of clustering is commonly used in data analysis to identify patterns in unlabeled data, helping to group similar items together in a wide range of applications such as customer segmentation, market research, and anomaly detection.
