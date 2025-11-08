# Sales & Use Tax Analytics

This project automates the **Sales and Use Tax calculation process** and visualizes results using **Alteryx Designer** and **Tableau**.  
It was developed as one of my first workflow projects as an Analytics Engineer to streamline tax reporting, improve accuracy, and enhance audit visibility.

---

## 🚀 Overview
Manual tax reporting often leads to inconsistent calculations and slow turnaround times.  
This workflow automates tax computations by applying jurisdiction-based rules and preparing data for visualization in Tableau.

**Key Goals:**
- Automate Sales and Use Tax calculations
- Ensure accuracy and compliance with regional tax rules
- Build dashboards for data-driven reporting

---

## ⚙️ Workflow (Alteryx)
- **Input & Preparation:** Imported raw sales data, standardized formats, and validated transaction records.  
- **Calculation Logic:** Applied regional tax rates and separated Sales Tax from Use Tax.  
- **Output:** Generated summarized tables by state, product category, and tax type, ready for Tableau visualization.

**File:** `sales_use_tax_calculation.yxmd`

---

## 📊 Visualization (Tableau)
The Tableau dashboard provides an interactive view of:
- **Sales vs. Tax Amounts** by region  
- **Tax Breakdown by Category**  
- **KPI Metrics** for compliance and potential audit risks  

**File:** `sales_use_tax_dashboard.twb`

*(Optional: Add a screenshot under `/images/dashboard_preview.png` once uploaded)*

---

## 💡 Insights
- Identified states with high Use Tax due to inter-state transactions  
- Exposed under-reported categories for audit follow-up  
- Reduced manual tax computation time by ~70%

---

## 🧰 Tools & Skills
- **Alteryx Designer** – ETL automation, data transformation, workflow design  
- **Tableau** – Visualization, storytelling, interactive dashboards  
- **Excel / CSV** – Data validation and tax rate references  

---

## 📁 Repository Structure
```
sales-use-tax-analytics/
│
├── alteryx/
│   └── sales_use_tax_calculation.yxmd
│
├── tableau/
│   └── sales_use_tax_dashboard.twb
│
├── data/
│   ├── sample_input.csv          # optional, anonymized or dummy data
│   └── output_summary.csv        # optional, clean output example
│
├── images/
│   └── dashboard_preview.png     # optional, screenshot of Tableau dashboard
│
└── README.md
```
---

## 👤 Author
**Syafiq**  
Analytics Engineer | ETL, Automation & Data Visualization  
☕ Coffee-fueled curiosity for making complex data simple.
