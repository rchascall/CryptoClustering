# Crypto Market Data Cluster Analysis
This challenge uses the K-Means clustering algorithm to group cryptocurrencies based on their price change percentage over different time intervals. Principal Component Analysis (PCA) was also used to optimize the clustering solution.

The dataset used in this analysis is taken from the crypto_market_data.csv file, which contains the following features:

coin_id: the name of the cryptocurrency
price_change_percentage_24h: the percentage change in the price of the cryptocurrency over the past 24 hours
price_change_percentage_7d: the percentage change in the price of the cryptocurrency over the past 7 days
price_change_percentage_14d: the percentage change in the price of the cryptocurrency over the past 14 days
price_change_percentage_30d: the percentage change in the price of the cryptocurrency over the past 30 days
price_change_percentage_60d: the percentage change in the price of the cryptocurrency over the past 60 days
price_change_percentage_200d: the percentage change in the price of the cryptocurrency over the past 200 days
price_change_percentage_1y: the percentage change in the price of the cryptocurrency over the past year

## Technologies Used
This project uses:
pandas
hvplot
scikit-learn
