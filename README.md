# What drives the price of a car?
Exploring the key determinants of used car prices.

## Overview
This project explores a dataset of used cars to understand the factors that influence their resale price. The dataset originates from Kaggle and contains information on over 426,000 cars (a cleaned subset of the original 3 million records).

The analysis follows the CRISP-DM framework (Cross Industry Standard Process for Data Mining), moving step by step from understanding the business problem, exploring and preparing the data, building predictive models, evaluation and finally translating the results into actionable insights.

The ultimate goal is to provide data-driven recommendations to a used car dealership on what makes a car more valuable, helping them refine their inventory strategy and pricing model.

See full analysis in the Jupyter Notebook [used-car-price](https://github.com/jasmitha-meka/used-car-price/blob/main/used-car-price.ipynb).
   
## Findings
* New cars up to 5 years old sell for the highest prices.
* Higher odometer lowers resale value.
* Diesel engines and 8-cylinder cars attract a price premium.
* Pickups and 4WD vehicles hold more value than sedans and FWD cars.

## Recommendations
* Focus on newer, low-mileage, diesel, 8-cylinder, pickup, and 4WD vehicles.
* Avoid overstocking sedans and high-mileage cars.
* Use predictive models for dynamic pricing.

## Technologies Used
* Python (Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly)
* Jupyter Notebook
