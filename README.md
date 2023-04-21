# Store Sales Forecasting Analysis
This repository contains a sales forecasting analysis for Corporación Favorita, a large Ecuadorian-based grocery retailer. The analysis is based on a dataset obtained from Kaggle and includes information about holidays, oil prices, stores, sales, and transactions. In addition, web scraping was used to gather information about the inhabitants of each city.

The primary goal of this analysis is to predict store sales in order to reduce food waste related to overstocking and improve customer satisfaction. To accomplish this goal, a regression model was used to predict sales for each individual store.

## Data
The dataset used for this analysis can be found on Kaggle: [Store Sales - Time Series Forecasting](https://www.kaggle.com/competitions/store-sales-time-series-forecasting/overview). 

I did web scraping to obtain information about the inhabitants of each city where the stores are located.

If you want to check the presentation is here: [Presentation: Predicting Store Sales](https://www.canva.com/design/DAFgn8TTWMc/qgdD3BjLb4vdmdqAgEH32w/edit?utm_content=DAFgn8TTWMc&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton)

## Analysis
To predict store sales, a regression model was created for each of the 54 stores. This approach allows to account for unique factors such as store location, size, and product offerings. By utilizing separate models for each store, we can more accurately predict sales and optimize inventory management strategies.

## Results and Insights

After running our regression models and analyzing the data, we have generated sales predictions for the period of August 15th to August 31st. These predictions are compared to the actual sales data for the first half of the month.

Overall, our predictions tend to be more conservative than actual sales data. However, the overall pattern of sales is consistent with what we expected based on previous analysis. We see a slight increase in sales immediately following payday on the 15th, followed by a gradual increase in sales leading up to the end of the month.

One exception to this pattern is the thirty first, which appears to have lower sales than expected. This could be due to a variety of factors, such as a local event or holiday that I did not account for in the models.

I will  continue  analyzing sales data and adjust the models. As you can see the score is 2.39 which means that the RMSLE has this value. The best results obtained in this competition have been models that have used time series, which I will try in the future to improve my model. 
