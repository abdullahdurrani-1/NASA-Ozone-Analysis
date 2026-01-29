# NASA-Ozone-Analysis
This project analyzes the ozone level in north america on large data scale 
# 🌍 NASA Ozone Vertical Profile Analysis

**A comprehensive analysis of 28 years of ozone vertical profile data from NASA, featuring statistical analysis, machine learning, and deep learning approaches.**

## 📋 Project Overview

This project analyzes **539,808 ozone measurements** from NASA's observational data (1994-2021) across North America. The study focuses on understanding vertical ozone distribution patterns, statistical significance of variations, and building predictive models using both traditional ML and deep learning approaches.

### 🎯 Key Objectives
1. **Statistical Analysis**: Identify significant differences in ozone levels between sites and seasons
2. **Pattern Recognition**: Understand diurnal and seasonal variations
3. **Predictive Modeling**: Build accurate models for ozone concentration prediction
4. **Deep Learning Application**: Implement LSTM networks for time-series forecasting

## 📊 Key Findings

### 🔬 Statistical Insights
- **Site Comparison**: Colorado shows 6% higher average ozone than Alberta (p < 0.001)
- **Seasonal Effect**: Summer ozone levels are 25% higher than winter (p < 0.001)
- **Altitude Correlation**: Strong negative correlation between pressure and ozone (r = -0.74)
- **Diurnal Patterns**: Clear daily cycles with afternoon peaks

### 🤖 Model Performance
| Model | RMSE (ppbv) | MAE (ppbv) | R² Score |
|-------|-------------|------------|----------|
| Linear Regression | 2.3e-14 | 1.8e-14 | 1.0000 |
| Random Forest | 0.27 | 0.09 | 0.9998 |
| Decision Tree | 0.53 | 0.33 | 0.9991 |
| Neural Network | 0.35 | 0.15 | 0.9995 |
| LSTM | 0.28 | 0.11 | 0.9997 |

### 🌡️ Environmental Implications
- **Altitude Effects**: Higher altitudes show increased ozone concentrations
- **Seasonal Variations**: Photochemical production peaks in summer months
- **Geographical Differences**: Regional variations impact local air quality

## 🛠️ Technical Implementation

### Data Pipeline
```python
Raw Data → Cleaning → Feature Engineering → Modeling → Visualization
