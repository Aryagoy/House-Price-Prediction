
# Predicting House Sale Prices 🏡

## Overview
This project aims to predict house sale prices using machine learning models. Leveraging data from Ames, Iowa, we explore various aspects of house pricing, such as property attributes, market trends, and local economic indicators. Our objective is to develop a robust predictive model that can help real estate professionals and homeowners make informed pricing decisions.

## Motivation
Accurately predicting house prices is critical for:
- **Homebuyers**: Know if a property fits within their budget.
- **Sellers**: Set competitive prices and maximize returns.
- **Real Estate Agents**: Assist clients with better insights.
- **Investors**: Optimize investments and assess risks.
- **Financial Institutions**: Determine accurate valuations for mortgages.

## Dataset 📊
The dataset contains house sale records from Ames, Iowa (2006–2010) and includes 82 features (like square footage, year built, lot size, etc.). The data was sourced from [Kaggle](https://www.kaggle.com/datasets/marcopale/housing).

## Models Used 🚀
We explored several machine learning models for predicting house prices:
- **Linear Regression**: Baseline model to establish reference performance.
- **Ridge and Lasso Regression**: Regularization techniques to reduce overfitting.
- **Decision Tree Regressor**: Captured non-linear relationships between variables.
- **Random Forest Regressor**: The best performing model, with RMSE of 28,724.68.

| Model                  | RMSE       | MAE        |
|------------------------|------------|------------|
| Baseline (Mean)         | 79,202.66  | 58,286.04  |
| Linear Regression       | 36,680.14  | 19,415.03  |
| Ridge Regression        | 36,447.63  | 19,468.99  |
| Lasso Regression        | 36,680.12  | 19,415.06  |
| Decision Tree Regressor | 35,849.98  | 23,200.52  |
| Random Forest Regressor | **28,724.68** | **18,283.59** |

## Results 📈
The Random Forest Regressor provided the best accuracy with a Root Mean Square Error (RMSE) of 28,724.68 and a Mean Absolute Error (MAE) of 18,283.59. This model outperformed others due to its ability to capture complex interactions between features.

## Future Work 🔮
- **Model Deployment**: Integrating the predictive model into real estate platforms or agent tools for real-time price predictions.
- **Enhanced Features**: Incorporate additional datasets (demographics, economic indicators) for richer insights.
- **Real-time Predictions**: Deploy the model in a web or mobile app for live use by homebuyers and sellers.

## Contributions 👥
- **Aditya Suresh**: Data Cleaning, Model Evaluation
- **Rhea Chandok**: Business Problem Definition, Feature Engineering
- **Sanam Palsule**: Data Visualization, Bias Analysis, Modeling
- **Arya Goyal**: Feature Importance, Modeling

## Links 🔗
- [Dataset on Kaggle](https://www.kaggle.com/datasets/marcopale/housing)
- [Google Colab Notebook](https://colab.research.google.com/drive/16HFlFpaw4lMAC--aV51RG_U0P3zKk01i?usp=chrome_ntp)

