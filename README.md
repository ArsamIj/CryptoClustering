# CryptoClustering
Assignment #19

In this challenge, I used my knowledge of Python and unsupervised learning to predict if cryptocurrencies are affected by 24-hour or 7-day price changes.

I used the StandardScaler() module from scikit-learn to normalize the data in order to prepare it to be transformed. In order to utilize the K-Means function accordingly, i first performed the elbow-curve methods to identify the optimal k-value to set my original data against. With a result of k=3, i was able to generate my scatter plots for "price_change_percentage_24h" vs. "price_change_percentage_7d".

I then used the PCA method to reduce the number of features the data was applying to differentiate he coins. The PCA method allowed me to reduce the number of features to 3, labelled PC1, PC2, and PC3. I then performed the elbow-curve methods to identify the optimal k-value for the new data i extracted using the PCA method. The new k-value acquired increased to 4.

Using the new k value, i re-plotted the PCA data into a scatter plot and segregated the clusters using the higher k-value acquired from the elbow-curve method. 

The higher k-value acquired from for the PCA based data allows us to see that for this particular set of data, we needed the higher k-value to appropriately segregate the clusters to be able to classify them.
