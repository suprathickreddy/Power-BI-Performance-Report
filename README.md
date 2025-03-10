
# Power BI Performance Report  

## Overview  
This project is an end-to-end Power BI portfolio project that focuses on creating a dynamic and interactive performance report for a fictional company. It leverages **DAX measures, Power Query transformations, virtual tables, and switch measures** to analyze **sales, profitability, and account segmentation**.  

## Key Features  

### 🔹 Data Processing & Modeling  
- Imported and cleaned **Excel-based** sales, account, and product hierarchy data using **Power Query**.  
- Created **virtual tables** for date and slicer values.  
- Established **data model relationships** and optimized table structures.  

### 🔹 DAX Measures & Calculations  
- Developed **key financial metrics** (Sales, Gross Profit, Quantity, Cost of Goods).  
- Implemented **Year-to-Date (YTD) and Prior Year-to-Date (PYTD) measures** using `TOTALYTD()` and `SAMEPERIODLASTYEAR()`.  
- Built **switch measures** for dynamic metric selection.  

### 🔹 Interactive Visuals & Analytics  
- **Treemap analysis** of **Bottom 10** countries by sales performance.  
- **Waterfall chart** to track **period-over-period performance changes**.  
- **Combo chart (Line & Stacked Column)** to compare **YTD vs PYTD trends** by month.  
- **Scatter plot with segmentation** for account profitability analysis.  

### 🔹 Dynamic Formatting & User Experience  
- **Conditional formatting** for profitability trends (**Green/Red indicators**).  
- **Custom slicers** and **dynamic titles** for improved usability.  
- **Enhanced dashboard layout** and **UX design** using PowerPoint backgrounds.  

## Technologies Used  
- **Power BI** (Power Query, DAX, Data Modeling, Visuals)  
- **Excel** (Data Source)  
- **DAX Functions** (`SUM()`, `DIVIDE()`, `CALCULATE()`, `SWITCH()`, `TOTALYTD()`, etc.)  

## Setup & Usage  
1. **Download** the Power BI `.pbix` file from this repository.  
2. **Open** the file in **Power BI Desktop**.  
3. Ensure **Excel data sources** are correctly linked.  
4. **Explore** the interactive dashboard using slicers and visual filters.  

## Repository Structure  
```
📂 PowerBI-Performance-Report  
 ├── 📄 README.md  # Project documentation  
 ├── 📂 Data       # Sample Excel data files (if applicable)   
 └── 📄 Report.pbix # Power BI report file  
```
