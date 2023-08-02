| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Time series analysis | The project involves building a taxi demand forecasting model for a taxi company based on historical taxi booking data at airports. The goal was to predict the number of taxi orders for the next hour to better manage and attract more drivers during peak demand periods.| Python, Pandas, Scikit-learn, Statsmodels |

## Summary
- For forecasting the number of taxi orders at airports, data for the period from March to September 2018 was analyzed.

- During the analysis, the following patterns were identified: there is a clear increase in the number of orders throughout the period, the highest number of orders is on Mondays and Fridays, the lowest number is on Tuesdays and Sundays, the peak order times are midnight and around 5 PM, and the lowest number of orders is at 6 AM. Lag features for 1 hour, 1 day, 1 week, and rolling averages for 1 week and 1 day were added as features for further use in ML models.

- To predict the demand, Linear Regression, LGBMRegressor, XGBoost, LSTM, Prophet and ARIMA models were trained. The RMSE metric was used to evaluate the prediction quality, and according to the task requirements, its value should not exceed 48 on the test set. The best result on the training set was achieved with the Linear Regression model (RMSE = 24.06), and its performance on the test set is 34.9.
