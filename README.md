# What drives the price of a car?
Exploring the key determinants of used car prices.

## Overview
This project explores a dataset of used cars to understand the factors that influence their resale price. The dataset originates from Kaggle and contains information on over 426,000 cars (a cleaned subset of the original 3 million records).

The ultimate goal is to provide data-driven recommendations to a used car dealership on what makes a car more valuable, helping them refine their inventory strategy and pricing model.

See full analysis in the Jupyter Notebook [used-car-price](https://github.com/jasmitha-meka/used-car-price/blob/main/used-car-price.ipynb).

## Methodology
The project follows the CRISP-DM framework:
1. Business Understanding – define dealership needs.
2. Data Understanding – explore and visualize dataset.
3. Data Preparation – clean, handle missing values, remove outliers.
4. Modeling – train Linear Regression, Ridge and Lasso models.
5. Evaluation – compare models using cross-validation (R² & RMSE).
6. Deployment (insights) – translate results into recommendations car dealership.
   
## Findings
* New cars up to 5 years old sell for the highest prices.
* Higher odometer lowers resale value.
* Diesel engines and 8-cylinder cars attract a price premium.
* Pickups and 4WD vehicles hold more value than sedans and FWD cars.

## Recommendations
* Focus inventory on newer, low-mileage vehicles.
* Prioritize diesel, 8-cylinder, pickup, and 4WD cars to maximize resale value.
* Avoid overstocking sedans and high-mileage vehicles, as they bring lower returns.
* Use predictive modeling for dynamic pricing to stay competitive.

## Next Steps
* Explore more pricing models to get more accurate predictions.
* Improve the quality of available car data to avoid losing useful information.
* Use additional charts to better understand customer preferences.
* Test the pricing model with new car listings to confirm its reliability.

## Technologies Used
* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly)
* Jupyter Notebook
