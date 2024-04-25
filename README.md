# Predicting-CO2-Emissions-of-Light-Duty-Vehicles-using-Multiple-Regression
"FuelConsumption.csv," which contains information about fuel consumption ratings and estimated carbon dioxide emissions for new light-duty vehicles sold in Canada.

# Predicting CO2 Emissions of Light-Duty Vehicles using Multiple Regression

## Overview
This project aims to predict the carbon dioxide (CO2) emissions of new light-duty vehicles sold in Canada using multiple regression analysis. The dataset used contains model-specific fuel consumption ratings and estimated CO2 emissions for various vehicles.

## Dataset
The dataset used in this project is named FuelConsumption.csv and is publicly available. It includes the following attributes:
- MODELYEAR
- MAKE
- MODEL
- VEHICLE CLASS
- ENGINE SIZE
- CYLINDERS
- TRANSMISSION
- FUELTYPE
- FUEL CONSUMPTION in CITY (L/100 km)
- FUEL CONSUMPTION in HWY (L/100 km)
- FUEL CONSUMPTION COMB (L/100 km)
- CO2 EMISSIONS (g/km)

## Approach
1. **Data Preprocessing**: The dataset is loaded and preprocessed to handle missing values and encode categorical variables if necessary.
2. **Model Training**: A multiple regression model is trained using the training data.
3. **Model Evaluation**: The trained model is evaluated using appropriate metrics on a validation set.
4. **Predictions**: CO2 emissions are predicted on a test dataset using the trained model.
5. **Evaluation of Predictions**: The performance of the model is assessed on the test dataset using suitable evaluation metrics.
