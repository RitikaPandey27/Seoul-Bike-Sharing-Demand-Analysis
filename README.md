# Seoul-Bike-Sharing-Demand-Analysis

## 🚲 Project Overview
The Seoul Bike Sharing Demand Analysis project explores the factors influencing bike rentals in Seoul, using machine learning models to forecast demand. This study aims to provide data-driven insights for optimizing urban mobility by understanding the relationship between environmental, temporal, and contextual factors and bike usage.

## 📊 Dataset
- **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)
- **Description:** The dataset contains hourly records of bike rentals, with key variables including:
  - Rented Bike Count
  - Weather indicators (Temperature, Humidity, Wind Speed, Rainfall, etc.)
  - Temporal variables (Hour, Day, Month, Season)
  - Holiday and Functioning Day markers

## 📈 Methodology
### 1. Exploratory Data Analysis (EDA)
- Identified seasonal patterns and commuter trends.
- Analyzed relationships between bike rentals and weather conditions.

### 2. Feature Engineering
- Created time-based features (hourly, daily, and seasonal indicators).
- Applied One-Hot Encoding for categorical variables.
- Addressed multicollinearity using Variance Inflation Factor (VIF) analysis.

### 3. Model Development
Implemented and compared the following models:
- **Linear Regression** (baseline model)
- **Ridge Regression** (L2 regularization)
- **Lasso Regression** (L1 regularization)
- **Random Forest** (ensemble learning)
- **XGBoost** (gradient boosting)

### 4. Model Evaluation
- **Metrics used:**
  - Mean Squared Error (MSE)
  - R-squared (R²)
- **Best Model:** XGBoost
  - **MSE:** 24,433.74
  - **R²:** 92.6%

## 🚀 Key Insights
- **Demand Patterns:** Higher bike rentals observed during peak commuting hours and warmer seasons.
- **Weather Impact:** Temperature and solar radiation positively correlated with demand, while rainfall and wind speed negatively affected rentals.
- **Holiday Trends:** Weekdays show bimodal rental peaks, while holidays have a smoother, leisure-driven pattern.

## 👥 Contributors
- **Garima Gambhir**
- **Ritika Pandey**
- **Sumedha Galgali**

## 📚 References
- [Seoul Bike Sharing Demand Dataset](https://archive.ics.uci.edu/dataset/560/seoul+bike+sharing+demand)
- Research papers on bike-sharing systems, urban mobility, and machine learning methodologies.

---
