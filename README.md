# rice-price-estimation
The project is based on comprehensive food prices of Rice commodity in India. India is a developing country where the market prices fluctuate often due to agricultural practices, erratic weather changes, etc. Our aim is to analyze the price fluctuations of the commodities in India during a certain time period. Our motivation lies in correlating the prices of rice with the climatic factors as we intend to forecast the percentage change in the price of rice. The prices are sorted and discretized into 10 equal bins. The class that we are predicting is an integer from 1 to 10, where 1 is the least percentage change and 10 is the highest percentage change in price. Thus, the target variable is a label indicating percentage change in the price of Rice commodity.
Data Preprocessing:
The data preprocessing technique we have used is Standardization. Standardization is a useful technique to transform attributes with a Gaussian distribution and differing means and standard deviations to a standard Gaussian distribution with a mean of 0 and a standard deviation of 1.
In order to prepare our data for modeling, we created a ‘date’ column of datatype ‘datetime’ from the month and year and merged all the features into one dataframe. We added several economic and climate factors to correlate them to the price. The features date, 3,6,9,12 month means of price, CO2 and consumer index are found to be highly correlated. Below is the heatmap representing the correlation among the features:


![alt text](https://github.com/Roshni96/Rice_price_forecast/blob/master/correlation.png)

The Histogram plot of the training data:

![alt text](https://github.com/Roshni96/Rice_price_forecast/blob/master/histogram.png)

The time series plot of price of rice in India:
![alt text](https://github.com/Roshni96/Rice_price_forecast/blob/master/time_series_plot.png)

