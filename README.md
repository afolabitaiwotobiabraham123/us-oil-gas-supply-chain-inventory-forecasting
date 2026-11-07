# US Oil & Gas Supply Chain and Petroleum Inventory Forecasting Analytics

## 1. Project Overview

This project focuses on analysing petroleum supply chain performance and forecasting petroleum inventory levels in the United States using publicly available data from the **U.S. Energy Information Administration (EIA)**.

The project examines historical petroleum inventory levels, supply, demand, imports, exports and consumption patterns to understand inventory movements, identify supply-demand imbalances and support better inventory planning and operational decision-making.

The analysis will use real US petroleum industry data to demonstrate how data analytics can support supply chain visibility, inventory monitoring, demand analysis and forecasting in the oil and gas industry.

**Data integrity:** This project uses publicly available US petroleum industry statistics. It does not claim access to confidential inventory or operational records from individual oil and gas companies.

## 2. Project Objectives

- Analyse historical US petroleum inventory levels.
- Monitor petroleum supply and demand patterns.
- Examine the relationship between petroleum imports, exports and inventory changes.
- Identify inventory fluctuations and potential supply-demand imbalances.
- Analyse petroleum consumption trends.
- Forecast future petroleum inventory levels.
- Develop interactive dashboards for inventory and supply chain performance monitoring.
- Generate business insights to support inventory planning and operational decisions.

## 3. Business Problems

The petroleum supply chain is affected by changing demand, production levels, imports, exports and inventory movements.

This project addresses the following business questions:

1. How have US petroleum inventory levels changed over time?
2. What patterns exist in petroleum supply and demand?
3. How do imports and exports influence domestic petroleum availability?
4. Which petroleum products experience significant inventory fluctuations?
5. Are there periods of unusually high or low inventory?
6. Can historical inventory patterns help forecast future stock levels?
7. What insights can support better petroleum supply chain planning?

## 4. Data Sources

The primary data source is the **U.S. Energy Information Administration (EIA)**.

Official data portal:

https://www.eia.gov/petroleum/data.php

The project will use relevant publicly available datasets, including:

| Dataset | Purpose |
|---|---|
| Petroleum Stocks / Inventory | Analyse historical petroleum inventory levels |
| Petroleum Supply | Examine petroleum supply patterns |
| Petroleum Demand / Product Supplied | Analyse consumption and demand |
| Petroleum Imports | Monitor incoming petroleum volumes |
| Petroleum Exports | Analyse outgoing petroleum volumes |
| Petroleum Production | Examine domestic petroleum production |

Only datasets that are accessible and relevant to the project will be included.

## 5. Scope of Analysis

### 5.1 Petroleum Inventory Analysis
- Historical inventory trends.
- Inventory fluctuations.
- Stock level comparisons.
- High and low inventory periods.

### 5.2 Supply Chain Analysis
- Petroleum supply patterns.
- Imports and exports.
- Domestic production.
- Supply-demand relationships.

### 5.3 Demand Analysis
- Petroleum consumption trends.
- Demand fluctuations.
- Product-level demand comparisons.
- Historical demand patterns.

### 5.4 Inventory Forecasting
- Historical inventory trend analysis.
- Time-series forecasting.
- Future inventory level predictions.
- Forecast performance evaluation.

### 5.5 Operations Analytics
- Petroleum availability monitoring.
- Supply-demand imbalance analysis.
- Inventory movement monitoring.
- Operational performance insights.

## 6. Tools and Technologies

| Tool | Purpose |
|---|---|
| Python | Data acquisition, exploration and preparation |
| Jupyter Notebook | Interactive data analysis |
| Pandas | Data manipulation and cleaning |
| Matplotlib | Data visualization |
| MySQL | Structured data storage and SQL analysis |
| Power BI | Interactive dashboards |
| Statsmodels | Time-series analysis and forecasting |
| Scikit-learn | Forecast evaluation and supporting machine learning |

## 7. Project Workflow

1. Data Acquisition
2. Exploratory Data Analysis (EDA)
3. Data Quality Assessment
4. Data Cleaning and Preparation
5. MySQL Database Setup
6. SQL-Based Supply Chain Analysis
7. Key Performance Indicator (KPI) Analysis
8. Petroleum Inventory Forecasting
9. Power BI Dashboard Development
10. Business Insights and Recommendations

## 8. Repository Structure

```text
us-oil-gas-supply-chain-inventory-forecasting/
│
├── README.md
│
├── data/
│   ├── raw/
│   └── processed/
│
├── python/
│   ├── 01_data_acquisition.ipynb
│   ├── 02_exploratory_data_analysis.ipynb
│   ├── 03_data_quality_assessment.ipynb
│   └── 04_data_cleaning_preparation.ipynb
│
├── mysql/
│   ├── 01_database_setup.sql
│   ├── 02_supply_chain_analysis.sql
│   ├── 03_inventory_kpi_analysis.sql
│   └── 04_business_analysis.sql
│
├── forecasting/
│   ├── README.md
│   └── 05_petroleum_inventory_forecasting.ipynb
│
├── power_bi/
│   ├── dashboard/
│   └── screenshots/
│
├── reports/
│   └── README.md
│
├── docs/
│   └── README.md
│
├── requirements.txt
│
└── .gitignore
```

## 9. Expected Deliverables

- Downloaded and documented EIA petroleum datasets.
- Python notebooks for data acquisition and preparation.
- Exploratory data analysis and data quality findings.
- MySQL database and analytical SQL queries.
- Petroleum inventory forecasting model.
- Power BI supply chain and inventory dashboard.
- Business insights and recommendations.

## 10. Expected Business Value

This project demonstrates how data analytics can help petroleum supply chain and operations teams:

- Improve visibility into petroleum inventory movements.
- Understand supply and demand fluctuations.
- Monitor petroleum availability.
- Identify potential supply-demand imbalances.
- Support inventory planning through forecasting.
- Make more informed operational and supply chain decisions.

## 11. Disclaimer

This is an independent portfolio project using publicly available US petroleum industry data from the U.S. Energy Information Administration. It is not affiliated with or officially endorsed by the EIA or any US oil and gas company.

All findings and forecasts are based on the datasets and analytical methods used in this project.
