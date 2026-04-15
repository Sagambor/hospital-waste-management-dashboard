# hospital-waste-management-dashboard
Excel Power Query project cleaning hospital waste data and building an interactive dashboard with PivotTables, charts, and slicers
# Hospital Waste Management Analysis (Excel Power Query + PivotTables)

## 📊 Project Overview
This project analyzes hospital waste management data using Excel’s Power Query and PivotTables.  
The goal was to clean raw records, handle inconsistencies, and build an interactive dashboard for management insights.

## 🧹 Data Cleaning Steps
- Standardized department and waste type names.
- Unified date column into `YYYY-MM` format.
- Removed duplicates (reduced dataset from 185 → 179 rows).
- Flagged and capped outliers (>500 kg capped at 500).
- Created clean columns: `Outlier` and `Quantity_Capped`.

## 📈 Analysis Outputs
- **PivotTable 1: Monthly Waste Trends**  
  - Line chart showing total waste quantities by month.  
  - Interactive slicers for Department and Waste Type.  

- **PivotTable 2: Departmental Waste Comparison**  
  - Column chart comparing total waste quantities across departments.  
  - Slicers for filtering by Waste Type.  

## 📊 Dashboard
- Combined both charts into a single **Hospital Waste Management Dashboard**.  
- Filters allow dynamic exploration by Department and Waste Type.  
- Provides management‑ready insights into waste generation patterns.

## 🔑 Key Insights
- Waste peaked in **August 2025**, driven largely by sharps.  
- **Surgical Ward** consistently produced the highest waste volumes.  
- **Chemical waste** was concentrated in Laboratory and Pharmacy.  
- General waste remained relatively stable across months.

## 📂 How to Use
- Open the `Cleaned_Data` sheet for the prepared dataset.  
- Use slicers on the dashboard to filter by Department or Waste Type.  
- Charts update dynamically for trend exploration and comparison.

---

### ✅ Recruiter‑Ready Value
This project demonstrates:
- Intermediate Power Query skills (data cleaning, custom formulas).  
- PivotTable and chart building for interactive analysis.  
- Dashboard design for clear, actionable insights.  
