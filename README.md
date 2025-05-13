# README

## Project Overview
This project explores the causal and predictive factors of electoral success in the 2022 U.S. primary elections, with a focus on campaign finance, candidate demographics, and incumbency status.
We used both causal inference techniques (Inverse Propensity Weighting) and predictive modeling (GLMs and nonparametric methods) to address our research questions.

## Repository Contents
All work for this project is contained in the Jupyter Notebook:

**Final Notebook (1).ipynb**

This notebook includes the following sections:

- Data Cleaning & Preprocessing
  - Merging and cleaning datasets from FiveThirtyEight and the FEC.
  - Standardizing candidate names, simplifying race categories, and removing incomplete records.
- Exploratory Data Analysis (EDA)
  - Visualizations and descriptive statistics exploring campaign finance patterns, demographic disparities, and electoral outcomes.
- Causal Inference (IPW Analysis)
  - Estimation of the Average Treatment Effect (ATE) of high vs. low campaign receipts on vote share using Inverse Propensity Weighting.
  - Discussion of assumptions, limitations, and findings.
- Predictive Modeling (GLMs & Nonparametric Methods)
  - Implementation of Logistic Regression, LASSO, Decision Tree, Random Forest, and k-Nearest Neighbors.
  - Model evaluation using accuracy, precision, recall, and AUC-ROC.
  - Feature importance comparison across models.

## Notes:
- All data used are publicly available from FiveThirtyEight and the FEC (details provided in the notebook).
- The notebook is designed to be run sequentially from data preparation to final modeling and analysis.
