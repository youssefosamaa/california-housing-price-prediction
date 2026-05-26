# California Housing Price Prediction

A machine learning project focused on predicting California housing prices using demographic and geographic data from the California Housing dataset.

## Project Overview

This project implements an end-to-end machine learning workflow including:

- Data cleaning and preprocessing
- Exploratory Data Analysis (EDA)
- Feature engineering
- Data visualization
- Categorical encoding
- Model training and evaluation

The goal is to predict median house values based on housing, population, and location-related features.

---

## Dataset Features

The dataset includes features such as:

- Longitude & Latitude
- Housing median age
- Total rooms & bedrooms
- Population & households
- Median income
- Ocean proximity

Target variable:

- `median_house_value`

---

## Workflow

### 1. Data Preprocessing
- Removed missing values
- Applied logarithmic transformations to skewed numerical features
- Encoded categorical variables using One-Hot Encoding

### 2. Exploratory Data Analysis
- Distribution visualizations using histograms
- Correlation heatmaps
- Geographical visualization of housing prices

### 3. Feature Engineering
Created additional features including:
- Bedroom-to-room ratio
- Rooms per household ratio

### 4. Model Training
Implemented a Linear Regression model using Scikit-learn.

### 5. Model Evaluation
Evaluated model performance using the R² score.

**Model Performance:**
- R² Score: **0.66**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Jupyter Notebook

---

## Key Skills Demonstrated

- Machine Learning Pipelines
- Data Preprocessing
- Feature Engineering
- Exploratory Data Analysis (EDA)
- Data Visualization
- Regression Modeling
- Model Evaluation

---

## Future Improvements

Possible future enhancements include:
- Trying advanced regression models
- Hyperparameter tuning
- Cross-validation
- Feature scaling optimization
