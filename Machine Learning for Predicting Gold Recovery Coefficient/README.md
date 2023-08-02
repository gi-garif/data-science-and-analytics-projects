
| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Machine learning for predicting gold recovery coefficient | The main objective of this project was to build a model that predicts the gold recovery rate from gold-bearing ore based on data with parameters related to mining and purification processes.| Python, Pandas, Matplotlib, NumPy, Scikit-learn |

## Summary

- To prepare a model for effectively predicting the gold recovery coefficient from gold-bearing ore, I considered RandomForestRegressor and HistGradientBoostingRegressor with the selection of features with the highest correlation and their scaling.
- I obtained the final symmetric mean absolute percentage error (sMAPE) for RandomForestRegressor, which was 8.45 for the training dataset.
The sMAPE for HistGradientBoostingRegressor on the training dataset was 8.19.
- Due to the better result on the training data, I applied HistGradientBoostingRegressor to the test dataset, achieving a result of 7.8 sMAPE.
- The sMAPE of HistGradientBoostingRegressor outperformed the result of the dummy model (9.08), confirming the adequacy of the final model.
