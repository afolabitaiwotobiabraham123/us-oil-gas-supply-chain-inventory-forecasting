# PROJECT DOCUMENTATION

# Canadian Natural Resources
## Materials, Inventory & Demand Forecasting Analytics

**Project Domain:** Oil & Gas | Supply Chain Analytics | Inventory Management | Forecasting

**Project Type:** Independent Data Analytics Portfolio Project

**Analytical Focus:** Materials Management, Inventory Optimization, Demand Forecasting and Supply Chain Performance

---

## 1. Executive Summary

This project focuses on applying data analytics, inventory management techniques, and forecasting methods to materials and inventory planning within the oil and gas industry.

Oil and gas operations depend on the availability of critical materials, maintenance supplies, spare parts, and operational inventory. Poor inventory planning can result in material shortages, excess stock, increased holding costs, emergency procurement, and disruptions to maintenance and operational activities.

The project aims to demonstrate how Python, MySQL, statistical forecasting, and Power BI can support better inventory decisions, improve material availability, and strengthen supply chain planning.

This is an independent portfolio project inspired by materials and inventory management challenges in the oil and gas industry. It does not use confidential or proprietary Canadian Natural Resources data.

## 2. Background and Business Problem

Materials management is an important part of oil and gas supply chain operations.

Operational facilities require different categories of materials to maintain equipment, perform maintenance activities, and support continuous production.

However, organizations may encounter several inventory management challenges:

- Material shortages that delay maintenance and operational activities.
- Excess inventory that increases inventory holding costs.
- Unnecessary emergency purchases.
- Inaccurate material demand planning.
- Poor visibility into material consumption patterns.
- Inefficient inventory replenishment decisions.
- Supplier delivery delays affecting material availability.

Without reliable inventory information and demand forecasts, organizations may struggle to determine what materials to purchase, when to replenish stock, and how much inventory to maintain.

This project explores how data analytics and forecasting can help address these challenges.

## 3. Project Aim

To develop an integrated materials and inventory analytics solution that uses historical data, inventory performance indicators, and forecasting techniques to support material planning, inventory optimization, and supply chain decision-making in the oil and gas industry.

## 4. Project Objectives

The specific objectives are to:

1. Analyze historical material consumption patterns.
2. Evaluate inventory levels and stock movements.
3. Identify stockout risks and excess inventory.
4. Analyze material demand trends and variability.
5. Calculate relevant inventory management KPIs.
6. Forecast future material demand.
7. Support reorder point and safety stock decisions.
8. Evaluate inventory replenishment and supplier performance where data is available.
9. Develop interactive dashboards for inventory monitoring.
10. Provide data-driven recommendations for improving materials and inventory management.

## 5. Analytical Scope

### 5.1 Materials Analytics

This area examines how operational materials are consumed and managed.

Key activities include:

- Material consumption analysis.
- Material usage pattern identification.
- High-demand and low-demand material analysis.
- Critical material identification.
- Material movement analysis.
- Identification of unusual consumption patterns.

### 5.2 Inventory Analytics

This area evaluates inventory availability, stock movements, and inventory performance.

Key activities include:

- Inventory level monitoring.
- Stock availability analysis.
- Stockout identification.
- Excess and slow-moving inventory analysis.
- Inventory turnover analysis.
- Days of inventory on hand.
- Reorder point calculations.
- Safety stock calculations.
- Inventory replenishment analysis.

### 5.3 Demand Forecasting

This area uses historical material consumption data to estimate future demand.

Key activities include:

- Historical material demand analysis.
- Material demand forecasting.
- Forecasting high-consumption materials.
- Forecast accuracy evaluation.
- Actual demand versus forecast comparison.
- Forecast-based inventory planning.

### 5.4 Supplier and Replenishment Performance

This area examines how supplier performance affects material availability and inventory planning.

Key activities include:

- Supplier lead-time analysis.
- Supplier delivery performance.
- On-time delivery analysis.
- Material replenishment performance.
- Procurement and inventory relationship analysis.
- Identification of potential supply chain risks.

These analyses will depend on the availability of suitable supplier and procurement records.

## 6. Data Requirements and Sources

The project will use publicly accessible datasets or clearly identified simulated datasets representing oilfield materials, inventory transactions, procurement, and supplier performance.

### 6.1 Potential Data Requirements

| Dataset | Description |
|---|---|
| Material Master | Material IDs, descriptions, categories and units of measurement |
| Inventory Records | Opening balances, closing balances and stock levels |
| Inventory Transactions | Material receipts, issues and adjustments |
| Material Consumption | Historical quantities consumed by material |
| Purchase Orders | Procurement quantities, order dates and purchase values |
| Supplier Records | Supplier identification and relevant attributes |
| Delivery Records | Expected and actual delivery dates |
| Lead-Time Records | Time taken to replenish materials |

### 6.2 Data Source Considerations

All datasets will be assessed for relevance, availability, completeness, and suitability for the intended analysis.

