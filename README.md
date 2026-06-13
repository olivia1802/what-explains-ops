# What Best Explains OPS in MLB?

## Project Overview

This project investigates which traditional batting statistics are most strongly associated with OPS (On-Base Plus Slugging) among Major League Baseball players.

Using 2023 MLB batting data, I explored relationships between offensive metrics through correlation analysis, data visualization, and multiple regression.

## Research Question

To what extent do home runs, batting average, walks, and strikeouts explain variations in OPS among MLB players?

## Methods

* Data Cleaning with Pandas
* Correlation Analysis
* Heatmap Visualization
* Multiple Linear Regression
* Statistical Interpretation

## Key Findings

* Batting Average (BA) was the strongest predictor of OPS.
* Home Runs (HR) showed a significant positive relationship with OPS.
* Walks (BB) had a smaller but statistically significant positive effect.
* Strikeouts (SO) were not a significant predictor after controlling for other offensive statistics.

## Dataset

Source: Kaggle – 2023 MLB Player Stats Dataset

Original data collected from Baseball Reference.

## Tools Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Statsmodels
* Jupyter Notebook

## Files

* `what_explains_ops.ipynb`
