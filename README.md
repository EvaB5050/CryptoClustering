# CryptoClustering
Data Bootcamp Module 19 Challenge

## Background
Utilising Python and Unsupervised Learning techniques, particularly K-means clustering, the aim is to predict whether cryptocurrencies exhibit susceptibility to fluctuations caused by either 24-hour or 7-day price changes. This challenge explores the realm of dimensionality reduction through Principal Component Analysis (PCA) and its influence on the clustering analysis.

## Instructions

* Prepare the Data using `StandardScaler()` from `scikit-learn` to normalise the data from the CSV file. Create a DataFrame with the scaled data.

#### Scaled Data

* Find the best value for `k` using the scaled DataFrame. 
* Plot a line chart with all the inertia values computed to visually identify the optimal value for `k`.
* Cluster the cryptocurrencies with `K-means` using the best value for `k`. 
* Create a scatter plot using `hvPlot` to visually show the clusters.

#### Principal Component Analysis (PCA)

* Optimise the Clusters by performing a PCA analysis using the original scaled DataFrame and reduce the features to three principal components. 
* Create a new DataFrame with the PCA data.
* Find the best value for `k` using the PCA data. 
* Plot a line chart with all the inertia values computed to visually identify the optimal value for `k`.
* Cluster the cryptocurrencies with `K-means` using the PCA data.
* Create a scatter plot using `hvPlot` to visually show the clusters.

### Results and comparisons are included in the Markdown sections in the `Crypto_Clustering.ipynb` file.

