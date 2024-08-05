# International Debt Data Analysis

This project explores the international debt data collected by The World Bank. The dataset contains information on the amount of debt (in USD) owed by developing countries across various categories. The analysis aims to uncover insights about global debt distribution, identify countries with the highest debt, and understand the types of debt indicators prevalent among these countries.

## Table of Contents

1. [Introduction](#introduction)
2. [Dataset](#dataset)
3. [Analysis](#analysis)
   - [Data Overview](#data-overview)
   - [Distinct Countries Count](#distinct-countries-count)
   - [Debt Indicators](#debt-indicators)
   - [Total Debt Calculation](#total-debt-calculation)
   - [Country with Maximum Debt](#country-with-maximum-debt)
   - [Average Debt Across Indicators](#average-debt-across-indicators)
   - [Principal Repayments](#principal-repayments)
   - [Most Common Debt Indicator](#most-common-debt-indicator)
   - [Maximum Debt by Country](#maximum-debt-by-country)
4. [Conclusion](#conclusion)


## Introduction

Countries may take on debt for various reasons, such as managing their economies or funding infrastructure projects. This analysis delves into international debt data, examining the financial obligations of developing countries to better understand the global economic landscape.

## Dataset

The dataset used in this project includes details such as country names, debt indicators, and the amount of debt. It provides a comprehensive view of the international debt scenario, with data sourced from The World Bank.

## Analysis

### Data Overview

We begin by selecting and displaying the first ten rows of the dataset to understand its structure and contents. The data includes columns like `country_name`, `country_code`, `indicator_name`, `indicator_code`, and `debt`.

### Distinct Countries Count

To perform a holistic statistical analysis, we first determine the number of unique countries present in the dataset. This is essential as a country may have debt in multiple indicators.

### Debt Indicators

We explore the different debt indicators (`indicator_code`) to understand the various categories in which countries can be indebted.

### Total Debt Calculation

We calculate the total amount of debt (in USD) owed by all countries combined to provide a global perspective on economic indebtedness.

### Country with Maximum Debt

We identify the country with the highest total debt and examine the amount of debt it holds.

### Average Debt Across Indicators

We calculate the average amount of debt owed by countries for different debt indicators to understand the distribution and severity of debt types.

### Principal Repayments

We focus on long-term debts (indicator `DT.AMT.DLXF.CD`) and identify the country with the highest amount of debt in this category.

### Most Common Debt Indicator

We determine the most common debt indicators across all countries to identify widespread economic issues.

### Maximum Debt by Country

We find the maximum amount of debt for each country and list the top ten countries with the highest debt amounts.

## Conclusion

This analysis provides valuable insights into the international debt landscape. It highlights countries with significant debt, common debt categories, and the average debt across different indicators. The findings can be used to better understand global economic conditions and guide policy decisions.

## How to Run

1. Clone the repository:
git clone https://github.com/yourusername/international-debt-analysis.git
2. Navigate to the project directory:
3. Ensure you have PostgreSQL installed and set up with the `international_debt` database.
4. Run the Jupyter Notebook to execute the analysis:
