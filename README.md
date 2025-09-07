# House Price Prediction

## Description
This project predicts house prices using Multiple Linear Regression. It includes data preprocessing, model training, evaluation, and visualization. Key features like area, bedrooms, bathrooms, parking, and amenities are used. The model identifies important factors affecting prices and provides a baseline for improvement.

## Problem Statement
The goal is to predict house prices accurately based on features, helping real estate companies optimize pricing strategies and support data-driven decisions.

## Dataset
- Features:
  - Area (sq. ft)
  - Bedrooms
  - Bathrooms
  - Parking
  - Amenities (e.g., Air Conditioning)
- Target: Price

## Methodology
1. **Data Preprocessing**: Handle missing values, encode categorical variables, split data.  
2. **Model Building**: Multiple Linear Regression using Scikit-learn.  
3. **Evaluation**: Metrics like R² Score, RMSE; Visualizations like Actual vs Predicted and Residual plots.  
4. **Insights**: Identify key factors influencing house prices and interpret model coefficients.

## Results
- **R² Score:** ~0.58  
- **RMSE:** 0.15  
- Key Influential Factors: Area, Bedrooms, Bathrooms, Parking, Amenities

## Conclusion
The model provides a baseline for real estate price prediction. It can be improved with additional features (e.g., location, property age) or advanced methods like Ridge/Lasso Regression and ensemble models. This project demonstrates practical ML application and hands-on experience in data analysis.

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/SuprabhaDas10/House-price-prediction.git
