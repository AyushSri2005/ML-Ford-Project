# 🚗 Ford Used Car Price Prediction

> An end-to-end machine learning project that explores used Ford car data and predicts vehicle prices using Linear Regression.

## 📌 About the Project

Buying a used car involves comparing several factors such as model, year, mileage, fuel type, engine size, and transmission. This project explores how these factors are related to the price of used Ford vehicles and uses them to build a regression model for price prediction.

I worked through the complete machine learning workflow — from understanding and visualizing the data to preprocessing, feature encoding, scaling, model training, and evaluation.

I also experimented with **two different approaches for handling categorical variables** and compared their impact on model performance.

---

## 🎯 What I Wanted to Understand

The main goals of this project were to:

- Explore the factors associated with used Ford car prices
- Understand patterns and relationships within the dataset
- Prepare real-world tabular data for machine learning
- Handle categorical and numerical features appropriately
- Build a baseline regression model
- Compare different categorical encoding approaches
- Evaluate how well the model explains variations in car prices

---

## 📊 Dataset

The dataset contains **17,966 used Ford car records** with 9 features.

| Feature | Description |
|---|---|
| `model` | Ford car model |
| `year` | Manufacturing year |
| `price` | Selling price of the vehicle |
| `transmission` | Type of transmission |
| `mileage` | Mileage of the vehicle |
| `fuelType` | Type of fuel used |
| `tax` | Vehicle tax |
| `mpg` | Miles per gallon |
| `engineSize` | Engine size |

### Prediction Target

```text
price
