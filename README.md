# 🚗 Car Price Prediction using Linear Regression

## 📌 Project Overview

This project focuses on predicting the price of used cars using Machine Learning.

A Linear Regression model is trained using different car-related features such as model, year, mileage, fuel type, transmission, tax, MPG, and engine size.

The project covers the complete Machine Learning workflow from data cleaning to model evaluation.

---

## 📊 Dataset

The dataset contains **17,966 car records** with the following features:

- `model` - Car model
- `year` - Manufacturing year
- `price` - Car price (Target Variable)
- `transmission` - Type of transmission
- `mileage` - Car mileage
- `fuelType` - Type of fuel
- `tax` - Vehicle tax
- `mpg` - Miles per gallon
- `engineSize` - Engine size

---

## 🛠️ Technologies & Libraries Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## 🔄 Machine Learning Workflow

### 1. Data Understanding

- Checked dataset shape
- Checked data types
- Checked numerical and categorical columns
- Used `head()`, `info()` and `describe()`

### 2. Data Cleaning

- Checked missing values
- Checked duplicate records
- Removed duplicate rows
- Checked categorical values
- Checked numerical values
- Verified data types

### 3. Exploratory Data Analysis (EDA)

Performed different visualizations to understand the relationship between car features and price.

EDA included:

- Price Distribution
- Price vs Year
- Price vs Mileage
- Price vs Engine Size
- Price vs Fuel Type
- Price vs Transmission
- Price vs Tax
- Price vs MPG
- Correlation Heatmap
- Top 10 Car Models by Average Price
- Top 10 Most Common Car Models

### 4. Feature Engineering

Created a new feature:

```python
car_age = 2026 - year