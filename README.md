# Stock Price Prediction using Polynomial Regression

This project predicts the **State Bank of India (SBIN)** stock price using **polynomial regression** built completely from scratch — without using any external machine learning libraries.

It demonstrates how we can perform curve fitting and future prediction using pure **NumPy linear algebra** and **data visualization** with Matplotlib.

## Project Overview

The goal of this project is to estimate and predict stock prices from historical data using **polynomial regression**.  
Instead of using "scikit-learn", the regression coefficients are calculated manually using the **Normal Equation**:

theta_cap = (H^T H)^{-1} H^T X

where:

- H = Design matrix (polynomial features of time)  
- X = Actual closing prices  
- theta_cap = Model coefficients  

Once trained, the model can predict future stock values for a given day index.
