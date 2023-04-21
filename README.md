# Store Sales Forecasting Analysis
This repository contains a sales forecasting analysis for Corporación Favorita, a large Ecuadorian-based grocery retailer. The analysis is based on a dataset obtained from Kaggle and includes information about holidays, oil prices, stores, sales, and transactions. In addition, web scraping was used to gather information about the inhabitants of each city.

The primary goal of this analysis is to predict store sales in order to reduce food waste related to overstocking and improve customer satisfaction. To accomplish this goal, a regression model was used to predict sales for each individual store.

## Data
The dataset used for this analysis can be found on Kaggle: [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview). The dataset includes information about holidays, oil prices, stores, sales, and transactions.

## Analysis
To predict store sales, a regression model was created for each of the 54 stores. This approach allows us to account for unique factors such as store location, size, and product offerings. By utilizing separate models for each store, we can more accurately predict sales and optimize inventory management strategies.

After running our regression models and analyzing the data, we have generated sales predictions for the period of August 1st to August 31st. These predictions are compared to the actual sales data for the first half of the month.

Overall, our predictions tend to be more conservative than actual sales data. However, the overall pattern of sales is consistent with what we expected based on previous analysis. We see a slight dip in sales immediately following payday on the 15th, followed by a gradual increase in sales leading up to the end of the month.

## Results and Insights
The results of our analysis provide valuable insights into consumer behavior and help us to refine our inventory management strategies. By continuing to analyze sales data and adjust our models accordingly, we can improve the efficiency and profitability of our stores and ultimately enhance the shopping experience for our customers.

It's important to note that external events, such as the magnitude 7.8 earthquake that struck Ecuador on April 16, 2016, can have a significant impact on supermarket sales. It's important to take these events into account when making sales forecasts to more accurately predict consumer behavior.
