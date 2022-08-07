# Cryptocurrencies
Use Unsupervised learning techniques to analyze Cryptocurrency data.

# Tools :

- Software: Python , Anaconda Navigator , Conda , Jupyter Notebook 
- [crypto_data.csv](http://localhost:8888/edit/Resources/crypto_data.csv),  [cryptocompare](https://min-api.cryptocompare.com/data/all/coinlist)

# Overview :
The purpose of this Analysis is to create a report that includes what cryptocurrencies are on the trading market and how they could be grouped to create a classification system for this new investment.
 - Preprocessing the Data for PCA
 - Reducing Data Dimensions Using PCA
 -  Clustering Cryptocurrencies Using K-means
 - Visualizing Cryptocurrencies Results

# Result:
First it will need to be processed to fit the machine learning models. Since there is no known output for what we looking for, we decided to use unsupervised learning. To group the cryptocurrencies, on a clustering algorithm. we used data visualizations to share our findings with the board.
- Following the preprocessing and cleaning phase we have a total of 532 tradable cryptocurrencies.

# Clustering Cryptocurrencies using K-Means - Elbow Curve
We don't know what would be the output of the analysis so we are using unsupervised machine learning to identify clusters of the cryptocurrencies.
We produced the elbow curve below using the K-Means method iterating on k values from 1 to 10.

![kmeans](https://user-images.githubusercontent.com/77947860/165988774-88786b5f-920e-494f-bed7-f1e82f46778c.png)

The best k value appears to be 4 so we would conclude on an output of 4 clusters to categorize the crytocurrencies.

# Visualizing Cryptocurrencies Results
3D-Scatter plot with clusters

![PCViz](https://user-images.githubusercontent.com/77947860/165989192-b4b6b646-91a8-490d-a450-dc44fce74df9.png)

This 3-D scatter plot was obtained using the PCA algorithm to reduce the crytocurrencies dimensions to three principal components.

# 2D-Scatter plot with TotalCoinMined vs TotalCoinSupply

![2D](https://user-images.githubusercontent.com/77947860/165989565-8d743906-49c8-4a71-9f24-7ea112956761.png)

Plotting the scatter plot from two cryptocurrency features directly does not efficiently segregate the different classes. Then using the PCA algorithm is the right method for better visualizations.


# Summary :
We have identified the classification of 532 cryptocurrencies based on similarities of their features.
Particularities of each group need to be analyzed to determined their performance and potential interest for the investment bank's clients.

