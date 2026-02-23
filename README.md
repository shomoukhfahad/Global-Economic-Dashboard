# Global-Economic-Dashboard
Interactive dashboard exploring global economic performance across countries using key financial indicators such as GDP, inflation, and unemployment.

# Global Economic Dashboard

Interactive dashboard exploring global economic performance across countries using key financial indicators such as GDP, inflation, and unemployment.

---

## Project Overview

This project presents an interactive financial dashboard that analyzes global economic indicators using publicly available data from the World Bank. The dashboard provides a clear overview of the global economy and allows users to explore economic trends across countries.

The main objective is to help stakeholders quickly understand:

- The overall state of the global economy  
- Differences between countries  
- Economic performance over time  
- Key indicators such as GDP, inflation, unemployment, and GDP per capita  

The dashboard is designed for non-technical decision-makers and focuses on clarity, usability, and meaningful insights.

---

## Data Source

The dataset was obtained from publicly available World Bank economic data (via Kaggle):

https://www.kaggle.com/datasets/tanishksharma9905/global-economic-indicators-20102025

It includes annual economic indicators for multiple countries between 2010 and the latest available year.

### Key indicators used in this analysis:

- GDP (Current USD)  
- GDP per Capita (Current USD)  
- Inflation (CPI %)  
- Unemployment Rate (%)  
- Other macroeconomic indicators  

Missing values in recent years were excluded from analysis to ensure accuracy.

---

## Methodology & Data Preparation

The following steps were performed:

- Imported and cleaned the dataset  
- Removed incomplete years with missing values  
- Built calculated measures for latest available year indicators  
- Designed an interactive dashboard using Power BI  
- Applied filters and aggregations to present global and country-level insights  

---

## Dashboard Features

### Page 1 — Global Economic Overview

Provides a high-level snapshot of the global economy, including:

- Total Global GDP (latest available year)  
- Global GDP per Capita  
- Global Inflation Rate  
- Global Unemployment Rate  
- Geographic distribution of indicators by country  
- Top 10 countries by GDP per capita  

<img width="930" height="585" alt="image" src="https://github.com/user-attachments/assets/f2b46560-f29d-46db-b3e2-b5579ae3f9d8" />


### Page 2 — Country Economic Trends

Allows users to analyze economic performance for a selected country:

- Country selector for interactive filtering  
- Trend analysis of GDP per capita over time  
- Comparative insights into economic development  
<img width="933" height="583" alt="image" src="https://github.com/user-attachments/assets/216872d5-cb62-4033-b292-1c56da49a8f0" />


## Key Insights

The dashboard highlights several important observations:

- Significant disparities exist between countries in GDP per capita  
- Economic indicators vary widely across regions  
- Some countries show strong growth trends while others stagnate  
- Inflation and unemployment patterns differ significantly worldwide  

These insights can support strategic planning, investment decisions, and policy analysis.

---

## Live Dashboard Link

https://app.powerbi.com/groups/me/reports/4f43fe87-ccf2-4eec-a8ae-6a42ffad7437?pbi_source=desktop

---

## Assumptions & Limitations

- Data availability varies by country and year  
- Some recent years contain missing values  
- Aggregated global figures may not reflect real-time economic conditions  
- Indicators are reported annually (not monthly or quarterly)
