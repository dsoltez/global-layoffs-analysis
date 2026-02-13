# Global Layoffs Dashboard (2020–2023)
## Overview
- This project analyzes global layoffs from 2020–2023 using a combination of SQL for data cleaning and exploratory analysis and Excel for dashboard visualization. The goal was to transform raw layoff records into a clear, insight‑driven report that highlights trends across companies, industries, countries, and years.
- The final deliverable is an executive‑style Excel dashboard summarizing key findings through KPI cards, bar charts, a filled map, and a time‑series trend line.

# 1. Tools & Technologies
- SQL (data cleaning, aggregation, EDA)
- Excel (dashboard design, charts, KPI cards, filled map)
- CSV files (raw + cleaned datasets)

# 2. Project Workflow
## A. Data Cleaning in SQL
- Removed duplicates and standardized inconsistent fields
- Cleaned date formats and normalized company/industry names
- Filtered invalid or incomplete records
- Aggregated layoffs by:
  - Company
  - Industry
  - Country
  - Year
## B. Exploratory Data Analysis
Using SQL queries, I identified:
- Top 10 companies by total layoffs
- Top 10 industries impacted
- Countries with the highest layoff counts
- Year‑over‑year layoff trends (2020–2023)
## C. Export to Excel
- Exported cleaned and aggregated SQL outputs into structured CSV files
- Imported the data into Excel for visualization
## D. Dashboard Development
Built a multi‑visual dashboard including:
- KPI Cards: Total layoffs, peak year, peak country, peak company
- Bar Charts: Top 10 companies and industries
- Filled Map: Layoffs by country
- Line Chart: Total layoffs by year with trendline
- Consistent formatting and layout for a clean, executive‑ready presentation

# 3. Key Insights
- 2022 was the peak year for global layoffs
- The United States accounted for the highest number of layoffs
- Amazon had the largest total layoffs among all companies

# 4. Repository Structure

| Folder / File | Purpose | Key Contents |
|----------------|---------|--------------|
| [`data/`](data/) | Cleaned datasets used in analysis | `layoffs.csv`, `Layoffs_Cleaned.csv`, `Total Laid Off By Year.csv`, `Total Laid Off by Company.csv`, `Total Laid Off by Country.csv`, `Total Laid Off by Industry.csv` |
| [`sql/`](sql/) | SQL queries for the aggregated data | `17. Data Cleaning.sql`, `18. Exploratory Data Analysis.sql`, |
| [`visuals/`](visuals/) | Excel Dashboard | `Global Layoffs Dashboard.png`, `World Layoffs By Company, Industry, Counry, and Total Yearly Layoffs.pdf`, `World Layoffs By Company, Industry, Counry, and Total Yearly Layoffs.xlsx`  |
| [`README.md`](README.md) | Full project documentation & overview | — |
- Tech‑related industries dominated the top 10 most impacted sectors
- Layoffs increased sharply from 2020 to 2022 before leveling off

# 5. How to View the Dashboard
- Download the Excel file from the dashboard folder
- Open it in Excel
- Explore the KPI cards, charts, and map to review insights

# 6. Contact
If you’d like to discuss the project, feel free to email me at dsoltez13@gmail.com




