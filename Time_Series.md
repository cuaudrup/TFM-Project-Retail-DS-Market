# Time Series
For the Time Series model, several options were considered. Models like ARIMA and PROPHET were trained, but we ultimately determined that the best option for a multivariate dataframe was to make the prediction with an XGBOOST model.

This XGBOOST model was also trained in different ways. Initially, we opted for daily training, but we observed that it was much slower and required a large amount of RAM and memory, and the predictions were less accurate on a weekly basis.

Finally, we decided to train the model with weekly sales data to achieve more realistic predictions. For this, we retained the sell price of the last week for each ID.

Here is the sales evolution, including a 4-week forecast.

Image.

Our time series model provides 4-week forecasts, but by repeating this process three times, we were able to extend our predictions to 12 weeks and graph the results. However, the main focus is on the first 4 weeks, as this is the part of the model that is trained with fully real data. Ideally, we would iterate our model each time we have new real data, rather than using data that matches our model's previous predictions.

Image.

Looking at this more detailed global graph for 2016, we can observe our first 4 weeks of predictions, which are marked in the designated area on the graph. They are characterized by an increase in sales compared to our starting point, which is week 17. This rise is around 5.5% during the first two weeks, then decreases by 1.5% over the following two weeks.

Thus, we can conclude that at the end of our 4-week predictions, there is an approximate 3% increase in total revenue. In the subsequent weeks, we also anticipate exponential growth, which aligns with trends from previous years, as summer is the season with expected peak sales.

Regarding global predictions by category, we find that the Supermarket category continues to contribute the most revenue, with a 6% increase at two weeks relative to week 17, but only a 2% increase by the end of the 4 weeks. On the other hand, the category showing the highest growth is Accessories, with an increase of around 7% in the second week, reaching up to 7.5% by the end of the 4-week forecast period compared to week 17.
