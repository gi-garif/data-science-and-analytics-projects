| Project | Description | Technologies used | 
| :---------------------- | :---------------------- | :---------------------- |
| Exploratory data analysis | Based on the data from Yandex.RealEstate service, the market value of various types of real estate properties was determined, along with the typical parameters of apartments based on their distance from the city center.| Python, Pandas, Matplotlib |

## Summary
- Area is a factor that affects the price the most. As the area of the apartment increases, its price also goes up. Apartments with a total area less than 20 sq.m. and greater than 150 sq.m. can be considered anomalies. It's also important to carefully consider listings with kitchen areas outside the range of 6-15 sq.m.

- Another critical factor is the number of rooms. Prices below 1,200,000 and above 12,000,000 can be viewed as abnormal. One-bedroom apartments tend to have the highest price per square meter, while three-bedroom apartments are relatively cheaper compared to other common options.

- Another significant factor is the floor level of the apartment. Apartments on the first floor are cheaper than those on other floors, while top-floor apartments are more expensive than first-floor ones, but cheaper than those on intermediate floors. Floors above 25 are a rarity. Most apartments are sold in five-story buildings and nine-story buildings.

- The farther from the city center, the cheaper the property, and the price on the outskirts can be significantly lower. The majority of selling apartments are located within 15 km from the city center and within 37 km from the nearest airport.

- Properties that take more than 500 days to sell can be considered outliers. The same can be said for apartments that sell within the first 45 days. Trends related to the publication date can also be observed: the cheapest properties are found in listings published on weekends, in May, and in June, while the most expensive ones are in April. During economic recessions, property prices tend to be lower compared to prosperous times.

- Among the 10 localities with the highest number of listings, real estate is most expensive in St. Petersburg and cheapest in Vyborg.
