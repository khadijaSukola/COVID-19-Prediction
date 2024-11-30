# COVID-19-Prediction

# Predicting Global COVID-19 Cases Using Machine Learning

## Project Overview
This project aims to predict global COVID-19 cases using a machine learning approach. By analyzing historical COVID-19 data, the project provides insights into case trends and helps inform public health decisions. It employs a Random Forest Regression model, achieving a high accuracy of 98.71%, and offers valuable findings about the pandemic's global impact.

---

## Objectives
1. Predict total COVID-19 cases globally using machine learning.
2. Provide actionable insights for public health decision-making.
3. Identify trends and patterns across continents.

---

## Data Source
The dataset is sourced from Kaggle (Worldometer dataset) and contains global COVID-19 statistics for various countries.
- The dataset includes the following key features:
  - Total Cases
  - Total Deaths
  - Total Recovered
  - Active Cases
  - Population
  - Mortality Ratio and Recovery Ratio (engineered features)

---

## Tools and Technologies
- **Languages**: Python
- **Libraries**:
  - Data Analysis: Pandas, NumPy
  - Visualization: Matplotlib, Seaborn
  - Machine Learning: Scikit-learn
- **Environment**: Google Colab

---

## Methodology
### 1. Data Preparation
- **Cleaning**: Removed missing values and standardized column names.
- **Feature Engineering**: Created new features such as Mortality Ratio and Recovery Ratio.

### 2. Exploratory Data Analysis (EDA)
- Generated visualizations:
  - Bar charts for total cases and deaths by continent.
  - Correlation heatmap to identify relationships between features.
  - scatter plot for visualizing the difference between the actual cases and predicted cases

### 3. Model Training
- Chosen Model: **Random Forest Regressor**
- Hyperparameters:
  - `n_estimators`: 100
  - `max_depth`: None
  - `min_samples_split`: 2
  - `min_samples_leaf`: 1

### 4. Model Evaluation
- Metrics:
  - **Root Mean Squared Error (RMSE)**: 8,936.73
  - **R² Score**: 0.9871
  - **Accuracy**: 98.71%

### 5. Results and Insights
- North America recorded the highest number of cases.
- Australi/oceania had significantly fewer cases compared to other continents.
- The Random Forest model demonstrated excellent predictive performance.

