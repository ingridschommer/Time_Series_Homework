# Time Series Homework
## In this assingment, I am using the tools we have learned about in class to predict future movements in the value of the Japanese yen versus the U.S. dollar.
## The time series analysis notebook uses the analysis to answer three questions. My answers, based on the analysis, are also included below: 
> Based on your time series analysis, would you buy the yen now?
>> Yes, since it is predicted to go up based on my Five Day Future Price Forecast Plot.

> Is the risk of the yen expected to increase or decrease?
>>Increase, based on my 5 Day Forecast of Volatility Plot.

> Based on the model evaluation, would you feel confident in using these models for trading?
>>No, as the p values are relatively high for both the ARMA and ARIMA models, I would not feel confident using those models for real life trading. However the Garch Model has a much lower p value, and I would feel more confident using that model.

The regression analysis notebook uses the analysis to answer the following question, which I have also provided my answer for: 
> Does this model perform better or worse on out-of-sample data compared to in-sample data?
>> This model performs better with out-of-sample data compared to in-sample-data, based on the comparison of the RMSE for in sample versus the RMSE for out of sample. However, overall the model does not perform very well. I am able to draw this conclusion by taking a look at the Returns and Predictions plot, where the predictions are very far off the actual return for the same date.



