# 331 Final Project: Can Money Buy Happiness?

## Overview
This project analyzes the relationship between **poverty rates** and **happiness scores** across countries using **Gapminder** and **WHR** data (2005-2023). We use **linear regression** to explore whether lower poverty correlates with higher happiness.

## Methodology
- **Data Cleaning**: Pivoted long format, removed NA values, joined datasets by country & year.
- **Regression Model**: Assessed the relationship between poverty and happiness using linear regression, evaluating model fit with R^2, coefficient analysis, and variance decomposition.
- **Simulation**: Generated predictions, added noise, ran **1000 simulations**, and analyzed R^2 distribution.

## Key Findings
- **Moderate inverse relationship**: Higher poverty correlates with lower happiness.
- **Model explains ~55% of variance**; other factors (e.g., GDP, policies) likely impact happiness.

## Running the Code
1. Install **R packages**: `tidyverse`, `ggplot2`, `gridExtra`, `DT`.
2. Ensure data files are in the `/data` folder.
3. Run the Quarto `.qmd` file to generate insights.

## Authors
**Justin Koida, Abigayle Mercer, Sammy Paykel**
