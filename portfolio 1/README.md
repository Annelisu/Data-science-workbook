# 🚗 Car Sales Data Analysis 📊

## Introduction: 📚

This repository contains an analysis of a car sales dataset. The dataset provides details about thousands of car sales records, allowing us to explore trends, prices, and key insights into the car sales industry.

## Dataset Structure: 📋

- **name** - 🚘 Type of car sold.
- **year** - 📅 The year the car was purchased.
- **selling_price** - 💵 The price at which the car is being sold.
- **km_driven** - 📏 The number of kilometers the car has been driven.
- **fuel** - ⛽ Fuel type of the car (petrol/diesel/CNG/LPG/electric).
- **seller_type** - 🏪 Indicates if the seller is an individual or a dealer.
- **transmission** - ⚙️ Gear transmission of the car (Automatic/Manual).
- **owner** - 👤 The number of previous owners of the car.

## Key Questions Explored: 🔍

1. 📅 **Trends in Car Sales**: What patterns emerge from sales over different years?
2. 💰 **Price Variation**: How does the price vary based on car type, fuel, and transmission?
3. 📏 **Kilometers Driven**: What is the relationship between the kilometers driven and the selling price of a car?
4. 🏪 **Seller Type Impact**: How does the seller type (individual or dealer) affect car prices?

## Python Libraries Used: 🐍

- pandas 🐼
- numpy 🔢
- matplotlib 📊

## Exploration: 🔍

Data Cleaning: 🧹
Initial dataset had 4,340 rows. After cleaning (removal of records with missing year or 'none' fuel type), the dataset was reduced to 3,886 rows.

* unique names: 1402
* unique seller type: 3
* unique transmission: 2
* unique owner: 5

## Summary: ✅
* Manual cars have much shorter price range and lower selling price compared to automatic cars.
* Price range for electric vehicle with prices fixed between 0 to 2.
* Test-drive cars have a higher selling price and highest median price among all categories.

This project offers a detailed analysis of car sales data, providing insights into the factors that influence car prices. It explores attributes such as kilometers driven, fuel type, and transmission, and examines how these impact sales trends.
