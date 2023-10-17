# CryptoClustering

This challenge is about predicting if cryptocurrencies are affected by 24-hour or 7-day price changes by using unsupervised learning with Python. 

Following tasks were completed:

1) Loaded the crypto_market_data.csv into a dataframe, observed the summary statistics and plotted the data to see what the data looks like.


2) Prepared the data by normalizing it using StandardScaler() module from scikit-learn. Created a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index for the new DataFrame.

3) Used the elbow method to find the best value for k which came out to be 4.
   
4) Clustered the cryptocurrencies for the best value for k on the original scaled data and created a scatter plot using hvPlot.
   
5) Using the original scaled DataFrame, performed a PCA and reduced the features to three principal components.
   
6) Retrieved the explained variance to determine how much information can be attributed to each principal component.
What is the total explained variance of the three principal components?

7) Used the elbow method to find the Best Value for k Using the PCA Data.

8) Clustered Cryptocurrencies with K-means Using the PCA Data and created a scatter plot using hvPlot
What is the impact of using fewer features to cluster the data using K-Means?
