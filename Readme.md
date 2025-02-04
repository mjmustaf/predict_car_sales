# Used Car Price Prediction Model

## Overview
This project develops a predictive model to determine the pricing of used cars based on various features such as age, mileage, and make/model. Aimed at helping used car dealerships optimize their inventory and pricing strategies, this analysis uses data from Kaggle’s used car dataset covering over 426K listings.

## Data
The dataset includes attributes like make, model, mileage, year, and selling price of used cars. Data cleaning and preprocessing were performed to adjust for missing values and outliers, ensuring quality inputs for model training.

## Methodology
We employed the CRISP-DM process, starting with business and data understanding, followed by data preparation where we handled missing data, feature engineering, and normalization. We used Lasso regression for modeling due to its effectiveness in feature selection, aiding in understanding impactful predictors.

## Findings
Key findings indicate that mileage and car age significantly influence used car prices negatively, suggesting dealers should focus on newer, low-mileage cars for better profitability. The model’s mean squared error (MSE) on test data is approximately 7.07, indicating reasonable prediction accuracy.

## Usage
To run the analysis, clone the repository and install required Python libraries as listed in `requirements.txt`. Open the Jupyter notebook `Used_Car_Price_Prediction.ipynb` to view the code and analysis.

## Contributing
Contributions to the project are welcome. Please fork the repository and submit a pull request with your enhancements.


## Link to Notebook
[Used Car Price Prediction Notebook](https://github.com/yourusername/used-car-pricing)

