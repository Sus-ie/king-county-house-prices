# King County House Prices Analysis

## Overview
This project analyzes house sale prices in King County, including Seattle, from May 2014 to May 2015. It aims to identify factors impacting house prices and build predictive models for house prices, with a special focus on properties valued at $650,000 and above.

## Data Description
The dataset contains 21 features, including:
- **Price**: The target variable for prediction. (This is our target)
- **Property Details**: Bedrooms, bathrooms, square footage, etc.
- **Location**: Latitude, longitude, and ZIP code.
- **Time-Based Features**: Year built, renovated.

## Features of the Project
- **Exploratory Data Analysis (EDA)**: Identify patterns, correlations, and anomalies.
- **Modeling**: Building and evaluating regression models:
  - Linear Regression
  - Ridge Regression
  - Lasso Regression
  - Decision Tree Regression
- **Outlier Removal**: Enhancing model performance by removing data anomalies.
- **Feature Selection**: Reducing multicollinearity and irrelevant variables.

## Key Results
- Decision Tree Regression showed the best performance for predicting house prices.
- The pipeline included custom treatments for Linear, Ridge, and Lasso regressions to fine-tune performance.
- Predictions for high-value houses (>$650,000) were made using the Decision Tree model.

## Tools & Technologies
- **Python**: Core programming language.
- **Libraries**: Pandas, Scikit-learn, Streamlit.
- **Visualization**: EDA plots and result comparison.

## Repository Contents
- **`datawork.py`**: Core data processing and modeling functions.
- **`GUI.py`**: Streamlit application for interactive exploration.
- **`EDA_notebook.ipynb`**: Detailed exploratory data analysis.

## Streamlit Application
The Streamlit application, `GUI.py`, provides an interactive interface to:
- Test different regression models (Linear, Ridge, Lasso, Decision Tree).
- Visualize performance metrics (R², RMSE, MSE, MAE).
- Predict house prices, including a dedicated module for predicting high-value houses (>$650,000).
- Compare results across models using visualizations.

## Deliverables
- **Notebook**: Step-by-step analysis and insights.
- **Streamlit Dashboard**: Interactive model and data exploration.
- **README**: Comprehensive documentation of the project processes and outcomes.

## Acknowledgments
This project was developed as part of an Ironhack Data Analytics course. Special thanks to:
- Caique Fabris
- Eduardo Parracho
- Imtiaz Faruk
- Isidre Munne-Bertran
- Nicolas Mirabet!
