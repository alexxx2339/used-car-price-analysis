Northern California Used Car Price Analysis

Author: Alejandro Alvarez

Project Overview

This project analyzes used vehicle pricing trends across Honda, Toyota, and Volkswagen vehicles in Northern California using R. The analysis includes data visualization, exploratory data analysis, and regression modeling to understand how mileage, vehicle age, and vehicle type influence resale value.

Dataset
61 vehicle listings collected from Craigslist
Honda, Toyota, and Volkswagen vehicles
Variables include:
Price
Mileage
Year
Brand
Vehicle Type
Fuel Type
Condition
Visualization 1: Mileage vs Price by Brand




Summary

Vehicle prices generally decrease as mileage increases. Toyota vehicles appear to maintain stronger resale values at higher mileage levels compared to some competing vehicles.

Visualization 2: Mileage vs Price by Vehicle Type




Summary

Trucks and SUVs tend to retain higher values even with higher mileage. Sedans show a wider range of depreciation patterns, while hybrid vehicles cluster around moderate mileage and price levels.

Regression Model

Model:

Price = f(Mileage, Year)

Key findings:

Mileage has a negative effect on vehicle price.
Newer vehicles command higher prices.
The model explains approximately 46% of the variation in used vehicle prices.
Future Improvements
Increase dataset size to 200+ observations.
Add additional vehicle brands.
Include location and condition scoring.
Develop machine learning price prediction models.
Create an interactive web application for vehicle price forecasting.