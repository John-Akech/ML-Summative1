# ML-Summative1

# Linear Regression Optimization Using Gradient Descent

This project demonstrates a simple linear regression model to predict sales based on TV marketing expenses. The assignment explores three different approaches: using **NumPy**, **Scikit-Learn**, and implementing **gradient descent** from scratch to optimize the cost function. Additionally, it includes a comparison of Linear Regression with a **Random Forest** and **Decision Tree** model.

## Table of Contents

1. [Overview](#overview)
2. [Dataset](#dataset)
3. [Getting Started](#getting-started)
4. [Implementation Steps](#implementation-steps)
5. [Model Comparisons](#model-comparisons)
6. [Results](#results)
7. [Dependencies](#dependencies)
8. [Contributing](#contributing)

## Overview
The goal of this project is to predict sales using a single feature: TV marketing expenses. To achieve this, we will:
- Build a linear regression model using **NumPy** and **Scikit-Learn**.
- Implement linear regression using **gradient descent**.
- Compare the performance of linear regression with **Random Forest** and **Decision Tree** models.

## Dataset
The dataset used in this project is `tvmarketing.csv`, which consists of two columns:
- **TV**: TV marketing expenses.
- **Sales**: Sales generated.

This is a simple, synthetic dataset to practice linear regression on a single feature.

## Getting Started
1. Clone the repository or download the project files.
2. Place the dataset file (`tvmarketing.csv`) in the `data` directory.

## Implementation Steps

### 1. Loading the Data
Use `pandas` to load the `tvmarketing.csv` file and print the first few rows to confirm the data has been loaded correctly.

### 2. Linear Regression with NumPy
- Use `np.polyfit` to fit a linear regression line to the data.
- Implement a prediction function based on the equation of the line: `Y = mX + b`.

### 3. Linear Regression with Scikit-Learn
- Reshape the data and split it into training and testing sets.
- Create and train a linear regression model using Scikit-Learn.
- Evaluate the model using **Root Mean Square Error (RMSE)**.

### 4. Linear Regression using Gradient Descent
- Implement gradient descent from scratch to optimize the sum of squares cost function.

### 5. Model Comparison
- Create and train **Random Forest** and **Decision Tree** models using Scikit-Learn.
- Compare the performance (in terms of RMSE) of all models, ranking them from best to worst.

## Model Comparisons
This section will compare the RMSE values of each model:
- **Linear Regression** (NumPy)
- **Linear Regression** (Scikit-Learn)
- **Gradient Descent**
- **Random Forest**
- **Decision Tree**

## Results
Results are presented as a ranked list based on RMSE, showing the best to worst performing models.

## Dependencies
The following packages are required:
- `numpy`
- `pandas`
- `matplotlib`
- `scikit-learn`

You can install them with:
```bash
pip install numpy pandas matplotlib scikit-learn

Contributing
Feel free to fork this project, open issues, and submit pull requests.

This README provides an organized overview, including steps for implementing and comparing the models. Let me know if you need further customization!
