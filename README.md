# Title
Module 8 prophet-challenge

## Source Data
Mercadolibre stock and google Search Data is available in static.bc-edx datasets which is pulled into Pandas dataframes for in-depth data analysis. We pulled 5 Years worth google search & stock data (Closing Price) from 2016 to 2020. The data is available in the form of csv files. 

## Data Processing, Transformation & Analysis:
2 Time Series datasets which is available at hourly frequency - one containing the stock price data and the other containing the google search data is read into Pandas dataframes to answer individual questions regarding the seach & stock price trend. The individual datasets are then combined into a single dataframe to answer the questions that require both the datasets like the corelation between the stock price and google search data. 

## Prophet Model Forecasting
The combined data sets is then fed into Prophet model to forecast the stock price for next 80 days approx. The forecasted stock price is then plotted along with the actual stock price to visualize the trend and answer questions like below:
1. What time of day exhibits the greatest popularity?
2. Which day of the week gets the most search traffic?
3. What's the lowest point for search traffic in the calendar year?

The code to answer all these questions and the forecasted stock price plot is available in the forecasting_net_prophet.ipynb file with detailed comments.