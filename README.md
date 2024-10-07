# K-Means-Grouping-Mall-Customer
Using K-Means Clustering Algorithm to grouping Mall Customers.
- UnSuperVised Learning
- Aims to Group the observations in a given dataset into clusters

## K-Means Clustering
- K-Means follows an iterative process in which it tries to minimize the distance of the data points from the centroid points. It’s used to group the data points into k number of clusters based on their similarity.
- Euclidean distance is used to calculate the similarity.

## Steps Involved
There are 3 important steps in K-Means Clustering.

1. **Initialize centroids** – This is done by randomly choosing K no of points, the points can be present in the dataset or also random points.
2. **Assign Clusters** – The clusters are assigned to each point in the dataset by calculating their distance from the centroid and assigning it to the centroid with minimum distance.
3. **Re-calculate the centroids** – Updating the centroid by calculating the centroid of each cluster we have created.
## Elbow Method
- One of the important steps in K-Means Clustering is to determine the optimal no. of clusters we need to give as an input. This can be done by iterating it through a number of n values and then finding the optimal n value.
- For finding this optimal n, the Elbow Method is used.
- You have to plot the loss values vs the n value and find the point where the graph is flattening, this point is considered as the optimal n value.
