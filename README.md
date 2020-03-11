# whelan_Cryptocurrencies

This repository contains my script for my module 18 challenge submission.

## Data Pre-Processing

In the data pre-processing step, I formatted the included cryptocurrency data set to prepare it for our unsupervised machine learning analysis. To do so, I removed all entries with null values, that aren't trading, that don't have defined algorithms, and that don't have coins mined. I then stored the data in a new DataFrame, set the indec, created dummy variables, and scaled the data, satisfying all the requirements of the assignment.

## Reducing Data Dimensions Using PCA

In this section, I reduced the data set into a new one with three Principle Characteristics variables.

## Clustering Cryptocurrencies Using K-means

In this section, I:

- Created an elbow curve of the data set to determine the optimal number of clusters at 4
- Predicted the k clusters of the set using four clusters
- Added the cluster and PC variable to our original data set

## Visualization

In this section, I:

- Created a 3D scatter plot to visualize the clusters
- Created a data table of the cryptocurrencies
- created a 2D scatter plot of the TotalCoinsMined on the TotalCoinSupply
