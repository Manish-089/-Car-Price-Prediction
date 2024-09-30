# Car Price Prediction

This project aims to build a machine learning model to predict the selling price of cars based on various features like present price, fuel type, transmission type, kilometers driven, and more. The dataset used contains information about cars including their names, year of manufacture, and other key attributes.

## Project Overview

The goal of this project is to train and evaluate regression models to predict car prices. Two models are used in this project:
1. **Linear Regression**
2. **Lasso Regression**

The models are trained using a dataset containing features about cars and their respective selling prices. The evaluation metrics and visualization methods are used to analyze the model performance.

## Dataset

The dataset used in this project contains the following columns:

- **Car Name**: The name of the car
- **Year**: The year the car was manufactured
- **Selling Price**: The price at which the car is sold
- **Present Price**: The current price of the car
- **Kms Driven**: The total kilometers driven by the car
- **Fuel Type**: The type of fuel used (Petrol/Diesel/CNG)
- **Seller Type**: Whether the seller is a dealer or an individual
- **Transmission**: Whether the car has a manual or automatic transmission
- **Owner**: The number of previous owners

## Installation

To run this project locally, you will need to have Python installed, along with the necessary libraries. You can install the required packages using:

```bash
pip install -r requirements.txt
