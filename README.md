# 🏠 Real Estate Price Prediction Project

Welcome to the **Real Estate Price Prediction** project! This project leverages a **Random Forest Regression model** to predict house prices based on 14 key features. It is designed to provide accurate pricing insights, making it valuable for buyers, sellers, and real estate professionals.

---

## 📌 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Dataset](#dataset)
- [Model Details](#model-details)
- [Installation and Usage](#installation-and-usage)
- [Results](#results)
- [Future Improvements](#future-improvements)
- [License](#license)

---

## 🔍 Overview
This project uses machine learning to predict real estate prices. By analyzing 14 diverse features such as location, size, and amenities, the model aims to offer robust predictions that can be used for decision-making in the real estate market.

---

## 📊 Features
The prediction model is based on the following **14 features**:
    1. CRIM      per capita crime rate by town
    2. ZN        proportion of residential land zoned for lots over 
                 25,000 sq.ft.
    3. INDUS     proportion of non-retail business acres per town
    4. CHAS      Charles River dummy variable (= 1 if tract bounds 
                 river; 0 otherwise)
    5. NOX       nitric oxides concentration (parts per 10 million)
    6. RM        average number of rooms per dwelling
    7. AGE       proportion of owner-occupied units built prior to 1940
    8. DIS       weighted distances to five Boston employment centres
    9. RAD       index of accessibility to radial highways
    10. TAX      full-value property-tax rate per $10,000
    11. PTRATIO  pupil-teacher ratio by town
    12. B        1000(Bk - 0.63)^2 where Bk is the proportion of blacks 
                 by town
    13. LSTAT    % lower status of the population
    14. MEDV     Median value of owner-occupied homes in $1000's


---

## 🛠️ Technologies Used
- **Programming Language**: Python
- **Libraries**:
  - `numpy` and `pandas` for data manipulation
  - `matplotlib` and `seaborn` for visualization
  - `scikit-learn` for building the Random Forest model
  - `joblib` for saving and loading the model

---

## 📂 Dataset
The dataset includes **500+ real estate entries** sourced from a publicly available database. It has been preprocessed to handle missing values, outliers, and categorical encoding.

---

## 🔢 Model Details
- **Algorithm**: Random Forest Regression
- **Evaluation Metrics**:
  - Mean Squared Error (MSE)
  - Root Mean Squared Error (RMSE)
- **Performance**: Achieved an RMSE score of **2.94** on the test dataset.

---

## 💻 Installation and Usage
### Prerequisites
Ensure you have Python installed (version 3.7 or above). Install the required libraries using:

```bash
pip install -r requirements.txt
