# Regression Project (Store Sales -- Time Series Forecasting)

# GOAL:
The goal of this project is to build a Model that predicts the sales for product families sold at Favorita stores located in Ecuador

# HYPOTHESIS

* Promotion impacts the number of sales and transactions positively
* Highest sales of the year occurs on December

# QUESTIONS

1. Is the train dataset complete (has all the required dates)?
2. Are sales influenced by specific dates in the year?
3. Which month has the highest sales record?
4. Top 10 Stores based on total sales, and total transactions
5. What is the Sales Trend for each Family?
6. What is the Sales Trend for each Store Number?
7. What is the trend in transactions for each store number?
8. Are certain groups of stores selling more products? (Cluster, city, state, type)
9. Did the earthquake that struck Ecuador on April 16, 2016 impact sales?
10. Are sales affected by promotions?

# File Descriptions and Data Field Information

* train.csv: The training data, comprising time series of features store_nbr, family, and onpromotion as well as the target sales.
* store_nbr: identifies the store at which the products are sold.
* family: identifies the type of product sold.
* sales: gives the total sales for a product family at a particular store at a given date. Fractional values are possible since products can be sold in fractional units (1.5 kg of cheese, for instance, as opposed to 1 bag of chips).
* onpromotion: gives the total number of items in a product family that were being promoted at a store at a given date.
* test.csv: The test data, having the same features as the training data. You will predict the target sales for the dates in this file.
* Date: The dates in the test data are for the 15 days after the last date in the training data.
* transaction.csv: Contains date, store_nbr and transaction made on that specific date.
* sample_submission.csv: A sample submission file in the correct format.
* stores.csv: Store metadata, including city, state, type, and cluster.
* cluster: is a grouping of similar stores.
* oil.csv: Daily oil price which includes values during both the train and test data timeframes. (Ecuador is an oil-dependent country and its economical health is highly vulnerable to shocks in oil prices).
* holidays_events.csv: Holidays and Events, with metadata.

# Technologies Used:
* Python
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Scikit Learn

# Author: FK Baffour
