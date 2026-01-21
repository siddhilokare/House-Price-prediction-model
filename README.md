# 🏡 House Price Prediction using Linear Regression

This project builds a **Linear Regression model** to predict house prices based on selected features from the Ames Housing dataset.  
It uses **GrLivArea (Living Area)**, **BedroomAbvGr (Bedrooms Above Ground)**, and **FullBath (Bathrooms)** as predictors for the target variable **SalePrice**.

---

## ⚙️ Features
- Loads housing dataset (`train.csv`)
- Selects key features for prediction:
  - Living Area (GrLivArea)
  - Bedrooms Above Ground (BedroomAbvGr)
  - Bathrooms (FullBath)
- Splits data into **training (80%)** and **validation (20%)**
- Trains a **Linear Regression model**
- Evaluates performance using:
  - Mean Squared Error (MSE)
  - R² Score
- Saves predictions to `train_predictions.csv`
- Visualizes **Actual vs Predicted Prices** with a scatter plot

---
