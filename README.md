## Overview
This repository contains a Jupyter notebook that demonstrates the application of Principal Component Analysis (PCA) to a dataset comprising different constituents of wine. The analysis explores dimensionality reduction to improve the understanding and visualization of the data.

## Dataset Description
- The dataset comprises the results of a chemical analysis of wines grown in the same region in Italy but derived from three different cultivars. The analysis determined the quantities of 13 constituents found in each of the three types of wines.

Attributes:
- Alcohol: Alcohol content
- Malic Acid: Malic acid content
- Ash: Ash content
- Alcalinity of Ash: Alcalinity of ash
- Magnesium: Magnesium content
- Total Phenols: Total phenols content
- Flavanoids: Flavanoids content
- Nonflavanoid Phenols: Nonflavanoid phenols content
- Proanthocyanins: Proanthocyanins content
- Color Intensity: Color intensity
- Hue: Hue
- OD280/OD315 of Diluted Wines: OD280/OD315 of diluted wines
- Proline: Proline content
  
## Files
- PCA_Wine_Data.ipynb: Jupyter notebook that performs PCA on the wine dataset.

## Analysis Overview
- The notebook carries out the following key steps:
- Data Loading: Load and inspect the dataset.
- Data Preprocessing: Normalize the data to ensure each feature contributes equally.
- PCA Application: Apply PCA to transform the data into principal components.
- Variance Analysis: Analyze the variance explained by each principal component to determine how many components should be retained.
- Data Visualization: Visualize the transformed data in the new feature space for better understanding and insights.
