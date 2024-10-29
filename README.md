# House Price Prediction Model

This repository contains research and analysis on a dataset for house prices. The dataset includes the following columns:

- **Square_Footage**: The total area of the house in square feet.
- **Num_Bedrooms**: The number of bedrooms in the house.
- **Num_Bathrooms**: The number of bathrooms in the house.
- **Year_Built**: The year the house was built.
- **Lot_Size**: The size of the lot on which the house is situated.
- **Garage_Size**: The size of the garage (if applicable).
- **Neighborhood_Quality**: A rating of the quality of the neighborhood.
- **House_Price**: The price of the house.

## Results

The analysis revealed that house prices are most strongly dependent on square footage. The model, which utilizes simple linear regression, performed exceptionally well in predicting house prices based on this feature.

## Performance

The predictive model was evaluated using Ordinary Least Squares (OLS) regression, which yielded a high R-squared value of 0.982. This indicates that approximately 98.2% of the variance in house prices can be explained by the model.

### Key Metrics:

- **Dependent Variable**: House Price (y)
- **F-statistic**: 38,610, indicating that the model is statistically significant (p-value < 0.001).
- **Coefficient for Square Footage**: The model showed that for each additional square foot, the house price increases by approximately $200.92.
- **Intercept**: The estimated base price of a house is around $52,450.

### Residual Analysis:

The Durbin-Watson statistic of 2.027 suggests that there is no significant autocorrelation among the residuals, which is favorable for the validity of the regression model. 

Overall, the simple linear regression model performed exceptionally well in predicting house prices based on square footage, confirming its importance as a key predictor in the dataset.




