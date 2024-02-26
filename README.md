# Mobile-Price-Range-Prediction

![Mobile Price Range Poster](https://github.com/meabhaykr/Mobile-Price-Range-Prediction/blob/main/Mobile%20Price%20Range%20Poster.jpg)

# Mobile Phone Price Range Prediction

## Overview

In the competitive mobile phone market, understanding the factors influencing prices is crucial for companies to make informed decisions regarding product offerings and pricing strategies. This project aims to predict price ranges of mobile phones based on various features using machine learning techniques.

## Problem Statement

The objective is to categorize mobile phone prices into different ranges (low cost, medium cost, high cost, and very high cost) based on features such as battery power, RAM, internal memory, camera specifications, and more. This will help mobile phone companies identify key factors influencing prices and optimize their market positioning.

## Dataset Description

The dataset comprises various features associated with mobile phones and their corresponding price ranges. Here's a brief description of the variables:

- **Battery_power**: Total energy a battery can store (mAh)
- **Blue**: Bluetooth availability (binary)
- **Clock_speed**: Microprocessor speed
- **Dual_sim**: Dual SIM support (binary)
- **Fc**: Front camera resolution (megapixels)
- **Four_g**: 4G availability (binary)
- **Int_memory**: Internal memory (GB)
- **M_dep**: Mobile depth (cm)
- **Mobile_wt**: Weight of the mobile phone
- **N_cores**: Number of processor cores
- **Pc**: Primary camera resolution (megapixels)
- **Px_height**: Pixel resolution height
- **Px_width**: Pixel resolution width
- **Ram**: Random access memory (MB)
- **Sc_h**: Screen height (cm)
- **Sc_w**: Screen width (cm)
- **Talk_time**: Battery talk time
- **Three_g**: 3G availability (binary)
- **Touch_screen**: Touch screen availability (binary)
- **Wifi**: Wi-Fi availability (binary)
- **Price_range**: Target variable with four categories indicating price range (0: low cost, 1: medium cost, 2: high cost, 3: very high cost)

## Project Summary

1. **Data Exploration and Cleaning**: The dataset is explored to understand its structure and identify any missing values or outliers. Data cleaning techniques are applied to ensure data quality and reliability.

2. **Feature Engineering**: Meaningful predictors are created by transforming or combining existing features. For example, the RAM to internal memory ratio and combined scores for camera quality and battery capacity are calculated.

3. **Exploratory Data Analysis (EDA)**: Relationships between features and price ranges are visually analyzed to uncover patterns and correlations.

4. **Modeling**: Three machine learning algorithms are utilized for prediction:
   - Random Forest Classifier
   - K-Nearest Neighbors
   - Support Vector Machine (SVM)
   
5. **Model Evaluation**: The models are evaluated based on their performance metrics, and hyperparameter tuning is performed to optimize the SVM model.

## Models Used and Results

- **Random Forest Classifier**: 
- **K-Nearest Neighbors**:
- **Support Vector Machine (SVM)**: Achieved a test accuracy of 96% after hyperparameter tuning, outperforming other models.

## Conclusion

The Support Vector Machine model demonstrated superior performance in predicting mobile phone price ranges. By leveraging this predictive model, mobile phone companies can gain valuable insights into the factors driving prices and make informed decisions to remain competitive in the dynamic market.
