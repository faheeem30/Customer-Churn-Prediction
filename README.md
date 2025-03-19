Customer Segmentation using K-Means Clustering

Overview

This project applies K-Means Clustering to segment customers based on their annual income and spending score. The goal is to categorize customers into meaningful groups for business insights.

Dataset

The dataset contains the following key features:

Age

Annual Income (k$)

Spending Score (1-100)

Prerequisites

Ensure you have the following Python libraries installed:

pip install pandas numpy matplotlib seaborn scikit-learn

Steps

1. Exploratory Data Analysis (EDA)

We visualize distributions and relationships in the dataset using histograms, scatter plots, and correlation matrices.

2. Data Preprocessing

The dataset is normalized using StandardScaler to ensure fair distance measurement for clustering.

3. Finding the Optimal Number of Clusters (Elbow Method)

We use the Elbow Method to determine the optimal value for K.

4. Applying K-Means Clustering

Based on the Elbow Method, we select K=5 and apply K-Means.

5. Mapping Clusters to Segments

We define meaningful labels for each segment.

6. Visualizing Customer Segments

We plot clusters to visualize customer segments.

7. Exporting Results

The segmented data is saved to a CSV file for further analysis.

Download the file from Google Colab using:

Navigate to the Files section in Colab.

Locate customer_segments.csv.

Right-click and select Download.

8. Power BI Dashboard

A Power BI dashboard is created using the exported CSV file to provide interactive visual insights.

Import customer_segments.csv into Power BI.

Use scatter plots and bar charts to analyze customer segments.

Apply filters and slicers to explore different customer groups.

Results

Customers are successfully segmented into five categories, providing insights into purchasing behavior. This can help businesses with targeted marketing strategies and customer relationship management.
