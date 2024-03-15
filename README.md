# Financial Data Processing and Feature Selection

## Description
This project focuses on processing financial data and selecting relevant features for predictive modeling. It includes data processing techniques like concatenation, sampling, division, and train-test split. The project explores various feature selection methods, including embedded methods (LightGBM and Lasso), filter methods (mutual information, r-value, and f-value), and a wrapper method using LGBMRegressor. For prediction, models such as TABNET, MLP (with PyTorch and scikit-learn implementations), Random Forest, and Linear models are used. The performance of these models is evaluated using metrics like RMSPE (Root Mean Squared Percentage Error) and MSE (Mean Squared Error).



## Requirements
- pandas
- numpy
- seaborn
- matplotlib
- dask
- joblib
- scikit-learn
- lightgbm
- pytorch_tabnet

## Usage
1. Process the raw data using the provided functions.
2. Sample the data to make it more manageable.
3. Divide the data based on time periods to capture different market behaviors.
4. Split the data into training and testing sets.
5. Use various feature selection methods to identify the most relevant features for modeling.
6. Train and evaluate models using the selected features.

## Authors
- Yukai Lin (yorklin.math@outlook.com)

## License
No license information provided.
