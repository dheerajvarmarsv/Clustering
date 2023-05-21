# Clustering
 This code is an implementation of K-means and DBSCAN clustering algorithms for customer segmentation using credit card data. 
 
 The code performs the following steps:

Data Extraction and Cleaning:

Reads the credit card data from the "CCGENERAL.csv" file.
Checks for null values in the dataset and imputes them with the median.
Drops the unnecessary column "CUST_ID" from the dataset.
Normalizes the data.
Data Visualization:

Conducts univariate analysis to understand the distribution of each column.
Conducts bivariate analysis using box plots to identify outliers.
Model Building:

Applies K-means clustering algorithm to the dataset.
Determines the optimal number of clusters using the elbow method and silhouette scores.
Visualizes the clusters using scatter plots.
Applies DBSCAN clustering algorithm to the dataset.
Visualizes the clusters using scatter plots.
The code provides insights into customer segments based on credit card behavior and helps identify patterns and trends. It demonstrates the use of clustering algorithms for customer segmentation and the visualization of clusters.

Please note that the code is written in Python and requires the installation of necessary packages such as NumPy, pandas, scikit-learn, and seaborn. The code can be run in a Jupyter Notebook environment or in Google Colab.
