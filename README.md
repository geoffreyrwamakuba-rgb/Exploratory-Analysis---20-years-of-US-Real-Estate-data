# Connecticut Real Estate Sales EDA (1999–2024)

Exploratory Data Analysis of 1.1M+ real estate transactions in Connecticut
This project analyses residential and commercial property sales to uncover long-term trends in pricing, property types, and inflation-adjusted returns.

### Key Questions

1. How have real estate sale prices changed over time (nominal vs inflation-adjusted)?
2. Which property types dominate the Connecticut housing market?
3. How do assessed values compare to sale prices across time?
4. What does profit (sale price vs assessed value) look like by property type?
5. Are there notable differences across towns and years?

### Data Cleaning & Preparation
- Removed rows with missing or invalid sale dates, prices, or assessed values
- Standardised town names, dates, and data types
- Removed duplicates using a composite key (Serial Number + Town + Address)
- Replaced inconsistent Sales Ratio with a calculated % Profit on Sale
- Consolidated Residential records using detailed residential sub-types
- Adjusted historical prices using CPI data to allow real (inflation-adjusted) comparisons

### Key Charts & Analysis

### Tools & Technologies
- **Python:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Data Sources:**
  - Connecticut Real Estate Sales (2001–2023) - [Data.gov](https://catalog.data.gov/dataset/real-estate-sales-2001-2018)
  - CPI data from the [Federal Reserve (FRED)](https://fred.stlouisfed.org/series/CPIAUCSL)
