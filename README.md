# Customer Segmentation Analysis

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Usage](#usage)
- [Analysis](#analysis)


## Introduction

This project focuses on customer segmentation analysis for a mall using clustering techniques. The goal is to segment customers into distinct groups based on their demographic and purchasing behavior, which can help in understanding customer patterns and tailoring marketing strategies.

## Features

- **Data Preprocessing**: Cleaning and preparing the dataset for analysis.
- **Clustering Analysis**: Applying K-means clustering to segment customers.
- **Visualization**: Visualizing the clusters using various plots for better understanding and insights.
- **Insights and Recommendations**: Providing actionable insights based on the analysis.

## Dataset

The dataset used for this project contains information about mall customers. It includes the following columns:

- `CustomerID`: Unique identifier for each customer.
- `Genre`: Gender of the customer.
- `Age`: Age of the customer.
- `Annual Income (k$)`: Annual income of the customer in thousands of dollars.
- `Spending Score (1-100)`: Spending score assigned to the customer based on their purchasing behavior.


## Usage

1. **Place the dataset**:
    - Ensure that the dataset file (`Mall_Customers.csv`) is placed in the `data/` directory.

2. **Run the analysis script**:
    - Execute the script to perform customer segmentation analysis:
    ```bash
    python customer_segmentation.py
    ```

3. **View the results**:
    - The script will output visualizations and save the segmented data into the `results/` directory.

## Analysis

- **Data Preprocessing**:
    - Handling missing values, if any.
    - Encoding categorical variables.
    - Scaling numerical features.

- **Clustering**:
    - Using K-means clustering to segment the customers.
    - Determining the optimal number of clusters using the Elbow Method.

- **Visualization**:
    - Visualizing the clusters using scatter plots.
    - Analyzing the characteristics of each cluster.


