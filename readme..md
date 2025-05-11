# 🏡 Airbnb Price Prediction

This project builds a machine learning model to predict the price of Airbnb listings based on a variety of listing and host features. It uses real-world Airbnb data and follows a complete ML pipeline, from preprocessing to model evaluation and prediction.

## 📌 Objective

To estimate the price of a property listed on Airbnb using structured information such as number of bedrooms, amenities, availability, and host-related features. This model can be useful for:

- Property owners to set competitive prices
- Rental platforms to provide price recommendations
- Market analysis in the short-term rental industry

## 🧠 What this project does

- Loads and explores real Airbnb data
- Cleans the dataset by removing uninformative or redundant features
- Creates new variables (feature engineering) such as price per guest
- Selects the most relevant features using a Random Forest model
- Evaluates the model using 5-fold cross-validation
- Makes predictions on unseen data (test set)

## ⚙️ Methods Used

- Regression with **Random Forest**
- Feature selection based on importance
- Feature engineering (variable combinations)
- 5-fold cross-validation using RMSE as evaluation metric
- No hyperparameter tuning or external optimization (as instructed in the course)

## 📈 Results

- The model achieved a cross-validated **RMSE of 9.02€**, meaning that on average, the predictions are within 9 euros of the actual price.
- The most important variable in the model was `price_per_guest`, a feature created during the engineering phase.
- Predictions on the test set showed realistic and coherent price estimates for different listings.
