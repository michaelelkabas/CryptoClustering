# Crypto Clustering Challenge

This project is a challenge to use unsupervised learning techniques to cluster cryptocurrencies based on their 24-hour and 7-day price changes. The goal is to identify patterns and group similar cryptocurrencies together.

## Project Overview

- **Data Preparation**: Load and preprocess the cryptocurrency market data.
- **Principal Component Analysis (PCA)**: Reduce the dimensionality of the data while retaining most of the variance.
- **K-Means Clustering**: Apply the K-Means algorithm to cluster the cryptocurrencies.
- **Visualization**: Visualize the clustering results and analyze the patterns.

## Files

- `crypto_market_data.csv`: The dataset containing cryptocurrency market data.
- `Crypto_Clustering.ipynb`: The Jupyter notebook with the starter code for the challenge.

## Steps

1. **Load and Preprocess Data**: Standardize the data to have a mean of 0 and a standard deviation of 1.
2. **PCA**: Use PCA to reduce the number of features while retaining 89.5% of the variance.
3. **K-Means Clustering**: Apply the K-Means algorithm to cluster the data into groups.
4. **Visualization**: Create scatter plots to visualize the clustering results and interpret the patterns.

## Dependencies

- Python 3.x
- pandas
- numpy
- scikit-learn
- hvplot
- matplotlib


