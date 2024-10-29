# Time Series
For the Time Series model, several options were considered. Models like ARIMA and PROPHET were trained, but we ultimately determined that the best option for a multivariate dataframe was to make the prediction with an XGBOOST model.

This XGBOOST model was also trained in different ways. Initially, we opted for daily training, but we observed that it was much slower and required a large amount of RAM and memory, and the predictions were less accurate on a weekly basis.

Finally, we decided to train the model with weekly sales data to achieve more realistic predictions. For this, we retained the sell price of the last week for each ID.

Here is the sales evolution, including a 4-week forecast.

Image.





