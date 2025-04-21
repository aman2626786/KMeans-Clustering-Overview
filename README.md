# KMeans-Clustering-Overview

K-Means Clustering is an unsupervised machine learning algorithm used for grouping data into distinct clusters based on their similarities. Here's a quick overview:

1. **How it Works**:
   - You specify the number of clusters, \( k \), beforehand.
   - The algorithm randomly initializes \( k \) centroids (center points of clusters).
   - Each data point is assigned to the nearest centroid, forming \( k \) clusters.
   - The centroids are recalculated as the mean of all points in their respective clusters.
   - Steps are repeated until the centroids stabilize or a stopping criterion is met.

2. **Applications**:
   - Customer segmentation in marketing.
   - Image compression by grouping similar colors.
   - Document clustering for organizing text data.

3. **Limitations**:
   - Sensitive to the initial placement of centroids.
   - Assumes clusters are spherical and equally sized, which may not always be true.


