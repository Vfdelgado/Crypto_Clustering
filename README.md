# Crypto Clustering

This project delves into the captivating realm of cryptocurrencies, leveraging unsupervised learning techniques to uncover insights into their behavior. By clustering cryptocurrencies based on their price change characteristics, we aim to understand how they respond to market dynamics.

______

## Objective:
This project aims to conduct comprehensive clustering analysis on cryptocurrency market data using Python. The primary objectives include identifying optimal cluster numbers using the elbow method, performing clustering with K-means algorithm, optimizing clusters with Principal Component Analysis (PCA), and comparing the results visually.

_______

## Implementation:

_______

### Find the Best Value for k by Using the Original Data:

- Implemented the elbow method algorithm to determine the best value for k.

- Visualized inertia values across different k values to identify the optimal number of clusters.

- Cluster the Cryptocurrencies with K-Means by Using the Original Data:

- Initialized K-means model with the determined best value for k.

- Fitted the model using the original data and predicted clusters.

- Visualized the clustering results using scatter plots with hvPlot.

________
### Optimize the Clusters with Principal Component Analysis:

- Created a PCA model with n_components=3 to reduce feature dimensions.

- Determined the total explained variance of the principal components.

- Visualized the reduced feature space and created a new DataFrame with PCA data.

_________
### Find the Best Value for k by Using the PCA Data:

- Applied the elbow method algorithm on PCA data to find the optimal value for k.

- Visualized inertia values to determine the best k value for clustering.

- Cluster the Cryptocurrencies with K-means by Using the PCA Data:

- Initialized K-means model with the optimal k value from PCA data.

- Fitted the model using PCA data and predicted clusters.

- Visualized the clustering results using scatter plots with hvPlot.

___________
### Visualize and Compare the Results:

- Created composite plots to compare elbow curves and cryptocurrency clusters between original data and PCA data.

- Analyzed the impact of using fewer features for clustering using K-means.

____________
## Results:

The clustering analysis provided valuable insights into the behavior of cryptocurrencies, aiding in identifying optimal cluster numbers and visualizing clustering patterns across different dimensions. These insights can assist in making informed decisions in cryptocurrency investment strategies.

___________
## Conclusion

Through this project, we successfully conducted in-depth clustering analysis on cryptocurrency market data, demonstrating the effectiveness of unsupervised learning techniques in understanding cryptocurrency behavior and market trends.

____________
### Resources
Past class activities, online resources.

