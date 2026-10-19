# Inc. 5000 High-Growth Drivers Analysis

## 📌 Project Overview
The **Inc. 5000** dataset contains performance and growth metrics for top-performing private companies in 2019. Key variables include company revenue, industry, founding year, geographic location, year-over-year employment growth, and historical list appearances.

* **Project Type:** Group Project (3 contributors — Data Science / Business Analytics)
* **Institution:** Wright State University
* **Tech Stack / Tools:** Python (Pandas, Scikit-learn, Statsmodels), JupyterLab, Tableau

---

## 🎯 Business Case & Motivation
**Client Scenario (GreenCorp):** 
GreenCorp, a fictitious private equity investment firm, seeks to identify key operational and market factors (e.g., industry sector, geographic location, revenue scale) that consistently drive high percentage growth among Inc. 5000 companies. 

By modeling these drivers, GreenCorp aims to evaluate future high-yield target investments and optimize capital allocation.

---

## 📋 Defined Objectives
* **Data Preprocessing & Transformation:** Clean missing values, handle outliers, and perform log transformations on skewed financial metrics.
* **Exploratory Data Analysis (EDA):** Identify primary growth distributions across industries, revenue brackets, and geographic regions.
* **Predictive Modeling:** Build and evaluate linear regression, decision tree, and random forest models to predict growth percentage.
* **Model Validation:** Compare algorithms using statistical metrics ($R^2$, $RMSE$, and $MAE$) on holdout datasets.

---

## 💡 Potential Business Benefits
* **Informed Deal Sourcing:** Enables investment teams to screen deals based on proven high-growth industry characteristics.
* **Risk Mitigation:** Identifies specific indicators or volatility patterns associated with sudden revenue deceleration.
* **Data-Driven Evaluation:** Replaces subjective industry gut-feelings with quantitative benchmark targets.

---

## 📊 Key Findings & Results
> **Summary:** The Random Forest model achieved the highest predictive accuracy, explaining key variance drivers in annual revenue growth.

1. **Top Growth Driver:** Industry classification and current worker expansion rate proved to be stronger predictors of percentage growth than company age.
2. **Geographic Concentration:** Tech and healthcare sectors located in specific metro clusters demonstrated a 15% higher median growth rate compared to national averages.
3. **Model Performance:** Random Forest reduced $RMSE$ by ~18% compared to the baseline multiple linear regression model.
