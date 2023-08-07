# CryptoClustering

Steps: 

   1. Prepare the Data
        - Create a DataFrame with the scaled data and set the "coin_id" index from the original DataFrame as the index.

   2. Find the Best Value for k Using the Original Scaled DataFrame.
        - Use the elbow method to find the best value for k. 

   3. Cluster Cryptocurrencies with K-means Using the Original Scaled Data.

   4. Optimize Clusters with Principal Component Analysis.
        - Using the original scaled DataFrame, perform a PCA and reduce the features to three principal components.

   5. Find the Best Value for k Using the PCA Data.
        - Use the elbow method on the PCA data to find the best value for k.
        
   6. Cluster Cryptocurrencies with K-means Using the PCA Data.
        -  Cluster the cryptocurrencies for the best value for k on the PCA data.
    