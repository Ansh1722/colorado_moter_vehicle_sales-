# 🚗 Colorado-Motor-Vehicle-Sales-Analysis-and-Forecasting

A comprehensive data analysis and predictive modeling project focused on understanding the market dynamics and forecasting future sales of **Motor Vehicles** in 17 counties across Colorado (2008-2015). This project covers deep exploratory data analysis (EDA), Time Series decomposition, and develops a Machine Learning model for high-accuracy sales prediction.

---

## ✨ Project Overview

This repository contains the complete workflow for the Colorado motor vehicle sales analytics project. The analysis aims to uncover growth patterns, seasonal variations, and build a high-accuracy predictive tool for resource planning.

* **Goal:** Analyze 8 years of quarterly sales data to uncover trend, seasonal, and geographic patterns influencing the market.
* **Prediction:** Build and evaluate a supervised learning model (specifically **Random Forest Regression**) to predict the total dollar value of quarterly sales.
* **Objective:** Provide strategic insights into market growth and optimal timing for resource allocation based on predictive accuracy.

---

## 📊 Key Findings & Business Insights

The analysis was performed on **501 records** of quarterly sales, covering a total market value of **$88.2 billion**.

| Key Finding | Insight/Value | Source |
| :--- | :--- | :--- |
| **Market Growth** | The market demonstrated a strong **61.8%** total growth from 2008-2015, showing a significant economic recovery pattern. | `colorado-analysis-results-only.pdf` |
| **Geographic Concentration** | The market structure is highly concentrated: the **Top 5 counties control 64.4%** of the total market opportunity. | EDA, `Dashboard.pdf` |
| **Seasonal Peak** | Sales consistently peak in **Q3** (July-September), indicating optimal timing for inventory and marketing spend. | Time Series Decomposition, Notebook |
| **Predictive Accuracy** | The final model achieved **97.9%** explained variance in sales forecasting. | Model Evaluation |

### Market Tiers Defined (Based on Average Quarterly Sales)

* **Tier 1 (Primary Focus):** >$500M (e.g., Arapahoe, El Paso)
* **Tier 2 (Secondary Opportunity):** $200M – $500M (e.g., Denver, Jefferson)
* **Tier 3 (Emerging):** <$200M (The remaining counties, showing expansion potential).

---

## 🤖 Methodology & Machine Learning Performance

The entire analysis workflow, including the forecasting model, is detailed in the Jupyter Notebook.

| File | Description | Methodology Covered |
| :--- | :--- | :--- |
| `working.ipynb` | The main **Jupyter Notebook** containing all code for data cleaning, EDA, time series decomposition, feature engineering, and the full Random Forest Regression workflow. | EDA, Time Series, Random Forest Regression |
| `colorado-analysis-results-only.pdf` | Comprehensive Executive Summary and Strategic Business Insights. | Summary of Findings |
| `Dashboard.pdf` | Visualizations of sales over time, geographic concentration, and seasonal trends. | Visual Data Summary |

### Forecasting Model Details

| Metric | Model Performance | Interpretation |
| :--- | :--- | :--- |
| **Model** | Random Forest Regressor | Selected for high performance in forecasting based on historical, time-series derived features. |
| **Target** | Quarterly Motor Vehicle Sales | Continuous variable prediction (Regression). |
| **Explained Variance ($R^2$)** | **97.9%** | The percentage of the variance in the target variable (Sales) that is predictable from the features. |
| **Root Mean Squared Error (RMSE)** | **~19.98 Million** | The standard deviation of the residuals (prediction errors), indicating the average magnitude of error in sales predictions. |

---

## 📁 Repository Structure

| File Name | Description |
| :--- | :--- |
| `working.ipynb` | The main **Jupyter Notebook** containing all code for data cleaning, EDA, feature engineering, and the **Machine Learning** model training and evaluation. |
| `colorado_motor_vehicle_sales.csv` | The raw dataset used for the entire analysis, containing annual, quarterly, county, and sales data. |
| `colorado-analysis-results-only.pdf` | The detailed **Comprehensive Findings Report** summarizing the executive summary, market tiers, competitive analysis, and strategic business insights. |
| `Dashboard.pdf` | Key **Visual
jupyter notebook working.ipynb