Where actual company-level data is unavailable, simulated datasets may be used to demonstrate the analytical methods.

Data sources, assumptions, and limitations will be documented.

No confidential or proprietary Canadian Natural Resources data is assumed.

## 7. Tools and Technologies

| Technology | Application |
|---|---|
| Python | Data acquisition, exploration, assessment and preparation |
| Jupyter Notebook | Documenting analytical workflows |
| Pandas | Data manipulation and analysis |
| Matplotlib | Data visualization |
| MySQL | Structured data storage and SQL analysis |
| Scikit-learn | Forecasting and predictive modelling where appropriate |
| Statsmodels | Statistical and time-series forecasting |
| Power BI | Interactive dashboards and business reporting |

## 8. Key Performance Indicators

The project will calculate and evaluate relevant KPIs across four analytical areas.

### 8.1 Inventory KPIs

- Inventory Turnover Ratio.
- Days Inventory Outstanding (DIO).
- Stockout Rate.
- Inventory Accuracy.
- Average Inventory Value.
- Excess Inventory.
- Reorder Point.
- Safety Stock.

### 8.2 Materials KPIs

- Material Consumption Rate.
- Material Demand Variability.
- High-Consumption Material Identification.
- Slow-Moving Material Rate.

### 8.3 Supplier and Replenishment KPIs

- Supplier Lead Time.
- On-Time Delivery Rate.
- Supplier Delivery Performance.
- Replenishment Cycle Time.

### 8.4 Forecasting KPIs

- Mean Absolute Error (MAE).
- Mean Absolute Percentage Error (MAPE), where appropriate.
- Root Mean Squared Error (RMSE).
- Forecast Bias.

All KPI definitions, formulas, assumptions, and data requirements will be documented before calculation.

## 9. Project Methodology and Workflow

The project will follow a structured analytical workflow.

**Phase 1: Data Acquisition**

Collect relevant public or simulated materials, inventory, procurement, and supplier datasets.

**Phase 2: Exploratory Data Analysis**

Explore dataset structures, distributions, material consumption patterns, and inventory trends.

**Phase 3: Data Quality Assessment**

Assess missing values, duplicate records, inconsistencies, invalid entries, and data reliability.

**Phase 4: Data Cleaning and Preparation**

Clean, standardize, transform, and prepare datasets for analysis.

**Phase 5: MySQL Database Development**

Create database structures, load prepared datasets, and establish relationships between relevant tables.

**Phase 6: SQL-Based Analysis**

Perform materials analysis, inventory analysis, supplier analysis, and KPI calculations.

**Phase 7: Inventory Analytics**

Evaluate inventory performance, identify stockout risks, analyze excess stock, and calculate replenishment indicators.

**Phase 8: Demand Forecasting**

Develop suitable forecasting models using historical material demand data.

**Phase 9: Forecast Evaluation**

Evaluate forecasting performance and compare predicted demand against actual observations.

**Phase 10: Power BI Dashboard Development**

Develop interactive dashboards to communicate inventory performance, material consumption, supplier performance, and forecasting results.

**Phase 11: Business Insights and Recommendations**

Interpret analytical results and develop recommendations supported by the available evidence.

## 10. Expected Project Deliverables

The completed project is expected to contain:

1. Raw and processed datasets.
2. Python and Jupyter Notebook workflows.
3. Data quality assessment documentation.
4. MySQL database and SQL analysis scripts.
5. Materials consumption analysis.
6. Inventory performance analysis.
7. Inventory KPI calculations.
8. Material demand forecasting models.
9. Forecast evaluation results.
10. Power BI inventory analytics dashboard.
11. Analytical reports and business recommendations.
12. Project documentation and data dictionary.

## 11. Expected Business Value

The project demonstrates how data analytics and forecasting can support oil and gas materials management through:

- Improved inventory visibility.
- Reduced risk of material shortages.
- Identification of excess and slow-moving inventory.
- Better material replenishment decisions.
- Improved material demand planning.
- More informed inventory allocation.
- Better supplier and delivery performance monitoring.
- Support for maintenance and operational continuity.
- Data-driven inventory management decisions.

The actual business impact will depend on the quality of the data, analytical findings, and practical implementation of recommendations.

## 12. Project Limitations and Assumptions

- Publicly available datasets may not fully represent the complexity of an actual oil and gas company's inventory operations.
- Simulated datasets, where used, will be clearly identified.
- Forecasting accuracy will depend on historical data quality, quantity, and demand patterns.
- Supplier performance analysis requires suitable procurement and delivery records.
- Inventory optimization recommendations will depend on the availability of cost, lead-time, demand, and stock information.
- No actual Canadian Natural Resources operational performance or financial results will be claimed.

## 13. Project Disclaimer

This is an independent educational and professional portfolio project inspired by materials and inventory management challenges in the oil and gas industry.

It is not an official Canadian Natural Resources project and does not represent the company's internal systems, confidential datasets, actual operational performance, or business decisions.
