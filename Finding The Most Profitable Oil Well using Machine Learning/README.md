| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Finding the most profitable oil well using machine learning | The task was to build a model that can determine the region where oil extraction will yield the highest profit. By analyzing the given data and using machine learning techniques, I predicted which region is the most profitable for oil extraction. | Python, Pandas, Scikit-learn, Bootstrap |

## Summary:

- During the preliminary analysis, it was found that the second dataset exhibits a very strong correlation between the target feature and the feature f2. Thanks to this property, the RMSE metric of the linear regression model turned out to be the best for the second region. However, according to the prediction results, the average oil reserves are higher in the first (92.59 thousand barrels) and third regions (95.09 thousand barrels).

- It was determined that the sufficient oil volume for a break-even development of a new well is 111.11 barrels. In all three regions, the average oil reserves in the old wells are less than 111.11 barrels: 93, 69, and 95 thousand barrels, respectively.

- The potential average profits and risks, calculated using the bootstrap technique, are distributed as follows: 423.9 million rubles and 0.05% for the first region, 513.26 million rubles and 0.01% for the second region, 381.12 million rubles and 0.07% for the third region.

- The only region where the probability of losses is less than 2.5% is the second region. Therefore, it is recommended to drill a new well in this region.
