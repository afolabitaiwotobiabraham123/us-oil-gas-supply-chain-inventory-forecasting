# MySQL Database and Supply Chain Analysis

This folder contains SQL scripts for database creation, petroleum inventory analysis, supply chain KPI calculations and business analysis.

## SQL Scripts

| Script | Purpose |
|---|---|
| 01_database_setup.sql | Create the project database and tables for storing processed EIA datasets. |
| 02_supply_chain_analysis.sql | Analyse petroleum supply, demand, imports and exports. |
| 03_inventory_kpi_analysis.sql | Calculate and analyse petroleum inventory performance indicators. |
| 04_business_analysis.sql | Investigate inventory trends, supply-demand imbalances and business insights. |

## Key Analysis Areas

- Petroleum inventory levels.
- Supply and demand comparisons.
- Import and export movements.
- Inventory changes over time.
- Petroleum availability.
- Supply-demand imbalances.

## Tools

- MySQL
- SQL

## Workflow

1. Create the project database.
2. Import processed datasets from `data/processed/`.
3. Perform SQL-based analysis.
4. Calculate relevant inventory and supply chain KPIs.
5. Generate analytical results for reporting and Power BI.

**Note:** Python handles data acquisition, exploration and preparation. MySQL handles structured storage and SQL-based analysis.
