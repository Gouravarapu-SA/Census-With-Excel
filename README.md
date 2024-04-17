# Indian Census Data Analysis

This SQL code analyzes census data from two tables, 'data1' and 'data2', in the 'project' database. The analysis includes data preparation, aggregation, analysis, data joining, advanced analysis, and a summary of key indicators at the state level.

## Data Preparation

- Initial queries fetch all data from the two tables and count the number of rows.
- Filters data for the states 'Jharkhand' and 'Bihar'.

## Overview Aggregation

- Calculates the total population of India by summing the 'population' column.
- Calculates the average growth rate, sex ratio, and literacy rate by state after grouping.

## Analysis

- Finds the top 3 and bottom 3 states by average growth, sex ratio, and literacy rate after ordering the results.
- Filters states starting with the letters 'A' and 'A' followed by 'm'.

## Data Joining

- Joins the two tables on the 'district' column to calculate the total males and females by state.
- Performs a similar join to calculate the total literate and illiterate population by state.

## Advanced Analysis

- Calculates the population in the previous census by subtracting the growth from the current population.
- Finds the ratio of total land area to the previous and current census populations.

## Summary

In summary, the SQL code performs a comprehensive analysis of Indian census data through techniques like aggregation, filtering, joining, and window functions to derive key indicators at the state level. This analysis provides valuable insights about various census parameters for each state, such as population, growth rate, sex ratio, literacy rate, and land area ratios.
