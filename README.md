# Cryptocurrencies
## Overview
This project is applying unsupervised machine learning to analyze the cryptocurrencies and clustering the currencies into groups.

## Resources
- crypto_data.csv from https://min-api.cryptocompare.com/data/all/coinlist

## Results

### K-Means - Elbow Curve
Since the clusters of unsupervised are unknown, K-Mean is to iterate k values from 1 to 10, and indentify the best fit numbers of clusters to the data set. As a result, Elbow Curve has a significant change where k = 4.

### Visualizing Cryptocurrencies Results
3D Scatter clearly demonstrates the data into 4 class

<img src = "images/Cryptocurrencies_3DScatter">

### Table contains class details of Cryptocurrencies
<img src = "images/Cryptocurrencies_table">

### HVPLOT Scatter with HVPLOT Table beside
<img src = "images/hvplot">



