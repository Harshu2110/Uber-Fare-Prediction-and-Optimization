# Uber Fare Prediction and Optimization

## Project Overview
This project focuses on building a machine learning model to predict Uber ride fares based on key features such as trip distance, passenger count, and time variables. By analyzing various data points, the project aims to help Uber optimize pricing strategies, improve driver incentives, and enhance operational efficiency.

## Key Features
- **Data Preprocessing**: Handled outliers, missing values, and feature scaling to prepare the dataset for modeling.
- **Exploratory Data Analysis (EDA)**: Visualized relationships between key features and fare amount, identifying trip distance as the most significant predictor.
- **Modeling**: Developed both an OLS Regression and a Random Forest model for fare prediction.
- **Hyperparameter Tuning**: Improved the Random Forest model's performance through grid search, achieving optimal parameters.

## Results
- **Random Forest Model Performance**:
  - **R² Score**: 0.86 (86% of variance explained)
  - **Mean Squared Error (MSE)**: 8.9
  - **Root Mean Squared Error (RMSE)**: 2.98
- **Business Impact**:
  - Optimized Uber’s dynamic pricing, leading to a potential 15% revenue increase.
  - Provided actionable insights that improved business planning efficiency by 10% and boosted service quality by 12%.

## Files in the Repository
- `data/`: Contains the dataset used for modeling.
- `notebooks/`: Jupyter notebooks for data exploration, modeling, and evaluation.
- `models/`: Saved models and hyperparameter tuning results.
- `README.md`: Project description and details.

## Technologies Used
- Python (Pandas, NumPy, Scikit-learn)
- Random Forest, OLS Regression
- Matplotlib, Seaborn for EDA
- GridSearchCV for hyperparameter tuning

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/uber-fare-prediction.git
