# Customer Segmentation Analysis

## Project Overview

This project focuses on customer segmentation using unsupervised machine learning. The goal is to identify groups of customers with similar demographic and behavioral characteristics.

## Project Goals

1. Explore and understand the customer dataset.
2. Prepare the data for clustering.
3. Identify customer segments using clustering techniques.
4. Evaluate and compare the clustering results.
5. Profile the resulting customer segments based on their characteristics.

## Methodology

### Data Preparation

The dataset was explored and prepared before applying the clustering models. The selected features were standardized to ensure that differences in feature scales did not affect the clustering results.

### Exploratory Data Analysis

The data was explored using descriptive statistics and visualizations to better understand the customer characteristics and distributions.

### Clustering Analysis

Different clustering approaches were explored for customer segmentation.

#### K-Means

K-Means clustering was applied to group customers based on similarities in their selected features. The Elbow Method and Silhouette Score were used to evaluate different numbers of clusters. Based on the results, 7 clusters were selected for the final K-Means model.

#### DBSCAN

DBSCAN was also tested as an alternative density based clustering method. Different parameter values were explored and the resulting clusters were evaluated using the Silhouette Score.

#### HDBSCAN

HDBSCAN was explored as another density based clustering approach. The resulting clusters and noise points were evaluated to determine its suitability for the dataset.

### Customer Profiling

The final K-Means clusters were profiled to understand the characteristics of each customer segment. The profiles were compared based on the selected demographic and behavioral features.

## Results

K-Means with 7 clusters was selected as the final clustering approach. The resulting customer segments were further analyzed through customer profiling to understand the differences between the groups.

## Tools

- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Google Colab
