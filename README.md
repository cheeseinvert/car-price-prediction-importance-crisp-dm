# What drives the price of a car?
An exploration of used car data to help dealership understand what drives the price of a car using CRISP-DM framework 

**Jupyter notebook:** https://github.com/cheeseinvert/car-price-prediction-importance-crisp-dm/blob/main/prompt_II.ipynb

## What is the problem? 
Using a dataset of used cars, I will explore the data to understand what drives the price of a car. The original dataset contained information on 3 million used cars. The provided dataset contains information on 426K cars to ensure speed of processing. My goal is to use the CRISP-DM framework applied to the dataset to understand what factors make a car more or less expensive. As a result of my analysis, I will provide clear recommendations to my client -- a used car dealership -- as to what consumers value in a used car.

## What is the data?
The dataset contains information on 426K used cars. The dataset contains the following 18 columns:

| Column Name | Description |
| --- | --- |
| id | The unique entry identifier for each car |
| region | The region where the car was sold |
| price | The price of the car |
| year | The year the car was made |
| manufacturer | The manufacturer of the car |
| model | The model of the car |
| condition | The condition of the car |
| cylinders | The number of cylinders in the car |
| fuel | The type of fuel used by the car |
| odometer | The number of miles on the car |
| title_status | The title status of the car |
| transmission | The transmission type of the car |
| VIN | The Vehicle Identification Number of the car |
| drive | The drive type of the car |
| size | The size of the car |
| type | The type of the car |
| paint_color | The color of the car |
| state | The state where the car was sold |

## What are the findings?
The findings suggest that the age of the car is the most important factor in determining the price of a car. My analysis used only used the year (age depreciation), odometer (wear depreciation), cylinders (engine size) and condition (physical state) to predict the price of the car. In order to improve the model, I would recommend using additional features such as the manufacturer (brand premium), the type of car (e.g. SUV, Sedan, Coupe), the size of the car (e.g. compact, mid-size, full-size), and the transmission type (e.g. automatic, manual). Perhaps I could also use the fuel type (e.g. gas, diesel, hybrid, electric) to improve the model.

## What do I recommend?
Based upon my findings, I recommend that the dealership focus on selling cars that are less than 5 years old. The dealership should also focus on selling cars that are in good condition and have low mileage, but the dominance of the age of the car in the model suggests that this is the most important factor in determining the price of a car.
