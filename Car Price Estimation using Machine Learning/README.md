| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Car price estimation using machine learning | The project involves developing a car valuation model for a used car marketplace app, which aims to attract new customers by providing a quick and accurate estimation of the market value of their cars. | Python, Pandas, Lightgbm, Catboost, Random Forest |

## Summary
- To select the optimal algorithm for quickly calculating car price, I've examined three ML models: RandomForestRegressor, LGBMRegressor and CatboostRegressor. Their performance was evaluated using the RMSE metric.
- To improve the results, I used categorical feature encoding (TargetEncoding) and feature scaling (StandardScaler).
- RMSE values below 2500 were achieved for all three models.
- LGBMRegressor turned out to be the best model based on prediction quality, prediction speed and training time.
- The RMSE on the test set is 1624.
