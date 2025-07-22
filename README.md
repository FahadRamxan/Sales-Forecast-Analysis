# Sales Forecast Analysis

## Overview

Sales Forecast Analysis is a Power BI project focused on analyzing historical sales data and forecasting future sales. The project demonstrates data cleaning, table creation, data modeling, and dashboard visualization using Power BI.

## Folder Structure

```
Sales-Forecast-Analysis/
│
├── Actuals.csv                     # Main sales data (raw and cleaned in Power BI)
├── Sales Forecast Results.png       # Example visualization of forecast results
├── README.md                       # Project documentation
```

## Data Preparation Steps

1. **Data Cleaning**
   - Imported `Actuals.csv` into Power BI.
   - Cleaned the `Amount` column (removed `$` and spaces, converted to numeric).
   - Checked for missing or inconsistent values.

2. **Table Creation**
   - Created additional tables (e.g., Date table, Product table) within Power BI using DAX or Power Query.
   - Linked tables using relationships (e.g., Product, Month Number).

3. **Data Modeling**
   - Established relationships between tables for accurate analysis.
   - Used calculated columns and measures for advanced insights.

4. **Dashboard & Visualization**
   - Built interactive dashboards in Power BI.
   - Visualized sales trends, forecasts, and product performance.
   - Used slicers and filters for dynamic exploration.

## Visualization

<!-- Add your image below -->
![Sales Forecast Results](Sales%20Forecast%20Results.png)

## Requirements

- Power BI Desktop (latest version)

## Usage

1. Open Power BI Desktop.
2. Import `Actuals.csv` and `Forecast.csv`.
3. Follow the steps above to clean, model, and visualize your data.
4. Explore the dashboard for insights and forecasts.

## License

This project is licensed under the MIT License.
