# Global Food Price Analysis Dashboard (2010–2017)

## Overview

This project analyzes global food price trends from 2010 to 2017 across 55 countries, using over 740,000 records sourced from Kaggle and the World Bank.

All food prices were standardized into US Dollars (USD) using exchange rate data to ensure fair global comparisons.

The solution was developed using Excel and Power BI, applying a star schema data model with 1 fact table and 9 dimension tables to support scalable analytics and interactive dashboards.

---

## Objectives

- Analyze global food price trends across countries and commodities
- Compare commodity prices over time
- Measure price volatility and market stability
- Assess the impact of exchange rates on food prices
- Identify inflation-like price movements through trend analysis
- Build interactive dashboards for decision-making

---

## Tools and Technologies

- Power BI
- Microsoft Excel
- Power Query (M Language)
- DAX (Data Analysis Expressions)
- Kaggle Dataset
- World Bank API

---

## Dataset Overview

- Time Period: 2010–2017
- Countries: 55+ countries
- Records: 740,000+ rows
- Focus: Food commodities only
- Currency: Standardized to USD

---

## Data Model

### Fact Table
Market_Prices

### Dimension Tables (9)

- Calendar Dimension
- Commodity Dimension
- Country Dimension
- Market Dimension
- Exchange Rate Dimension
- Market Type Dimension
- Unit Dimension
- Currency Dimension
- Locality Dimension

This structure improves:
- Data consistency
- Query performance
- DAX calculation accuracy
- Scalability of the model

---

## Data Processing (ETL)

- Extracted exchange rate data from World Bank API using Power Query
- Handled pagination for complete dataset retrieval
- Cleaned missing and inconsistent values
- Converted all prices to USD for consistency
- Aligned monthly food prices with yearly exchange rates
- Created calculated fields for analytical metrics

---

## Dashboards

### Market Overview Dashboard
- Global price comparisons across countries
- Regional and continental insights
- High-level market trends

### Price Analysis Dashboard
- Time-series price movements
- Year-over-Year (YoY) analysis
- FX impact on food prices
- Inflation-like trends

### Product Analysis Dashboard
- Commodity-level performance
- Price ranking of food items
- Volatility comparison across products
- Cross-country commodity insights

---

## Key Metrics (DAX)

- Average Price (USD)
- Total Price (USD)
- Year-over-Year (YoY) Price Change
- FX YoY Change
- Price Volatility (Standard Deviation)
- Product Frequency
- Total Commodities
- Total Countries
- Total Markets
- Total Currencies

---

## Stakeholders

- Government Ministry (Agriculture / Trade / Finance)
Uses food price data to support policy decisions, regulate markets, and ensure food security.

- International Organizations (FAO / WFP / World Bank)
Use the data for global food security monitoring, humanitarian planning, and economic reporting.

- Market Analysts
Analyze price trends, inflation patterns, and commodity performance for investment and research purposes.

- Supply Chain Firms
Use insights to optimize sourcing, pricing strategies, logistics planning, and risk management.

---

## Key Insights

- Food prices vary significantly across countries and time periods
- Exchange rates have a strong impact on local food pricing
- Certain commodities show high volatility and instability
- Clear regional differences exist in pricing patterns
- Price acceleration reveals inflation-like behavior in some markets

---

## Challenges

- Aligning monthly food price data with yearly exchange rates
- Complex relationships between fact and 9 dimension tables
- DAX calculation issues due to filter context complexity
- Currency inconsistencies across countries before standardization
- Difficulty combining FX and price trends in visuals

---

## Business Value

This analysis supports:
- Policy-making and economic planning
- Global food security monitoring
- Market pricing strategies
- Supply chain optimization
- Inflation and commodity research

---

## Future Improvements

- Extend dataset beyond 2017
- Use monthly FX rates instead of yearly averages
- Add predictive forecasting models
- Improve drill-down analytics in dashboards

---

## Dashboard Preview

(Add images from the images folder here)

---

## Contact

- GitHub: (add your username)
- LinkedIn: (add your profile)

---

## Conclusion

This project demonstrates end-to-end skills in data engineering, data modeling, and business intelligence using Power BI, transforming large-scale global datasets into actionable insights.
