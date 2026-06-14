# Methodology

## Data Collection
Data was collected from Kaggle (food price dataset) and the World Bank API (exchange rates).

## Data Extraction
The World Bank API was accessed using Power Query (M language). Pagination was implemented to retrieve data for the period 2010–2017. The indicator used was PA.NUS.FCRF.

## Data Transformation (ETL)
- Removal of null values
- Standardization of currency to USD
- Alignment of monthly food prices with yearly exchange rates
- Creation of unique keys for data integrity

## Data Modeling
A star schema was implemented consisting of:
- 1 fact table (Market_Prices)
- 9 dimension tables

## Analysis
- DAX measures were used for KPI development
- Time intelligence functions were applied for YoY calculations
- Volatility was measured using standard deviation
