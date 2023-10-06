# Clustering Analysis on USArrests Data

This project performs a clustering analysis on the USArrests dataset, which contains crime-related statistics for all 50 US states in 1973. The analysis involves hierarchical clustering, scaling of variables, Principal Component Analysis (PCA), and K-means clustering.

## Project Overview

### Technologies Used

- Python
- Libraries: pandas, numpy, matplotlib, seaborn, scipy, scikit-learn
- Jupyter Notebook

### Dataset

The USArrests dataset consists of 50 observations on 4 variables:
- Murder: Murder arrests (per 100,000)
- Assault: Assault arrests (per 100,000)
- Rape: Rape arrests (per 100,000)
- UrbanPop: Percent of the population living in urban areas

### Tasks

1. **Hierarchical Clustering with Raw Data**
   - Perform hierarchical clustering using complete linkage and Euclidean distance.
   - Cut the dendrogram to form three distinct clusters.
   - Identify states in each cluster and describe their characteristics.

2. **Hierarchical Clustering after Scaling**
   - Repeat hierarchical clustering after scaling variables to zero mean and unit standard deviation.
   
3. **PCA and Hierarchical Clustering**
   - Conduct Principal Component Analysis (PCA) on the data.
   - Perform hierarchical clustering on the first two principal component score vectors.
   - Cut the dendrogram to form three clusters and present a scatterplot of PC1 vs. PC2.
   - Compare group characteristics with those from Task 2.

4. **K-means Clustering with PCA**
   - Repeat analysis using K-means clustering (K=3) with PC1 and PC2 as features.
   - Set initial centroids as group means from hierarchical clustering in Task 3.
   - Compare results with hierarchical clustering in Task 3.

## Files and Structure

- `USArrests.csv`: Dataset file.
- `USArrest_cluster_analysis.ipynb`: Python script containing functions for data loading, visualization, and clustering.
- `README.md`: Project documentation.



