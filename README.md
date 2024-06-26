# BoomBikes: Predicting Bike Sharing Demand

## General Information

BoomBikes, a US-based bike-sharing company, is preparing for post-pandemic recovery and growth. This project aims to develop a multiple linear regression model to predict bike rental demand ('cnt'). By understanding the factors influencing bike rentals, BoomBikes aims to adjust their strategy and gain a competitive edge in the market.

## Technologies Used

- Python 3.11.5
- pandas 2.2.2
- numpy 1.26.4
- matplotlib 3.8.4
- seaborn 0.13.2
- scikit-learn 1.5.0
- statsmodels 0.14.2

## Conclusions

### Factors Affecting Bike Rental Demand

#### Year (yr)
- **Coefficient:** 2021.4376
- **Interpretation:** There is a strong positive influence of the year on bike rental counts. As the year increases, the rental count increases significantly, possibly due to a growing trend in bike rentals over time.

#### Holiday (holiday)
- **Coefficient:** -839.4338
- **Interpretation:** Holidays negatively affect bike rental counts. On holidays, bike rentals decrease, possibly because people tend to stay indoors or use other modes of transportation.

#### Temperature (temp)
- **Coefficient:** 4496.6820
- **Interpretation:** Temperature has a very strong positive effect on bike rentals. As the temperature increases, the number of bike rentals increases significantly, indicating warmer weather encourages more rentals.

#### Windspeed (windspeed)
- **Coefficient:** -1301.2697
- **Interpretation:** Higher wind speeds have a negative impact on bike rentals. As wind speed increases, the rental count decreases, suggesting people are less likely to rent bikes in windy conditions.

#### Season (season_2 and season_4)
- **Coefficient for season_2:** 879.7754
- **Coefficient for season_4:** 1191.5878
- **Interpretation:** Certain seasons positively influence bike rentals. Season 2 (likely spring) and season 4 (likely fall) see an increase in bike rentals compared to the base season, indicating favorable weather conditions for biking.

#### Month (mnth_8 and mnth_9)
- **Coefficient for mnth_8:** 470.5913
- **Coefficient for mnth_9:** 1010.8056
- **Interpretation:** August (mnth_8) and September (mnth_9) positively affect bike rentals, likely due to favorable weather conditions during these months.

#### Weather Situation (weathersit_2 and weathersit_3)
- **Coefficient for weathersit_2:** -705.2619
- **Coefficient for weathersit_3:** -2449.8560
- **Interpretation:** Poor weather conditions negatively affect bike rentals. Weather situation 2 (moderate conditions) and weather situation 3 (bad conditions) lead to decreased rentals, with severe weather having the most significant negative impact.

### Insights

- **Weather and Temperature:** Favorable weather conditions and warmer temperatures significantly boost bike rentals.
- **Seasonality:** Spring and fall seasons see higher bike rentals, indicating seasonal patterns in bike rental demand.
- **Temporal Trends:** Bike rentals have been increasing over the years, suggesting a growing trend in bike-sharing.
- **Holidays and Adverse Conditions:** Holidays and poor weather conditions deter bike rentals, highlighting external factors' impact on rental behavior.

## Acknowledgements

This project was completed as part of an ML course at Upgrad.

## Contact

Created by [@sandeepks1] - feel free to contact me!
