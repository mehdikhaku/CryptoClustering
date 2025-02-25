# CryptoClustering
![1](images/1.JPG)

## Introduction
Use your knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes

## Sources of data
Within Resources Folder:
*  crypto_market_data.csv

## Findings
### Elbow Curve Comparison:
![elbow1](images/elbow1.JPG)
![elbow2](images/elbow2.JPG)

* The elbow curve for the PCA data (elbow curve 2) shows a lower inertia value compared to the elbow curve for the original data (elbow curve 1). This indicates that using fewer features resulted in a reduction in the sum of squared distances within the clusters. A lower inertia value suggests better clustering performance and tighter grouping of data points within each cluster.

### Cluster Scatter Plot Comparison:
![cluster1](images/cluster1.JPG)
![cluster2](images/cluster2.JPG)

* Cluster Graph 1 (using original data): The clusters are overlapping, and there is no clear separation or distinct clusters. This suggests that using the original data, with more features, may not have effectively captured the underlying patterns or structure of the data for clustering purposes.

* Cluster Graph 2 (using PCA data): The clusters in this graph are not overlapping, and there is a clear separation and well-defined clusters. You can identify 4 distinct clusters. This indicates that using fewer features (through PCA) has potentially reduced noise and helped reveal more distinct patterns in the data, leading to more meaningful and separable clusters.

## Conclusion

Based on these observations, it seems that using fewer features (PCA data) to cluster the cryptocurrency data using K-Means has had a positive impact. It has resulted in better-defined and separable clusters compared to using the original data. The reduction in the number of features through PCA has likely helped to highlight the essential patterns and reduce the impact of noise, leading to more accurate and meaningful clustering results.

## Instructions

For detailed instructions, refer to the [Instructions PDF](instructions.pdf).

