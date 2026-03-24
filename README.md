# Weather Data Analysis & Forecasting

### Ezequiel Oyola
### 24/03/2026
### Dataset: World Weather Repository (Daily Updating)

## PM Accelerator Mission

The Product Manager Accelerator Program is designed to support PM professionals through every stage of their careers. From students looking for entry-level jobs to Directors looking to take on a leadership role, this program has helped over hundreds of students fulfill their career aspirations.

## Introduction

- Objective:
    - Weather data analysis
    - Detect patterns
    - Build predictive models
- Type of data:
    - Meteorological variables
    - Air quality
    - Temporary information

## Data Cleaning & Preprocessing

- No missing values
- Elimination of imposible values
- Outlier treatment
- Normalization

Extreme outliers and errors were detected in the dataset.

## Exploratory Data Analysis (EDA)

There were redundant variables like temperature_celsius and feels_like_celsius, wind and gust, PM2.5 and PM10.
The precipitations and contamination variables presented extreme values and
high variability.

## Model Building

### model used: Random Forest Regressor

### Strategy:
- Time series
    - Temporal features
    - LAGS

### Evaluation:
- Cross-validation = 0.987
- Test score = 0.988
- Difference = 0.001

There is no signs of Overfitting. The model showed excellent generalizability, achieving a high level of accuracy in short-term temperature prediction.

## Visualization

- Histograms
- Correlation Heatmap
- Prediction vs Actual Values

## Conclusion

The analysis allowed us to understand the behavior of meteorological variables and build a robust predictive model. The combination of data cleaning, exploratory analysis, and machine learning techniques yielded accurate and reliable results.