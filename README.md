# CryptoClustering

This challenge is about predicting if cryptocurrencies are affected by 24-hour or 7-day price changes by using unsupervised learning with Python. 

Following tasks were completed:

1) Loaded the crypto_market_data.csv into a dataframe, observed the summary statistics and plotted the data to see what the data looks like.

![Screenshot 2023-10-17 at 12 03 50 AM](https://github.com/ShipraGupta16/CryptoClustering/assets/25715747/c8725e2c-a605-493d-bb5c-66b64554fb96)

2) Prepared the data by normalizing it using StandardScaler() module from scikit-learn. Created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

3) Used the elbow method to find the best value for k which came out to be 4.

![Screenshot 2023-10-17 at 12 04 53 AM](https://github.com/ShipraGupta16/CryptoClustering/assets/25715747/609dbd68-2606-406e-b4b0-cf84ae842614)

4) Clustered the cryptocurrencies for the best value for k on the original scaled data and created a scatter plot using hvPlot.

![Screenshot 2023-10-17 at 12 05 21 AM](https://github.com/ShipraGupta16/CryptoClustering/assets/25715747/c36bd064-7247-419c-a3ae-1d565dc8ddcb)

5) Using the original scaled DataFrame, performed a PCA and reduced the features to three principal components.
   
6) Retrieved the explained variance to determine how much information can be attributed to each principal component.
What is the total explained variance of the three principal components?

7) Used the elbow method to find the Best Value for k Using the PCA Data.
![Screenshot 2023-10-17 at 12 06 04 AM](https://github.com/ShipraGupta16/CryptoClustering/assets/25715747/8b75666d-4ca4-44ac-917d-c1b2b6a354e5)

8) Clustered Cryptocurrencies with K-means Using the PCA Data and created a scatter plot using hvPlot
What is the impact of using fewer features to cluster the data using K-Means?
![Screenshot 2023-10-17 at 12 06 33 AM](https://github.com/ShipraGupta16/CryptoClustering/assets/25715747/07b61446-99c0-4952-9aa9-9df5ea610a6d)
![Screenshot 2023-10-17 at 12 07 02 AM](https://github.com/ShipraGupta16/CryptoClustering/assets/25715747/0d01f0a4-d4df-4a67-a71e-6967a6e8eb05)
