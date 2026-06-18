# HOUSEPRICE_PREDICTION

## About
This project is focused on predicting house prices using machine learning techniques. The goal is to understand how different house features influence price and build a model that can estimate house values.

## Dataset
The dataset contains information about houses such as:
- Area
- Number of bedrooms
- Number of bathrooms
- Stories
- Parking spaces
- Furnishing status
- Amenities like air conditioning, basement, and hot water heating
- Price (target variable)

## Data Preprocessing
- Handled missing values if present
- Removed duplicate records
- Converted categorical variables into numeric form using encoding techniques
- Prepared features for model training

## Models Used
Two machine learning models were trained:
- Linear Regression
- Random Forest Regressor

The dataset was split into training and testing sets (80/20 split) for evaluation.

## Model Evaluation
The models were evaluated using:
- R² Score
- Mean Absolute Error (MAE)
- Root Mean Squared Error (RMSE)

## Results
- Linear Regression: 0.65 R²
- Random Forest Regressor: 0.61 R²

Linear Regression performed slightly better on this dataset.

## Feature Engineering
New features were created such as:
- house_size_score
- total_rooms
- area_per_bedroom
- bathroom_bedroom_ratio
- amenity_score

These features showed correlation with price but did not significantly improve model performance.

## Key Findings
- Area is the most important factor affecting house price
- Bathrooms, parking, and stories also play a major role
- Amenities such as air conditioning increase property value
- Feature engineering does not always improve model accuracy

## Tools Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn

## Conclusion
This project demonstrates a complete machine learning workflow including data preprocessing, model building, evaluation, and feature analysis. The results show that simple models like Linear Regression can perform well for housing price prediction, and that understanding data is more important than just increasing model complexity.
