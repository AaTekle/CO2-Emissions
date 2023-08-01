# CO2 Emissions Linear Regression Model Project

## Introduction

This project aims to build a linear regression model to predict CO2 emissions based on various features related to vehicles. The dataset used in this project contains information about different car models and their corresponding CO2 emissions. By creating a linear regression model, we aim to understand the relationship between vehicle attributes and CO2 emissions, thereby enabling us to predict emissions for new or existing car models.

## Dataset

The dataset used in this project contains the following features:

- **Car_Model**: The make and model of the car.
- **Engine_Size**: The size of the car's engine in liters (L).
- **Cylinders**: The number of cylinders in the car's engine.
- **Fuel_Consumption_City**: The fuel consumption rate in liters per 100 kilometers (L/100 km) for city driving.
- **Fuel_Consumption_Hwy**: The fuel consumption rate in liters per 100 kilometers (L/100 km) for highway driving.
- **Fuel_Consumption_Comb**: The combined fuel consumption rate in liters per 100 kilometers (L/100 km) for city and highway driving.
- **Fuel_Type**: The type of fuel used by the car (e.g., Regular Gasoline, Premium Gasoline, Diesel).
- **CO2_Emissions**: The CO2 emissions in grams per kilometer (g/km) for the car.

## Project Goals

The main objectives of this project are as follows:

1. **Data Exploration**: Perform data exploration and gain insights into the dataset, such as identifying missing values, understanding the distribution of variables, and finding correlations between features and CO2 emissions.

2. **Linear Regression Model**: Build a linear regression model using the training data to predict CO2 emissions based on selected features.

3. **Model Evaluation**: Evaluate the performance of the linear regression model using appropriate metrics, such as mean squared error, R-squared, and visualizations to understand the model's accuracy and potential improvements.

4. **Data Analysis**: Evaluated the data to see which cars and models had the most impact on Emissions, highways, and city roads.

5. **Predictions**: Use the trained model to predict CO2 emissions for new car models or existing models not present in the training data.

## Getting Started

To run this project, follow these steps:

1. **Requirements**: Ensure you have the required Python libraries installed.

2. **Clone the Repository**: Clone this repository to your local machine using Git:

   ```
   git clone https://github.com/aarontekle/CO2-Emissions-Linear-Regression.git
   ```

3. **Data**: Place the dataset file (e.g., `CO2_emissions_dataset.csv`) in the project folder.

4. **Run the Jupyter Notebook**: Open the Jupyter Notebook file (`CO2_Emissions_Linear_Regression.ipynb`) using Jupyter Notebook in Visual Studio Code or any Jupyter environment. Execute the cells sequentially to perform data exploration, data preprocessing, model building, and evaluation.

5. **Results**: The final model's performance metrics and predictions will be displayed in the notebook, and visualizations will be saved in the project folder.

## Conclusion

By building a linear regression model, this project seeks to gain insights into the factors influencing CO2 emissions in vehicles and establish a predictive model for future emission estimates. The model's accuracy will help decision-makers in the automotive industry to optimize fuel efficiency, reduce greenhouse gas emissions, and contribute to environmental sustainability.
