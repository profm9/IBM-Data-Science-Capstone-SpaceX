# IBM Data Science Capstone: SpaceX Falcon 9 Landing Prediction

![Python](https://img.shields.io/badge/Python-3.10%2B-blue)
![Machine Learning](https://img.shields.io/badge/Machine%20Learning-Scikit--learn-orange)
![Data Analysis](https://img.shields.io/badge/Data%20Analysis-Pandas%2C%20SQL-green)

## Overview
This project predicts whether the first stage of a SpaceX Falcon 9 rocket will land successfully. By determining the likelihood of landing, we can estimate launch costs—a critical factor for competitors aiming to challenge SpaceX's market dominance.

This project covers the end-to-end data science lifecycle, from data acquisition and cleaning to interactive visualization and predictive modeling.

## Objectives
- **Data Collection:** Extract data using SpaceX API and Web Scraping from Wikipedia using BeautifulSoup.
- **Data Wrangling:** Perform data cleaning and feature engineering (binary classification of landing outcomes).
- **Exploratory Data Analysis (EDA):** Analyze trends via SQL (SQLite) and visualization tools (Pandas, Matplotlib, Seaborn).
- **Interactive Visualizations:** Use **Folium** for geospatial mapping of launch sites and **Plotly Dash** for real-time analytics.
- **Predictive Analysis:** Build and optimize classification models (Logistic Regression, SVM, Decision Tree, KNN) using GridSearchCV.

## Repository Structure

| Folder/File | Description |
| :--- | :--- |
| `data/` | CSV datasets and the SQLite database file. |
| `notebooks/` | Numbered Jupyter notebooks following the project workflow. |
| `app/` | Python script for the Plotly Dash interactive dashboard. |
| `ds-capstone-coursera.pdf` | Project Presentation in PDF Format. |
| `README.md` | Project summary and documentation. |

## Methodology
1. **Data Collection:** REST API integration and BeautifulSoup scraping.
2. **EDA:** SQL queries for mission statistics and Folium for proximity analysis to infrastructure.
3. **Dashboard:** Interactive app with dropdowns and range sliders for mission-specific filtering.
4. **Machine Learning:** Hyperparameter tuning with 10-fold cross-validation across four algorithms.

## Key Findings
- **Best Model:** The **Decision Tree Classifier** yielded the highest Cross-Validation accuracy of **87.5%**.
- **Success Trends:** Landing success rates reached approximately **90%** by 2019, demonstrating operational maturity.
- **Top Site:** **KSC LC-39A** is the most successful site, accounting for over **40%** of all successful landings.
- **Payload Optimization:** Success rates are notably higher for payloads within the **2,000kg to 4,000kg** range.

## Acknowledgments
- **IBM Data Science Professional Certificate** on Coursera.
- SpaceX API for providing public access to mission data.
