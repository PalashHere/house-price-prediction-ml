# Data-Driven House Price Prediction for Real Estate Insights



## Project Overview
This project builds machine learning models to predict house prices based on property features like location, size, and amenities. It uses structured datasets with advanced preprocessing, feature selection, and model evaluation techniques. The project was done for Ideal Real Estate Co. to enable accurate, data-driven pricing decisions.

## Dataset
- Source: HousingDataSet.csv
- Records: 21,613
- Features: 21 attributes including bedrooms, bathrooms, sqft_living, waterfront view, latitude, longitude, etc.

## Tools and Technologies
- Python (Pandas, NumPy, Scikit-learn)
- Google Colab / Jupyter Notebook
- XGBoost, LightGBM, CatBoost
- Matplotlib, Seaborn

## Machine Learning Models
- Linear Regression
- Ridge and Lasso Regression
- K-Nearest Neighbors (KNN)
- Decision Tree Regressor
- Random Forest Regressor
- XGBoost Regressor
- LightGBM Regressor
- CatBoost Regressor (Best performer)

## Feature Engineering
- Extracted year and month from date fields
- Standardized numerical features
- Handled missing values using median imputation
- Treated outliers using Winsorization
- Applied feature selection techniques (SelectKBest, RFE, Tree-based)

## Model Performance
- Best Model: CatBoost Regressor
- R² Score: 0.8915
- Achieved the lowest MAE and RMSE among all models

## Business Impact
- Enabled accurate property pricing
- Improved decision-making for real estate professionals
- Optimized listing and selling strategies

## How to Run
1. Clone the repository.
2. Install required Python libraries.
3. Open the notebook in Google Colab or Jupyter.
4. Run all cells sequentially.

## License
This project is licensed under the MIT License.
