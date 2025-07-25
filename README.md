# EV Adoption Forecasting

This project analyzes Electric Vehicle (EV) adoption patterns using machine learning techniques. The analysis is performed on county-level EV population data to understand and forecast EV adoption trends.

## Overview

The project uses a Random Forest Regressor to analyze and predict EV adoption rates based on various geographical and demographic factors. It includes data preprocessing, exploratory data analysis, and machine learning model implementation.

## Dataset

The project uses the "Electric Vehicle Population By County" dataset (`Electric_Vehicle_Population_By_County.csv`) which contains:

- County and State information
- Electric Vehicle (EV) totals
- Percentage of electric vehicles
- Temporal data (Date)
- Total of 20,819 data points with 10 features

## Technologies Used

- Python
- Key Libraries:
  - pandas: Data manipulation and analysis
  - numpy: Numerical computations
  - scikit-learn: Machine learning implementation
  - seaborn & matplotlib: Data visualization
  - joblib: Model persistence

## Features

1. **Data Preprocessing**

   - DateTime conversion
   - Missing value handling
   - Outlier detection and treatment using IQR method

2. **Exploratory Data Analysis**

   - Statistical summary
   - Feature analysis
   - Outlier visualization

3. **Machine Learning**
   - Random Forest Regression model
   - Model optimization using RandomizedSearchCV
   - Performance metrics evaluation (MAE, MSE, R2)

## Project Structure

- `EV_Adoption_Forecasting.ipynb`: Main Jupyter notebook containing the analysis
- `Electric_Vehicle_Population_By_County.csv`: Dataset file
- `RF_Tree.png`: Visualization of the Random Forest decision tree

## Setup and Usage

1. Ensure you have Python installed with the required libraries:

```bash
pip install pandas numpy scikit-learn seaborn matplotlib joblib
```

2. Clone the repository and navigate to the project directory

3. Open and run the Jupyter notebook:

```bash
jupyter notebook EV_Adoption_Forecasting.ipynb
```

4. Follow the notebook cells sequentially to understand the analysis process and results.
#

# Week 2:

## Theory and Concepts

### Data Type Handling

1. **Numeric Conversion**

   - Converting string data to numeric types
   - Handling mixed data types
   - Managing conversion errors using error handlers

2. **Date-Time Processing**
   - Converting string dates to datetime objects
   - Extracting temporal features (year, month)
   - Creating time-based aggregations

### Feature Engineering

1. **Lag Features**

   - Creating time-shifted versions of variables
   - Rolling means and averages
   - Percentage change calculations
   - Growth slope computation

2. **Temporal Features**
   - Months since start calculation
   - Cumulative sums and rolling metrics
   - Trend and seasonality extraction

### Model Selection and Evaluation

1. **Random Forest Regression**

   - Ensemble learning principles
   - Decision tree fundamentals
   - Feature importance analysis
   - Hyperparameter tuning concepts

2. **Time Series Concepts**

   - Temporal dependency
   - Seasonality patterns
   - Trend analysis
   - Forecasting principles

3. **Performance Metrics**
   - Mean Absolute Error (MAE)
   - Root Mean Square Error (RMSE)
   - R-squared (R²) interpretation
   - Model validation techniques

### Visualization and Analysis

1. **Time Series Plotting**

   - Historical vs forecast visualization
   - Trend line plotting
   - Cumulative growth charts

2. **Model Insights**
   - Feature importance visualization
   - Prediction vs actual comparisons
   - County-wise growth patterns
   - Regional adoption trends
