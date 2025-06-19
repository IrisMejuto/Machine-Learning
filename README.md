# 🏡 Airbnb Price Prediction

Machine Learning model that predicts nightly prices for Airbnb listings based on property characteristics and host information.

## 📋 Description

Supervised Machine Learning model using Random Forest regression to predict Airbnb listing prices. The system analyzes property features, host information, and location data to identify key pricing factors and help property owners optimize their pricing strategy.

## 📁 Project Structure

```
├── data/
│   └── airbnb-listings-extract.csv    # Raw Airbnb dataset
│   └── airbnb_test.csv    # Test Airbnb dataset
│   └── airbnb_train.csv    # Train Airbnb dataset
├── notebooks/
│   └── airbnb_price_prediction.ipynb  # Main analysis and modeling
├── module_utils.py                     # Dependencies and configuration
└── README.md                          # Project documentation
```

## 📊 Dataset

The dataset contains **11,824 Airbnb listings** with:

**Property Features**:
- Physical characteristics (bedrooms, bathrooms, accommodates, beds)
- Property type and room type
- Location data (coordinates, neighborhood)
- Amenities and available features

**Host Information**:
- Host response metrics and ratings
- Listing counts and verification status
- Host experience indicators

**Pricing Variables**:
- Nightly price (target variable)
- Additional fees (cleaning, security deposit)
- Pricing policies and cancellation terms

**Review Metrics**:
- Review scores across multiple dimensions
- Number of reviews and review frequency
- Guest satisfaction indicators

## 🧠 Model Architecture

**Random Forest Regressor**
- Ensemble method combining multiple decision trees
- Handles mixed data types (numerical + categorical)
- Provides feature importance rankings
- Robust to outliers and missing values

## 🔬 Methodology

**Preprocessing**:
- Data cleaning and removal of irrelevant variables
- Missing value handling with appropriate strategies
- Feature engineering without data leakage
- Categorical variable encoding

**Training**:
- Train/test split (80/20) with stratified sampling
- Cross-validation for model evaluation
- Feature selection based on importance
- Hyperparameter optimization

**Evaluation**:
- RMSE and R² metrics for regression performance
- Feature importance analysis for business insights
- Error analysis and model validation

## 📈 Results

**Model Performance**:
- Test RMSE: 
- R² Score: 
- Cross-validation results: 

**Key Insights**:
- Most important features: 
- Pricing factors discovered: 
- Business recommendations: 

## ⚙️ Main Dependencies

- **Python 3.x**
- **scikit-learn >= 1.3.0** - Machine learning algorithms
- **pandas >= 1.5.0** - Data manipulation
- **numpy >= 1.24.0** - Numerical computations
- **matplotlib >= 3.7.0** - Data visualization
- **seaborn >= 0.12.0** - Statistical visualization

Dependencies are loaded via `module_utils.py` configuration file.
