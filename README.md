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
