# Blinkit Sales Analysis Dashboard | Power BI

An interactive **Power BI sales analytics dashboard** built using Blinkit grocery sales data to evaluate **sales performance, outlet efficiency, and customer purchasing behavior**.  
This project showcases a complete **end-to-end data analytics workflow**, from raw data preparation to insight-driven visualization.

---

## Project Objective
The goal of this dashboard is to help stakeholders quickly understand **what drives sales and how outlet characteristics impact performance**.

Key objectives:
- Evaluate overall sales performance
- Identify high-performing outlet types and sizes
- Analyze customer preferences by item category and fat content
- Compare sales distribution across outlet location tiers
- Support data-driven business decisions through KPIs and visuals

---

## Dashboard Preview
![Blinkit Sales Dashboard](images/dashboard_overview.png)

---

## Business Overview
Blinkit is India’s last-minute grocery delivery platform.  
This dashboard provides actionable insights into **sales trends, outlet performance, and product-level metrics** across multiple dimensions such as outlet size, location tier, establishment year, and item categories.

---

## Dataset Description

### Raw Dataset
- **File:** `blinkit_raw_data.xlsx`
- Original, unprocessed sales data
- Contains missing values and inconsistent category labels
- Retained to ensure transparency and reproducibility

### Cleaned Dataset
- **File:** `blinkit_cleaned_data.xlsx`
- Cleaned, standardized, and optimized for analysis
- Used directly in Power BI for modeling and visualization

### Why Raw & Cleaned Data Are Separated
- Preserves original data integrity
- Enables easy reprocessing if business logic changes
- Follows industry best practices in analytics projects

### Dataset Columns
| Column Name | Description |
|------------|------------|
| Item Identifier | Unique product ID |
| Item Type | Product category |
| Item Fat Content | Low Fat / Regular |
| Item Visibility | Product visibility score |
| Item Weight | Weight of the product |
| Sales | Total sales amount |
| Rating | Average customer rating |
| Outlet Identifier | Unique outlet ID |
| Outlet Establishment Year | Year outlet was opened |
| Outlet Location Type | Tier 1 / Tier 2 / Tier 3 |
| Outlet Size | Small / Medium / High |
| Outlet Type | Grocery Store / Supermarket Types |

---

## Data Cleaning & Preparation
The following steps were performed prior to analysis:
- Removed duplicate records
- Standardized categorical values
- Handled missing and zero values
- Corrected inconsistent labels
- Converted columns to appropriate data types
- Built data model relationships
- Created calculated measures using DAX

---

## Dashboard Features

### Key KPIs
- Total Sales
- Average Sales
- Number of Items Sold
- Average Customer Rating

### Visualizations
- Sales Trend by Outlet Establishment Year (Area Chart)
- Sales by Item Fat Content (Donut Chart)
- Sales by Outlet Size (Donut Chart)
- Sales by Item Type (Bar Chart)
- Sales by Outlet Location Tier (Bar Chart)
- Fat Content Distribution by Outlet Tier
- Outlet Type Performance Table:
  - Total Sales
  - Number of Items
  - Average Sales
  - Average Rating
  - Item Visibility

### Interactive Filters
- Outlet Location Type
- Outlet Size
- Item Type

---

## Key Insights
- Tier 3 outlets generate the highest total sales
- Supermarket Type1 is the top-performing outlet type
- Medium-sized outlets contribute the most revenue
- Low-fat items show strong sales contribution
- Older outlets demonstrate more stable sales performance

---

## Repository Structure
```
blinkit-sales-analysis-dashboard/
│
├── data/
│ ├── blinkit_raw_data.xlsx
│ └── blinkit_cleaned_data.xlsx
│
├── images/
│ └── dashboard_overview.png
│
├── README.md
├── LICENSE
```
---

## Tools & Technologies
- Power BI Desktop
- DAX (Data Analysis Expressions)
- Microsoft Excel
- Data Cleaning & Transformation
- Business Intelligence & Data Visualization

---

## License
This project is licensed under the **MIT License**.

---
