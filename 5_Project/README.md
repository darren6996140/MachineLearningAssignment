# Public Transportation Ridership Prediction in Malaysia

## Table of Contents
- Introduction
- Project Objectives
- Dataset
- Methodology
- Results and Key Insights
- Project Structure
- Installation and Usage
- Contributors
- References
- Video Presentation

---

## Introduction
This project is part of the TDS3851 Machine Learning coursework assignment for Trimester 3, 2024/25 at MMU. It aims to predict public transportation ridership trends in Malaysia using historical data from LRT, MRT, Monorail, and KTM rail transit systems. Machine learning models are used to provide insights for transportation planners to optimize scheduling and resource allocation.

---

## Project Objectives
- Predict short-term ridership trends for LRT Ampang and MRT Kajang lines.
- Identify key factors influencing public transportation ridership.
- Analyze seasonal trends and daily/weekly variations.
- Develop machine learning models to forecast ridership patterns.

---

## Dataset
The dataset is sourced from **Malaysia's Open Data Portal** and contains historical ridership data from various rail networks. It includes daily passenger counts for LRT, MRT, Monorail, KTM, and ETS services.  

Dataset Link: [https://data.gov.my/data-catalogue/ridership_headline](https://data.gov.my/data-catalogue/ridership_headline)

---

## Methodology
1. **Data Preprocessing & EDA**  
   - Handle missing values  
   - Feature engineering (e.g., time-based features)  
   - Visualizing ridership trends  

2. **Dimensionality Reduction**  
   - Apply Principal Component Analysis (PCA)  

3. **Machine Learning Modeling**  
   - Use Ridge Regression for forecasting  
   - Train models with historical ridership data  

4. **Model Evaluation**  
   - Metrics: RMSE and R² Score  
   - Cross-validation for performance assessment  

5. **Prediction & Forecasting**  
   - Generate a 7-day ridership forecast  

---

## Results and Key Insights
### Model Performance:
- LRT Ampang Model: **R² = 0.96**, RMSE ≈ 6,926  
- MRT Kajang Model: **R² = 0.97**, RMSE ≈ 6,106  

### Key Findings:
- Ridership is **higher on weekdays** and **lower on weekends**.  
- Past ridership patterns are strong indicators of future ridership.  
- **COVID-19 significantly affected** ridership from 2020–2023.  
- Intermodal connections (Monorail, Komuter) impact demand.  

### Forecasting Insights:
- The **7-day forecast** indicates stable demand, with peak ridership on **Mondays and Fridays**.  
- Insights from the model can assist in **train schedule optimization** and **resource allocation**.  
---

## Installation and Usage
### Required Python Libraries:
```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyter
```
To Run the Jupyter Notebook:
jupyter notebook or open in Google Colab



