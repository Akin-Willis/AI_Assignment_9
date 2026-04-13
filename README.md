# Assignment 9: Unsupervised Learning - Mall Customer Segmentation

## Project Description
This project applies unsupervised machine learning techniques to
analyze and segment mall customers based on their annual income
and spending behavior. The dataset used is the Mall Customer
Segmentation dataset from Kaggle. The goal is to identify natural
groupings of customers that can be used to inform business and
marketing strategies.

## Dataset
- Name: Mall Customer Segmentation
- Source: Kaggle
- File: Mall_Customers.csv
- Features used:
  - Age
  - Annual Income (k$)
  - Spending Score (1-100)
  - Gender (one-hot encoded)

## Requirements
The following libraries are required to run this notebook:
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Set Up and Run the Notebook

Step 1
Open Google Colab at https://colab.research.google.com

Step 2
Upload the notebook file to Colab or open it from GitHub.

Step 3
Upload the dataset file Mall_Customers.csv to Colab
using the Files panel on the left side.

Step 4
Run each cell from top to bottom in order.

Step 5
Make sure all outputs are visible before saving as PDF.

## Notebook Structure
1. Import necessary libraries
2. Load the Mall Customers dataset
3. Dataset Selection and Preprocessing
4. Visualise the original data
5. Elbow Method and Silhouette Score
6. KMeans Clustering
7. Agglomerative Hierarchical Clustering
8. Silhouette Scores for both models
9. Cluster Visualisation
10. Dimensionality Reduction using PCA
11. Model Evaluation Summary
