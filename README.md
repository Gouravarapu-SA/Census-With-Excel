# Census-With-Excel
overview of Indian census data analysis, including data preparation, aggregation, analysis, data joining, advanced analysis, and a summary of key indicators at the state level.
Indian Census Data Analysis
The SQL code is analyzing census data from two tables 'data1' and 'data2' in the 'project' database.
Data Preparation
• Initial queries fetch all data from the two tables and count number of rows.
• Filters data for states 'Jharkhand' and 'Bihar'.
Overview
Aggregation
• Calculates total population of India by summing 'population' column.
• Calculates average growth rate, sex ratio, literacy rate by state after grouping.
Analysis
• Finds top 3 and bottom 3 states by average growth, sex ratio, literacy rate after ordering
results.
• Filters states starting with letters 'A' and 'A' followed by 'm'.
Data Joining
• Joins two tables on 'district' column to calculate total males, females by state.
• Similar join to calculate total literate and illiterate population by state.
Advanced Analysis
• Calculates population in previous census by subtracting growth from current pop.
• Finds ratio of total land area to previous and current census populations.
Summary
In summary, the SQL code performs comprehensive analysis of Indian census data through techniques like aggregation, filtering, joining, window functions to derive key indicators at state level. This provides valuable insights about various census parameters for each state.
