# An Economic Analysis of Global Football Transfers

## Project Summary

This project focuses on the analysis of European football transfers using Excel. The objective is to gain insights into transfer patterns, financial aspects, and the performance of European countries in the global football transfer market.

## Business Problem & Key Questions

The primary business problem addressed in this project is the need for understanding and visualizing the dynamics of football transfers in Europe. Key questions include:

1. How can we efficiently organize and review the football transfer database?
2. What is the aggregate number of European transfers, and how does it vary across seasons and continents?
3. How can we analyze European transfers by country, considering both quantity and financial worth?
4. Which European countries are the top spenders in terms of incoming transfer values?

## Approach

### Database Review

1. **Data Splitting:** Utilized Excel’s Text-to-Columns tool to split data in the "Countries" sheet.
2. **Continent Name Cleanup:** Removed extra spaces in continent names and ensured uniformity.
3. **Database Sheet Review:** Applied filters, corrected entries, and filled in the "Continent" column using VLOOKUP or XLOOKUP.

### Analyze the Aggregate Number of European Transfers

1. **Table Creation:** Developed a table to aggregate European transfer data based on season and continent.
2. **SUMIFS Function:** Employed Excel’s SUMIFS function to add data based on multiple criteria, considering both incoming and outgoing transfers.

### Analyze European Transfers by Country

1. **Table Setup:** Structured a table to illustrate the quantity and financial worth of player transfers in and out of Europe.
2. **SUMIFS Function Implementation:** Utilized Excel’s SUMIFS function to populate the table, adjusting parameters for outgoing transfers and financial values.

### Visualize Transfer Fees of Top 5 European Countries

1. **Identifying Top 5 Countries:** Used the RANK function to identify the five countries with the most significant incoming transfer values.
2. **Visualization Creation:** Developed a table and visualization using Excel formulas and charts to showcase the transfer fees of the top 5 European countries.

## Data Cleaning

- Split data in the "Countries" sheet using Text-to-Columns.
- Cleaned up continent names by removing extra spaces.
- Reviewed and corrected entries in the "Database" sheet, addressing inconsistencies and errors.

## Data Preparation

- Filled in the "Continent" column in the "Database" sheet using VLOOKUP or XLOOKUP.
- Created tables for aggregate transfer analysis and European transfers by country.
- Implemented SUMIFS functions to populate tables based on specific criteria.

## Results

The analysis provided insights into:

- Aggregate number of European transfers by season and continent.
- Quantity and financial worth of player transfers in and out of European countries.
- Identification of the top 5 European countries with the most significant incoming transfer values.

## Key Takeaways

1. **Database Organization:** Efficiently split and cleaned data for effective database review.
2. **Aggregate Transfer Analysis:** Utilized SUMIFS functions for a detailed analysis of European transfers.
3. **Country-specific Analysis:** Employed SUMIFS functions to analyze transfers by country, considering both quantity and financial values.
4. **Top 5 Countries Visualization:** Developed a visualization to identify and compare the transfer fees of the top 5 European countries.

This project provides valuable insights into the football transfer landscape in Europe, facilitating informed decision-making and strategic planning for football clubs and stakeholders.
