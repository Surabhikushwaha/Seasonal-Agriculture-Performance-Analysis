# Seasonal Agriculture Performance Analysis

## Major Project – VOIS AICTE Batch 1 2026–2027

### Project Overview

Agricultural performance can vary across seasons because of environmental conditions, farming practices, resource availability and economic factors.

This project analyzes an agricultural dataset to identify seasonal patterns, compare agricultural performance, examine relationships between environmental/resource factors and agricultural outcomes, and develop evidence-based insights and recommendations.

---

## Problem Statement

Raw agricultural data does not clearly explain how agricultural performance changes across different seasons.

The objective of this project is to analyze the available agricultural data and investigate:

- Seasonal differences in agricultural performance
- Changes in crop productivity across seasons
- Resource usage and water efficiency
- Relationships between environmental conditions and yield
- Economic performance across seasons
- Crop-wise variations and unusual patterns

---

## Objectives

The main objectives of this project are:

- Explore and understand the agricultural dataset
- Clean and prepare the data for analysis
- Compare agricultural performance across seasons
- Analyze crop-wise performance
- Examine environmental factors such as rainfall and temperature
- Analyze resource usage and water efficiency
- Compare revenue, cost and profit
- Identify relationships using correlation analysis
- Visualize important patterns and trends
- Develop evidence-based conclusions and recommendations

---

## Dataset

The dataset contains **4,000 agricultural records and 28 columns**.

The dataset includes information related to:

- Farm and geographical information
- Crop and season
- Farm area
- Rainfall
- Temperature
- Humidity
- Sunlight
- Soil conditions
- Fertilizer and pesticide usage
- Seed quality
- Yield
- Production
- Market price
- Total cost
- Revenue
- Profit
- Water usage
- Water efficiency
- Disease and pest risk

### Data Cleaning

During data preprocessing:

- Duplicate records found: **0**
- Total missing values initially found: **120**
- Missing values were present in:
  - `Rainfall_mm` – 48
  - `Soil_Moisture_pct` – 40
  - `Yield_Tonnes_Ha` – 32
- Missing numerical values were handled using the **median**
- Final missing values: **0**
- Final dataset size: **4,000 × 28**

---

## Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Performed

### 1. Seasonal Performance Analysis

The average agricultural performance was compared across:

- Kharif
- Rabi
- Zaid

### 2. Yield Analysis

Average yield was compared across seasons and crops.

### 3. Profit Analysis

Average profit was compared across different seasons.

### 4. Revenue vs Cost Analysis

Average revenue and total cost were compared to understand seasonal economic performance.

### 5. Environmental Analysis

Relationships between:

- Rainfall and yield
- Temperature and yield

were explored using scatter plots.

### 6. Correlation Analysis

Correlation analysis was performed to examine relationships between agricultural variables and yield.

### 7. Crop-wise Analysis

Average yield, production, revenue and profit were compared across different crops.

### 8. Season × Crop Analysis

A heatmap was created to compare crop yield across different seasons.

### 9. Water Efficiency Analysis

Average water efficiency was compared across seasons.

---

## Key Findings

### Seasonal Findings

- **Kharif** recorded the highest average yield: **5.63 tonnes/ha**
- **Rabi** recorded an average yield of **5.04 tonnes/ha**
- **Zaid** recorded the lowest average yield: **4.64 tonnes/ha**

### Economic Findings

- Kharif recorded the highest average profit: **₹178,914.65**
- Rabi recorded an average profit of **₹87,689.47**
- Zaid recorded a negative average profit of approximately **−₹24,804.82**

The negative average profit in Zaid is associated with its average cost being higher than its average revenue.

### Water Efficiency

Average water efficiency:

- Kharif: **5.89 tonnes/1000 m³**
- Rabi: **5.19 tonnes/1000 m³**
- Zaid: **4.41 tonnes/1000 m³**

### Correlation Findings

Water efficiency showed the strongest correlation with yield:

- Water Efficiency → **0.91**
- Production → **0.88**
- Profit → **0.49**
- Revenue → **0.43**
- Water Used → **0.39**
- Rainfall → **0.03**
- Temperature → **0.01**

Correlation indicates association and does not by itself prove causation.

### Crop-wise Findings

**Sugarcane** recorded the highest average yield:

- Average Yield: **46.64 tonnes/ha**
- Average Profit: **₹817,187.99**

Other crops analyzed include:

- Maize
- Rice
- Wheat
- Chilli
- Groundnut
- Cotton
- Pulses

---

## Recommendations

Based on the analysis:

1. Improve water-use efficiency to support agricultural productivity.
2. Consider seasonal performance while planning agricultural activities.
3. Investigate the reasons for negative profitability during the Zaid season.
4. Use crop-wise performance data for better crop planning.
5. Monitor environmental and resource-related factors together with yield.
6. Use predictive analytics and machine learning for future seasonal planning.

---

## Future Scope

The project can be further enhanced by:

- Predicting seasonal yield using machine learning
- Predicting agricultural profit
- Integrating real-time weather data
- Using weather forecasts for agricultural planning
- Developing an interactive Power BI or Tableau dashboard
- Extending the analysis to district-level recommendations
- Developing agricultural risk prediction models

---

## Project Files

- `Seasonal_Agriculture_Performance_Analysis.ipynb` – Complete Jupyter Notebook
- Dataset – Agricultural dataset used for analysis
- Charts – Visualizations generated during analysis

---

## Conclusion

The analysis demonstrates clear variations in agricultural performance across seasons and crops.

Kharif performed best overall in terms of average yield, profit and water efficiency, while Zaid showed comparatively weaker economic performance.

Water efficiency showed a strong positive association with yield in the dataset. Crop-wise analysis also revealed substantial differences, with Sugarcane recording the highest average yield.

These findings can support better seasonal planning, resource management and further agricultural analysis.

---

## Author

**Student Name:** Surabhi kushwaha  
**College:** Gautam Buddha University 
**AICTE STU ID:** STU69a84546249181772635462 

### VOIS AICTE Batch 1 – 2026–2027
