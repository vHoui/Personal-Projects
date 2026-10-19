# Inc. 5000 High-Growth Drivers Analysis

## Project Overview
The **Inc. 5000** dataset contains performance and growth metrics for top-performing private companies in 2019. Key variables include company revenue, industry, founding year, geographic location, year-over-year employment growth, and historical list appearances.

* **Project Type:** Group Project (3 contributors — Data Science / Business Analytics)
* **Institution:** Wright State University
* **Tech Stack / Tools:** Python (Pandas, Scikit-learn), JupyterLab, Tableau and RapidMiner (AI studio)

---

## Business Case & Motivation
**Client Scenario (GreenCorp):** 
GreenCorp, a fictitious private equity investment firm, seeks to identify key operational and market factors (e.g., industry sector, geographic location, revenue scale) that consistently drive high percentage growth among Inc. 5000 companies. 

By modeling these drivers, GreenCorp aims to evaluate future high-yield target investments and optimize capital allocation.

---

## Defined Objectives
* **Data Preprocessing & Transformation:** Clean missing values, handle outliers, and perform log transformations on skewed financial metrics.
* **Exploratory Data Analysis (EDA):** Identify primary growth distributions across industries, revenue brackets, and geographic regions.
* **Predictive Modeling:** Build and evaluate linear regression, decision tree, and random forest models to predict growth percentage.
* **Model Validation:** Compare algorithms using statistical metrics ($R^2$, $RMSE$, and $MAE$) on holdout datasets.

---

## Method: Using Linear Regression, Decision tree and Random Forest for analysis.

---

## Data Exploration
* **Data review:** Refer to word doc report.
---

## Potential Business Benefits
* **Informed Deal Sourcing:** Enables investment teams to screen deals based on proven high-growth industry characteristics.
* **Risk Mitigation:** Identifies specific indicators or volatility patterns associated with sudden revenue deceleration.
* **Data-Driven Evaluation:** Replaces subjective industry gut-feelings with quantitative benchmark targets.

---

## Key Findings & Results
> **Summary:** 

Company 'age' has the biggest impact on company growth by large followed by the "IT Services" and "Environment Services" industry negatively according to the Linear regression model. Meaning that older companies that have been successful for a long time may be pursuing slow and steady growth. Positive growth has been seen in the 'Construction', 'Retail' and 'Logistics & Transportation' industries. The decision tree model agreed very closely with the linear regression model, the random forest model found that "Small_Workforce" is also a significant factor although the significance is a lot lower than company age. All models have also found that factors outside external influences that we cannot see in this data. When using the 80% training and 20% validation method it achieves the results ($R^2$):

* Linear Regression: 0.1150
* Decision Tree: 0.1103
* Random Forest: 0.1205

This is not a complete failure as it still helps guide the company that there some takeaways to look at in this dataset.
