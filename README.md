# Renewable vs Fossil Energy Analysis

## **Overview**
This project analyzes the evolution of renewable and fossil energy production and consumption over time, using visualizations and predictive modeling techniques. The goal is to understand the trends, correlations, and future projections for energy transition.

## **EDA and Visualization**
- Created a line chart showing energy consumption over time.
- Plotted standardized values of fossil and renewable energy on the same graph.
- Visualized the percentage of renewables (Renewable + Nuclear) over total energy production over the years.
- Computed the Pearson correlation coefficient between fossil and renewable energy.
- Found a strong positive correlation (0.85), indicating simultaneous growth.
- Compared energy consumption vs production to analyze trends.

## **KMeans clusterization**
- I clustered the years based on the year-over-year changes in renewable energy production, identifying periods with similar growth patterns.

## **Time Series Forecasting with Prophet**
- Used META Prophet to forecast renewable energy trends.
  - Trained a model on historical data and predicted future energy production.
  - Cross validation: MAPE under 10%, low RMSE and MAE. 

## **Technologies Used**
- **Python**, **Pandas**, **Matplotlib**, **Prophet**

## **Key Insights**
- As a counterintuitive resul, there is a positive correlation between fossil and renewable energy production because the enery demand is globally growing.
- However, renewable energy consuption is growing more than fossils fuel one.
- The Green energy (Renewable + Nuclear) has grown from 7 in 1973 to 20-22% of the production in 2022.

## **Conclusions**
This project provides a data-driven perspective on the global energy transition, helping to understand future sustainability challenges.
