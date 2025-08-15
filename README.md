## AI-ML-Task-8

## Clustering with K-Means

## Overview

This project involves applying K-Means clustering to the Mall Customers dataset to group customers based on demographic and spending patterns. The objective is to identify customer segments, determine the optimal number of clusters using the Elbow Method and evaluate clustering performance with the Silhouette Score

## Dataset

The dataset used in this project is the Mall Customers dataset, which contains customer demographic and spending data.

## Tools and Libraries

Python

Pandas

Matplotlib

Scikit-learn

## Steps

1. Import the Dataset

Load the dataset using Pandas and view basic information (null values, data types). Display the first few records to understand the structure.

2. Feature Selection and Scaling

Select numerical features: Age, Annual Income (k$), Spending Score (1-100). Standardize features using StandardScaler to ensure equal weight in clustering.

3. Dimensionality Reduction (PCA)

Apply PCA to reduce features to 2 components for visualization. Plot customers in 2D space to visualize patterns.

4. Apply K-Means Clustering

Initialize K-Means with k=3 (initial test). Fit the model and assign a cluster label to each customer.

5. Find Optimal Number of Clusters (Elbow Method)

Calculate inertia for k values from 1 to 10. Plot inertia vs. number of clusters to identify the “elbow” point. Choose k = 4 as optimal.

6. Visualize Clusters

Fit K-Means with the optimal k value. Use PCA components to plot clusters in different colors.

7. Evaluate Clustering

Calculate Silhouette Score to assess clustering quality. Achieved Silhouette Score: 0.404 (moderate separation between clusters).

## Output

Visualization shows distinct clusters of customers based on age, income, and spending score.
