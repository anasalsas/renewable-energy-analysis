# CO2 and Greenhouse Gas Emissions Dashboard

## 1. Project Overview

This Excel dashboard analyzes global CO2 emissions and energy consumption trends by country and region, utilizing data from Kaggle. The dashboard allows users to explore key performance indicators (KPIs) such as CO2 emissions per capita, consumption per capita, and year-on-year (YoY) growth.

### Objectives:

- Analyze CO2 emissions and energy consumption by country and region.
- Compare key metrics such as emissions per capita, energy consumption per capita, and global CO2 share.
- Create a dynamic dashboard for data visualization, enabling interactivity via slicers and dropdowns to facilitate exploration of trends and comparisons.

### Data Source:

- **Source**: Kaggle Dataset "CO2 and Greenhouse Gas Emissions" by Daniel R. Dias. (Link: [CO2 and Greenhouse Gas Emissions Dataset](https://www.kaggle.com/datasets/danielrpdias/co2-and-greenhouse-gas-emissions))
- **Data Format**: CSV
- **Data Information**: 54 columns and 25 203 rows
- **Data Treatment**: Power Query in Excel for data type conversion (from text to numeric (decimal)), and removal of 4 columns with 100% null values.

## 2. Data Cleaning/Transformation (in Power Query)

- **Data Import**: Imported the CSV file into Excel.
- **Data Cleaning**: Removed 4 columns with 100% null values.
  - **Columns Removed**: `share_global_cumulative_other_co2`, `cumulative_other_co2`, `other_co2_per_capita`, `other_industry_co2`.
- **Data Transformations**: Utilized Power Query to:
  - Change data types where necessary (e.g., text to decimal).
  - Perform outlier analysis using Q1, Q3, and IQR calculations (outliers were flagged but not removed in this iteration).
  - Created two main tables for analysis: CO2_Countries and CO2_Regions, which are tables in the data model. They are stored in the model.
  - **CO2_Countries**: For country-level data.
  - **CO2_Regions**: For region-level data.
- Ensured that both tables were added to the data model for integration with slicers and dropdowns.
- Used Excel's **pivot tables** to aggregate data, compute averages, totals, and YOY growth for CO2 emissions and energy consumption.

## 3. Data Modeling (Pivot Tables)
  - Created pivot tables for both country and region-level analysis, and pivot charts for dynamic data visualization.

## 4. KPI Calculations

Key performance indicators (KPIs) calculated from the data include:

- **Average CO₂ Emissions**: By country/region.
- **Average CO₂ Consumption**: By country/region.
- **CO₂ Emissions per Capita**: By country/region.
- **Year-on-Year (YoY) Growth**: For CO₂ emissions.

## 5. Created Graphs:

- **Top 10 Countries with CO₂ Emissions (Bar Chart)**
- **CO₂ Emissions by Source (Coal, Oil, Gas, etc.) (Line Chart)**
- **CO₂ Growth YoY by Region (Line Chart)**
- **Share of Global CO₂ by Region (Pie Chart)**
- **Global CO₂ Emissions & Methane Levels (Line Chart)**
- **CO₂ vs Energy Consumption Efficiency (Bubble Chart)**

## 6. Dashboard Overview:

### CO₂ Emissions by Country
- **Slicers**: Year, Country
- **Charts**:
  - Bar chart: **Top 10 Countries with CO₂ Emissions**
  - Line chart: **CO₂ Emissions by Source (Coal, Oil, Gas)**

- **Charts**:
  - Line chart: **CO₂ Growth YoY by Region**
  - Pie chart: **Share of Global CO₂ by Region**

- **Charts**:
  - Line chart: **Global CO₂ Emissions & Methane Levels**

## 7. Skills Showcased

- **Data Import and Cleaning**: Proficient use of Power Query for data import, transformation, and cleaning (removal of null values, outlier detection).
- **Data Analysis**: Utilized Excel formulas like AVERAGEIFS and IFERROR to compute averages and KPIs.
- **Data Visualization**: Created interactive pivot tables and visualizations (Bar Charts, Line Charts, Pie Charts).
- **Dashboard Creation**: Built a dynamic and user-friendly dashboard using Excel's slicers, dropdowns, and pivot tables for interactive data exploration.
- **Advanced Excel Techniques**: Mastered complex functions for data aggregation and analysis (including YEAR, AVERAGEIFS, etc.).

## 8. Key Learnings:

- **Interactivity**: The use of slicers and dropdowns helped make the dashboard interactive, but the initial setup with multiple slicers could be optimized for better user experience.
- **Data Modeling**: Ensuring that slicers work consistently across different pivot tables and visualizations is essential for effective interactivity.
- **Data Validation**: Emphasized the importance of ensuring data integrity, especially with large datasets and dynamic models.

## 9. Future Improvements:

- **Advanced Data Cleansing**: More robust handling of missing data (imputation) would improve analysis quality.
- **Power BI Integration**: Future dashboards could benefit from more advanced interactivity using Power BI, which would allow for more dynamic filtering and richer visualizations.
- **Enhanced Data Modeling**: Further refinement of data relationships and ensuring all slicers and dropdowns interact seamlessly across different data sources.

## 10. Recommendations for Recruiters and PMO Analysts:

- **Best Practices**: Demonstrates strong skills in Excel, particularly with Power Query, pivot tables, and interactive dashboards.
- **Efficient Data Handling**: Successful handling of large datasets, including the calculation and display of meaningful KPIs.
- **Interactive Dashboards**: The ability to create user-friendly, interactive dashboards is essential for Data Analysts and PMO Analysts.

## 11. Impressions for Recruiters:

### Strengths:
- **Data Analysis**: Demonstrated a solid understanding of data analysis using Excel, with a focus on meaningful KPIs and visual storytelling.
- **Interactive Dashboards**: Successfully created engaging, interactive dashboards that allow users to filter data and explore insights.
- **Attention to Detail**: Emphasis on year-on-year growth and CO₂ per capita shows the ability to extract valuable insights from data.

### Areas for Improvement:
- **Advanced Interactivity**: Future work could leverage Power BI for enhanced interactivity, especially for handling larger datasets and providing more advanced visuals.
- **Data Cleansing**: More rigorous handling of missing data and outliers could lead to more reliable and precise insights.
- **Data Model Optimization**: Ensuring slicers work seamlessly across different data models would improve the overall experience and utility of the dashboard.

## 12. Dashboard Overview (Suggested Visuals)

Example visuals:

1. **CO₂ Emissions by Country** – Bar chart for top countries, line chart for emissions by source
2. **Emissions by Region** – Line chart for YoY growth, pie chart for global share
3. **CO₂ & Energy Efficiency** – Bubble chart for energy efficiency, line chart for CO₂ and methane levels

![Star Shema](images/KPIs_Dashboard.png) 
![Star Shema](images/Dashboard_1.png)
![Star Shema](images/Dashboard_2.png)
