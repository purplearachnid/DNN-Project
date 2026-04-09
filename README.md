# DNN-Project

Problem Statement
As power grids transition toward renewable energy sources like solar and wind, accurate short-term demand forecasting becomes critical for balancing generation and consumption. Traditional statistical models struggle to capture the nonlinear relationships between weather conditions, time-based patterns, and energy demand. This project develops a Deep Neural Network (DNN) to forecast hourly electricity demand using historical consumption data and weather features, supporting smarter grid operation and reduced reliance on fossil-based backup systems.
Dataset
Two datasets from Kaggle are used, both covering Spain (2015–2018) at hourly resolution:

energy_dataset.csv — hourly energy generation, load forecasts, and electricity prices
weather_features.csv — hourly weather data (temperature, humidity, wind, etc.) across major Spanish cities

👉 https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather

Download both files from Kaggle and place them in the root directory before running the notebook.

Libraries used:
numpy, pandas — data handling
matplotlib — visualizations
scikit-learn — StandardScaler, SimpleImputer, LinearRegression, MAE/RMSE metrics
tensorflow / keras — DNN model (Dense, Dropout, EarlyStopping)
os, zipfile, math, warnings — standard Python utilities
