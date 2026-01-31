# Prodigy_ML_Task01

# House Price Prediction Using Linear Regression

## Overview
This project implements a **Linear Regression model** to predict house prices based on features such as **square footage, number of bedrooms, and number of bathrooms**. The model is trained on the **House Prices: Advanced Regression Techniques dataset** from Kaggle.

This project demonstrates:
- Loading and exploring a real-world dataset
- Handling missing values
- Feature selection and preprocessing
- Building, training, and evaluating a linear regression model
- Making predictions for new data

---

## Dataset
**Source:** [Kaggle House Prices Dataset](https://www.kaggle.com/c/house-prices-advanced-regression-techniques/data)  
**Files used:**
- `train.csv` → Training data with features and sale prices
- `test.csv` → Optional test data (if predicting unseen houses)

**Key Features Used:**
- `GrLivArea` → Above grade (ground) living area square feet
- `BedroomAbvGr` → Number of bedrooms
- `FullBath` → Number of full bathrooms
- `SalePrice` → Target variable

---

## Preprocessing
- Handle missing values:
  - Numerical columns → Fill with **median**
  - Categorical columns → Fill with **mode**
- Selected only relevant features to simplify the model.
- Train-test split performed to evaluate model performance.

---

## Model
**Algorithm:** Linear Regression  
**Evaluation Metrics:**
- **RMSE** (Root Mean Squared Error)
- **R² Score**  

**Coefficients:**  
The model learns the contribution of each feature to house price:
- Positive coefficient → Increase in feature increases predicted price
- Negative coefficient → Increase in feature decreases predicted price

---
## License

This project is open-source and free to use under the MIT License.

---
## Author

PRUONH KIMLIYA
Email: kimliyapruonh@gmail.com
Location: Phnom Penh, Cambodia
---
## References

Kaggle: House Prices - Advanced Regression Techniques
