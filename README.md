# Data-Science---Simple-Linear-Regression-SLR-
# Regression Modeling for Predicting Delivery Time and Salary Hike

This repository contains regression modeling code for predicting delivery time using sorting time and for predicting salary hike using years of experience. The project includes exploratory data analysis (EDA) and model building for both tasks. Here's an overview of the project:

## Problem Statements

### Task 1: Predicting Delivery Time
The goal of this part of the project is to predict delivery time based on sorting time. We perform EDA, do necessary transformations, and build simple linear regression models to predict delivery time.

### Task 2: Predicting Salary Hike
In the second part of the project, we build a prediction model for salary hike based on years of experience. Again, EDA is performed, and we create different models for prediction.

## Tools and Libraries

- Python
- Pandas
- NumPy
- Scikit-Learn (for building regression models)
- Matplotlib
- Seaborn

## Task 1: Predicting Delivery Time

### EDA

We start by exploring the delivery time dataset and perform EDA to understand the data's characteristics.

### Model Building

We build several regression models for predicting delivery time, including:
1. A direct model (no transformation)
2. A square root transform model
3. A square transform model
4. A cube root transform model
5. A logarithmic transform model

We compare these models based on Root Mean Squared Error (RMSE) and R2 Score.

## Task 2: Predicting Salary Hike

### EDA

We perform an initial exploration of the salary hike dataset and check for missing values and duplicated rows.

### Model Building

We create different models for predicting salary hike, including:
1. A direct model (no transformation)
2. A min-max transform model
3. A logarithmic transform model

The models are compared based on RMSE and R2 Score.

## Conclusion

We analyze and compare the models for both tasks and determine the best-performing models based on RMSE and R2 Score.

## Getting Started

You can run the regression models for delivery time and salary hike by following the code in the Jupyter Notebook provided in this repository.

### Prerequisites

Make sure you have the following libraries installed:

- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Seaborn

You can install them using `pip install`.

## Author

[Manish Parihar]

## License

This project is licensed under the MIT License.

## Acknowledgments

- The regression modeling project was created for educational purposes to learn about building regression models in Python.
- The datasets used are for demonstration and practice. You can replace them with your own datasets for real-world applications.

