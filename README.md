# Simple Linear Regression

This is a Python program that demonstrates Simple Linear Regression using the scikit-learn library to model a linear relationship between years of experience and salary.

## Introduction

Simple Linear Regression is a statistical method used to model the relationship between two continuous variables - an independent variable (predictor) and a dependent variable (target). The program leverages the scikit-learn library, which provides an easy-to-use implementation of linear regression.

## Dependencies

Before running the program, make sure you have the following packages installed:

- numpy
- pandas
- matplotlib
- scikit-learn

You can install them using the following command:

```bash
pip install numpy pandas matplotlib scikit-learn
```

## How the Program Works

1. Import the necessary libraries:

The program starts by importing essential libraries, including numpy, pandas, matplotlib, and scikit-learn's LinearRegression.

2. Load and visualize the data:

The program loads salary data from the "Salary_Data.csv" file using pandas and creates a scatter plot to visualize the linear relationship between years of experience and salary.

3. Fit the Linear Regression Model:

Using scikit-learn's LinearRegression, the program fits a linear regression model to the data to estimate the relationship between years of experience and salary.

4. Predict New Values:

The program uses the fitted model to predict the salary for an employee with 12 years of experience. The predicted value is shown in red on the plot.

## How to Use

1. Ensure you have Python and the required dependencies installed on your machine.

2. Clone the repository to your local machine using the following command:

```bash
git clone https://github.com/wasim-jussab/simple-linear-regression.git
```

3. Change to the project directory:

```bash
cd simple-linear-regression
```

4. Make sure the "Salary_Data.csv" file is in the same directory as the Python script.

5. Run the program:

```bash
python simple_linear_regression.py
```

6. The program will display scatter plots of the salary data, the fitted linear regression model, and the predicted salary for an employee with 12 years of experience.

## Contributing

If you'd like to contribute to this project or report any issues, please feel free to open a pull request or submit an issue on the GitHub repository.

---
Created by [Wasim Jussab](https://github.com/wasim-jussab)
```
