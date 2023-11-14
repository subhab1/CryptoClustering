# CryptoClustering
## Background
The Crypto Clustering project aims to predict if cryptocurrencies are affected by 24-hour or 7-day price changes using unsupervised learning techniques, specifically K-means clustering. Additionally, the project explores the impact of dimensionality reduction using Principal Component Analysis (PCA) on clustering.
## Procedure

* Data Loading and Preprocessing: Begin by loading the cryptocurrency data and performing necessary preprocessing steps. Handle missing values, encode categorical variables, and prepare the data for scaling.
* Data Scaling:Use the StandardScaler to scale the data, ensuring that all features are on a similar scale. This step is crucial for K-means clustering.
* Determining Optimal k with Elbow Method:Apply the elbow method to identify the optimal number of clusters (k) using the original scaled data. Plot the sum of squared distances against different k values and observe the "elbow" point.
* K-means Clustering (Original Scaled Data):Perform K-means clustering on the original scaled data using the determined optimal k value. Assign each cryptocurrency to a cluster.
* Principal Component Analysis (PCA):Implement PCA to reduce the dimensionality of the data to three principal components. This step is crucial for visualizing the data in a 3D space.
* Optimal k with Elbow Method (PCA Data):Apply the elbow method again, this time using the PCA-transformed data. Determine the optimal k for clustering in the reduced feature space.
* K-means Clustering (PCA Data):Conduct K-means clustering on the PCA-transformed data using the optimal k value. Assign cryptocurrencies to clusters in the reduced-dimensional space.
* Visualization with hvPlot:Utilize hvPlot to create visualizations that compare the clustering results between the original scaled data and the PCA-transformed data. Visualize the clusters in both 2D and 3D to observe how well the clusters are separated.
* Analysis and Comparison:Analyze the clustering results from both approaches. Compare the consistency of clusters and observe if reducing the dimensionality through PCA has affected the quality of the clustering.
* Conclusion:Summarize the findings, highlighting the effectiveness of K-means clustering on both the original scaled data and the PCA-transformed data. Discuss any insights gained from the analysis and the implications for understanding cryptocurrency trends.
