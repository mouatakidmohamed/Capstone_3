# Capstone 3: EmporiUm Sales Analysis with Power BI

## MOHAMED MOUATAKID 

## Overview
This project analyzes four years of sales data (2022–2025) for EmporiUm, a virtual student bookstore, 
focusing on the **South region** (Florida, South Carolina, Texas). The report was built for the South 
region's director and store managers to support data-driven business decisions.

## Report Contents
- **Page 1 – South Region Sales Trends & Category Performance**
  - Line chart: monthly sales trends across the full 4-year period
  - Bar chart: sales performance by product category
- **Page 2 – South Region: State Breakdown & Top Books**
  - Donut chart: relative sales by state within the South region
  - Table: top-selling general-audience books with author names (excluding textbooks and study guides)

## Data Sources
- `Capstone3_Sample_Sales.xlsx` — store sales, online sales, products, store locations, management team, 
  inventory categories, shipper list
- `book_list.txt` — title and author list for general-audience books

## Data Cleaning Highlights
- Removed unreliable Category data from raw sales tables; rebuilt clean Category/Subcategory via merge with Products
- Combined Online Sales' separate Year/Month/Day columns into a single date field
- Standardized inconsistent state abbreviations (e.g. CT/Connecticut, NY/New York)
- Matched book titles to author names via text merge, resolving punctuation and whitespace mismatches
- Built a unified State column combining in-store and online sale locations

## Video Walkthrough
LINK TO YOUR VIDEO : https://youtu.be/nhtDIV2ufQM




