# Used Car Price Prediction Project

## Overview

This project aims to develop machine learning models for predicting the selling prices of used cars based on various attributes. The dataset used for this project is divided into two .csv files, "train" and "test", and contains information about used cars, including their name, manufacturing year, selling price, kilometers driven, fuel type, seller type, transmission, and owner history. The goal is to assist sellers in setting reasonable prices for their used cars and help buyers find the best value in the market.

## Project Components

### 1. Dataset

- The dataset is divided into two .csv files: "train.csv" and "test.csv".
- Attributes include car name, manufacturing year, selling price, kilometers driven, fuel type, seller type, transmission, and owner history.
- This dataset will be used to train and test the machine learning models.

### 2. Linear Regression

#### Multi-Feature Equation

- Linear regression will be implemented using the multi-feature equation approach.
- The model will be trained to predict selling prices based on multiple input features.
- Standardized regression coefficients (β) will be calculated.

#### Gradient Descent

- Linear regression will also be implemented using the gradient descent approach.
- Gradient descent is an optimization algorithm used to find the best-fit line for the data.
- It will also produce standardized regression coefficients (β).

#### Model Comparison

- The accuracy of both models will be compared using three evaluation metrics: Root Mean Square Error (RMSE), Mean Square Error (MSE), and Mean Absolute Error (MAE).
- This comparison will assess the performance of the linear regression models.

### 3. Polynomial Regression

- Polynomial regression models will be implemented using the same dataset, with degrees ranging from 1 to 10.
- RMSE values will be calculated for each degree to understand how the complexity of the model affects prediction accuracy.
- A plot will be created to visualize the relationship between model degree and RMSE.

## Repository Structure

The repository will have the following structure:

- **data/**: Contains the "train.csv" and "test.csv" datasets.
- **code/**: Contains the code for implementing linear regression, gradient descent, polynomial regression, and evaluating the models.
- **results/**: Stores the results, including RMSE values and visualizations.
- **README.md**: This file providing an overview of the project and instructions for running the code.

## Usage

1. Clone this repository to your local machine.
2. Install the necessary dependencies, which may include Python, Jupyter Notebook, and relevant libraries (e.g., NumPy, pandas, scikit-learn, matplotlib).
3. Run the Jupyter Notebook or Python scripts in the "code" directory to execute the linear regression and polynomial regression models.
4. Examine the results in the "results" directory, including RMSE values and plots.

## Contribute

If you'd like to contribute to this project or report issues, please feel free to create a pull request or open an issue on this repository.


## Authors

- Yahia Ehab
- Ahmed Shehata

## Acknowledgments
.
- Inspiration for this project came from Dr Caroline from the GIU Computer Science.

Thank you for your interest in this project! We hope it helps in understanding and implementing various regression techniques for predicting used car prices.
