# Porter Regression

Dataset: Kaggle [Porter Delivery Time Estimation](https://www.kaggle.com/datasets/ranitsarkar01/porter-delivery-time-estimation)<br>
License: [Attribution-NonCommercial 4.0 International (CC BY-NC 4.0)](https://creativecommons.org/licenses/by-nc/4.0/)

---

## Predicting delivery time for the order
**Problem Statement**
Porter is India's Largest Marketplace for Intra-City Logistics. Leader in the country's $40 billion intra-city logistics market, Porter strives to improve the lives of 1,50,000+ driver-partners by providing them with consistent earning & independence. Currently, the company has serviced 5+ million customers

Porter works with a wide range of restaurants for delivering their items directly to the people.

Porter has a number of delivery partners available for delivering the food, from various restaurants and wants to get an estimated delivery time that it can provide the customers on the basis of what they are ordering, from where and also the delivery partners.

This dataset has the required data to train a regression model that will do the delivery time estimation, based on all those features

## Modeling
Built a delivery time prediction model for Porter using regression techniques. Data preprocessing included handling missing values and outliers, along with feature engineering and standardization. Experimented with various models like Linear Regression, Decision Tree, XGBoost, AdaBoost, CatBoost, LightGBM, Random Forest and Neural Networks. LightGBM Regressor achieved the best performance with a minimum mean squared error of 0.653.