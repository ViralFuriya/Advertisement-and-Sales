# Linear Regression Demonstration

## Overview
In this demonstration, we explore the application of linear regression in predicting sales based on advertising expenditure across various media channels. The dataset comprises four variables: TV, radio, newspaper, and sales, with each row representing data from a specific advertising campaign.

## Libraries Used
- **pandas**: Data manipulation library.
- **numpy**: Fundamental package for scientific computing.
- **seaborn**: Statistical data visualization library.
- **matplotlib.pyplot**: Plotting library.
- **warnings**: Module for issuing warning messages.
- **scipy.stats**: Statistical functions and distributions.
- **statsmodels.stats.outliers_influence**: Module for outlier detection and influence analysis.
- **sklearn.model_selection**: Module for model selection and evaluation.
- **sklearn.linear_model**: Module containing various linear regression models.
- **sklearn.metrics**: Module for evaluating model performance.
- **statsmodels.formula.api**: Module providing a formulaic interface to statsmodels regression models.
- **statsmodels.api**: Module providing a wide range of statistical models and tests.

## Reading Advertising Data
The advertising data is read from the "advertising.csv" file into a pandas DataFrame named df using the `read_csv` function. The data has the first row as the header and the first column as the index.

## Evaluation Metrics Used
- **R-squared**: A measure of the proportion of variance in the dependent variable that is predictable from the independent variables.
- **Root Mean Squared Error (RMSE)**: A measure of the average deviation of predicted values from the actual values.
- **Adjusted R-squared**: A modified version of R-squared that adjusts for the number of predictors in the model.

## Conclusion
Through this demonstration, I've illustrated the practical implementation of linear regression for predictive analytics in marketing. We preprocess the data, train the linear regression model, evaluate its performance using relevant metrics, and interpret the results to gain insights into the relationship between advertising expenditure and sales.

Please note that this is a simplified explanation for demonstration purposes, and additional steps such as feature engineering and model tuning may be required for real-world applications.
