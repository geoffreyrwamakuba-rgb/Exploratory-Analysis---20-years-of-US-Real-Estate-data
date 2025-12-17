# Connecticut Real Estate Sales EDA (1999–2024)
Exploratory Data Analysis of 1.1M+ real estate transactions in Connecticut.
Completed in Python (Pandas, NumPy, Matplotlib, Seaborn) to uncover long-term trends in pricing, property types and towns.

### Key Questions, Charts & Analysis

### 1. How have sales price trends changed over the 2001–2023 period overall, by Property Type and Town?
#### 1.1. Overall Trend.
![alt text](https://github.com/geoffreyrwamakuba-rgb/Exploratory-Analysis---20-years-of-US-Real-Estate-data/blob/main/1.1%20Connecticut_property_sales_over_time.png?raw=true)

#### 1.2 By Property Type
![alt text](https://github.com/geoffreyrwamakuba-rgb/Exploratory-Analysis---20-years-of-US-Real-Estate-data/blob/main/1.2%20Sales_trends_by_property_type.png?raw=true)

#### 1.3 By Town
![alt text](https://github.com/geoffreyrwamakuba-rgb/Exploratory-Analysis---20-years-of-US-Real-Estate-data/blob/main/1.3%20Sales_over_time_for_top_10_towns.png?raw=true)


### 2.1 How does sale price vary with assessed value?
### 2.2 Does property type influence the % Profit on Sale?
### 3.  Which towns or regions have the highest sale price over the years?
### 4.1 How do median household income, education levels, or poverty rates correlate with prices and sales activity?
### 5. How did COVID-19 pandemic years affect sale prices and volumes in Connecticut?


### Data Cleaning & Preparation
- Removed rows with missing or invalid sale dates, prices, or assessed values
- Standardised town names, dates, and data types
- Removed duplicates
- Replaced inconsistent Sales Ratio with a calculated % Profit on Sale
- Consolidated Residential records using detailed residential sub-types

### Tools & Technologies
- **Python:** pandas, numpy
- **Visualization:** matplotlib, seaborn
- **Data Sources:**
  - Connecticut Real Estate Sales (2001–2023) - [Data.gov](https://catalog.data.gov/dataset/real-estate-sales-2001-2018)
  - CPI data from the [Federal Reserve (FRED)](https://fred.stlouisfed.org/series/CPIAUCSL)
