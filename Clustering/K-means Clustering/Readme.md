## K-Means Clustering:
K-means clustering is one of the simplest and popular unsupervised machine learning algorithms.

Typically, unsupervised algorithms make inferences from datasets using only input vectors without referring to known, or labelled, outcomes.

The objective of K-means is simple: group similar data points together and discover underlying patterns. To achieve this objective, K-means looks for a fixed number (k) of clusters in a dataset.

A cluster refers to a collection of data points aggregated together because of certain similarities.

You’ll define a target number k, which refers to the number of centroids you need in the dataset. A centroid is the imaginary or real location representing the center of the cluster.

Every data point is allocated to each of the clusters through reducing the in-cluster sum of squares.

In other words, the K-means algorithm identifies k number of centroids, and then allocates every data point to the nearest cluster, while keeping the centroids as small as possible.

The ‘means’ in the K-means refers to averaging of the data; that is, finding the centroid.

## How the K-means algorithm works:

To process the learning data, the K-means algorithm in data mining starts with a first group of randomly selected centroids, which are used as the beginning points for every cluster, and then performs iterative (repetitive) calculations to optimize the positions of the centroids.

It halts creating and optimizing clusters when either

-The centroids have stabilized there is no change in their values because the clustering has been successful.

-The defined number of iterations has been achieved.

## Steps in K-Means Notebook:
(1)Importing the library.

(2)Importing the Data.

(3)Exploring the Data.

(4)Using Elbow method to find optimal number of cluster.

![elbow method](https://user-images.githubusercontent.com/55452866/88565223-ec15c700-d051-11ea-8ffd-58cf1fe6afb1.png)

(5)Training the Kmeans model.

(6)Visualising the Clusters.

![cluster](https://user-images.githubusercontent.com/55452866/88565380-23847380-d052-11ea-9c0f-9a834b592340.png)
