
# ECON 3916 — Problem Set 4: The Model That Fit Too Well

## Overview

In this problem set, I analyzed a store revenue prediction model using simulated data from 400 stores. The goal was to understand why a model with a high R² could still make systematic prediction errors.

## What I Did

- Compared training and held-out model performance.
- Used residual plots to identify nonlinearity and heteroskedasticity.
- Investigated prediction errors for large stores and checked multicollinearity using VIF.
- Compared models with different levels of complexity.
- Used 5-fold cross-validation to select a model.
- Examined learning curves and data leakage.

## Key Results

- The original model had a training R² of about 0.955 and a held-out R² of about 0.920.
- The original linear model over-forecast the largest stores by about $7,100 on average.
- The quadratic model had the lowest cross-validation MSE, about 35.72 million.
- Its held-out MSE was about 48.84 million dollars squared.

## What I Learned

A high R² does not always mean a model makes reliable predictions. Residual analysis, cross-validation, and careful feature selection are important for understanding model performance. I also learned that using validation data during model development can make performance estimates too optimistic.
