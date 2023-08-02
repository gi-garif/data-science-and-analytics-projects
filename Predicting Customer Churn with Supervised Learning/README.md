| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Predicting customer churn with supervised learning | The task at hand was to predict whether a customer will leave the bank in the near future or not. Historical data on customer behavior and contract terminations with the bank have been provided for analysis.| Python, Pandas, Matplotlib, Scikit-learn |

## Summary
- In this study, linear regression, random forest, and extreme gradient boosting models were examined, and the target F1 metric of over 0.59 was achieved. The initial F1 metrics on the original data were as follows: Linear regression: 0.32, Random forest: 0.58, Extreme gradient boosting: 0.60.
- As the initial ratio of negative to positive class in the target parameter (customer churn) was 4:1, experiments were conducted with class weighting, increasing the positive class and reducing the negative class to correct the imbalance.
- The best results were achieved by increasing the minority class and using the extreme gradient boosting model. The F1 score of this model was 0.62, and the ROC_AUC was 0.76. The F1 score is 3 percentage points better than the same model before correcting the imbalance.
- According to historical data, customer churn primarily depends on the age of the clients and the number of bank products used by each client. Customers over the age of 45 and those who use only one bank product are the most likely to churn.
