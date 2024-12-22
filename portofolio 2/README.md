# 🚗 Car Sales Price Prediction & Data Ethics Analysis 📊

## Introduction: 📚

This repository contains Part 2 of the car sales data analysis. The main objectives are to build predictive models to estimate car selling prices and assess the ethical considerations related to data usage.

## Goals: 🎯

1. **Car Price Prediction**: Build linear regression models to predict car prices using cleaned data.
2. **Data Ethics**: Explore ethical issues in the use of car sales data.

## Dataset Structure: 📋

- A cleaned car sales dataset (`car_sells_clean_data.csv`) is used in this analysis.
- **Features** include various car attributes like car type, year, kilometers driven, fuel type, seller type, transmission, and owner details.

## Explorations: 🔍

### Data Exploration: 🧹
- The dataset has been pre-cleaned and prepared for analysis.
- Find various correlation in:
  * Year and Selling Price: 0.41110276220633124
  * KM Driven and Selling Price: -0.17720277985723884
  * Seller Type and Selling Price: -0.20863704840276948
  * Fuel Type and Selling Price: -0.2776270434173492
  * Owner and Selling Price: -0.2055235873112245
- Split and train datasets
- Ethical analysis in showcasing infographics

### Predictive Modeling: 🤖
- **Linear Regression Models**: Models are trained using the `linear_model.LinearRegression` class from scikit-learn.
- **Train-Test Split**: Data is split into training and testing sets using an 80-20 split.
- **Performance Metrics**: The model’s performance is evaluated using the R² score.

### Data Ethics: 🤔
- Explores potential ethical concerns with data collection, privacy, and fairness.
- Reflects on how this data could be misused and suggests mitigation strategies.

## Python Libraries Used: 🐍

- pandas 🐼
- numpy 🔢
- scikit-learn 🤖
- seaborn 🎨
- matplotlib 📊

## Findings: ✅
* Year and selling price has the strongest correlation among all the other features
* KM Driven and selling price displays negative correlation, indicating its weak correlation
* The analysis of 4 MSE models show that model B has the highest MSE, meaning predictions are far from actual values
* implementing ethical data visualisation is critical in maintaining unbiased information
  
This project explores how linear regression models can predict car prices and examines key ethical issues in the use of car data. It provides insights into how feature selection and data partitioning impact model performance.
