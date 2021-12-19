# Cryptocurrencies

## Overview

The purpose of this project is to use unsupervised machine learning to analyze what cryptocurrencies are on the trading market, and create a report including the traded cryptocurrencies classified by group.

This classification report could be used by an company to propose a new cryptocurrency investment portfolio to its clients.

#### We use the following methods for the analysis:

- Preprocessing the data

- Reducing data dimensions using Principal Component Analysis

- Clustering cryptocurrencies using K-Means

- Visualizing classification results with 2D and 3D scatter plots

## Results

After cleaning and preprocessing data, we have a total of 532 tradable cryptocurrencies.

![Screen Shot 2021-12-18 at 9 04 19 PM](https://user-images.githubusercontent.com/88747464/146661034-837f03e9-fc70-49d3-b04f-5a3c0f2f894f.png)

Additionally, we used PCA to reduce dimension to three principal components.

![Screen Shot 2021-12-18 at 9 06 33 PM](https://user-images.githubusercontent.com/88747464/146661083-d14f7eee-f3e0-4e8d-9237-b7713d2a2333.png)

Then we created Elbow Curve to predict the best k-value, which appears to be k = 4.

![Screen Shot 2021-12-18 at 9 06 17 PM](https://user-images.githubusercontent.com/88747464/146661086-c38e1509-dd99-458d-b972-09f49d401a44.png)

### Visualizing Cryptocurrencies Results

#### 3D-Scatter plot with clusters

![newplot (1)](https://user-images.githubusercontent.com/88747464/146661217-f0afcc0c-2cee-4d26-9311-21e926db81dd.png)

- This scatter plot shows the distribution and the four clusters of cryptocurrencies.

- The outliers like the unique cryptocurrency is in class #2.

#### Tradable Cryptocurrencies Table

![Screen Shot 2021-12-18 at 9 14 48 PM](https://user-images.githubusercontent.com/88747464/146661256-9e49f1db-ae5f-4a61-bc2c-625fe99b1137.png)

- Most of the cryptocurrencies are part of class #0 and #1.

- The outlier: BitTorrent, is the only cryptocurrency in class #2.

#### 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply 

![Screen Shot 2021-12-18 at 9 15 29 PM](https://user-images.githubusercontent.com/88747464/146661222-5cfcf0a4-7376-4f9d-b9ac-0d0bd9085740.png)

- Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. 

## Summary

2D scatter plot does not as efficiently as the 3D. 

Using the PCA algorithm gives a better visualizations.

