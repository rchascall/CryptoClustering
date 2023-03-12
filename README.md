# Crypto Market Data Cluster Analysis
This challenge uses the K-Means clustering algorithm to group cryptocurrencies based on their price change percentage over different time intervals. Principal Component Analysis (PCA) was also used to optimize the clustering solution.

The dataset used in this analysis is taken from the crypto_market_data.csv file, which contains the following features:

1. coin_id: the name of the cryptocurrency
2. price_change_percentage_24h: the percentage change in the price of the cryptocurrency over the past 24 hours
3. price_change_percentage_7d: the percentage change in the price of the cryptocurrency over the past 7 days
4. price_change_percentage_14d: the percentage change in the price of the cryptocurrency over the past 14 days
5. price_change_percentage_30d: the percentage change in the price of the cryptocurrency over the past 30 days
6. price_change_percentage_60d: the percentage change in the price of the cryptocurrency over the past 60 days
7. price_change_percentage_200d: the percentage change in the price of the cryptocurrency over the past 200 days
8. price_change_percentage_1y: the percentage change in the price of the cryptocurrency over the past year

## Technologies Used
This project uses:
1. Pandas
2. hvplot
3. scikit-learn
