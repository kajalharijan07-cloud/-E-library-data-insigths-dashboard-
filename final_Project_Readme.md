# E-Library Data Insights Dashboard

This project provides a Python-based dashboard to analyze library borrowing trends and generate helpful visual insights using data visualizations.

---

##  Features

- Load and clean CSV dataset
- Detect and fill missing values
- Display useful statistics:
  - Top 5 most borrowed books
  - Average borrowing duration
  - Busiest borrowing day
- Filter data based on a selected column value
- Generate six different charts:
  - Bar chart — Most borrowed books
  - Line chart — Monthly borrowing trend
  - Pie chart — Genre distribution
  - Heatmap — Borrow duration via day/month
  - Count plot — Genre-wise book count
  - Histogram — Borrow duration distribution

---

##  Tools & Libraries

| Library | Use |
|--------|-----|
| pandas | Data processing |
| numpy | Numeric analysis |
| matplotlib | Basic visualization |
| seaborn | Advanced visualization |

Install dependencies:
```bash
pip install pandas numpy matplotlib seaborn
