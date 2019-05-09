# K-means-plus-plus
An implementation of the K-means++ clustering algorithm
(A variation of the normal K-means algorithm)

The K-means++ Algorithm carefully selects the initial centroids for K-means clustering. The algorithm follows a simple probability based approach where initially the first centroid is selected at random. The next centroid selected is the one that is farthest from the currently selected centroids. This selection is decided based on a weighted probability score. The selection is continued until we have K centroids and then K-means clustering is done using these centroids.
