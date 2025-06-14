
# IMF Assessment

This repository contains all files and documentation related to the two assessment tasks provided for the IMF data visualization and analysis challenge.

### Repository Structure

```
IMF-Assessment/
│
├── PowerBI/                   # Power BI Dashboard and Documentation
│   ├── IMF_Dashboard.pbix
│   └── Documentation PowerBI.md      # Approach, challenges, and user guidance
│
├── Python/                    # Python Data Processing and Visualization
│   ├── WEO_Data.xlsx
│   ├── economic_analysis.py
│   ├── economic_data_analysis.xlsx
│   └── requirements.txt
```

---

##  Power BI Task

Located in the `PowerBI/` folder:
- Contains the `.pbix` dashboard file and accompanying documentation.
- Dashboard visualizes GDP growth and inflation trends over 2015–2024 for selected countries.
- Includes drill-through and economic zone segmentation.

---

##  Python Task

### Description

The Python script processes and analyzes international economic indicators (GDP growth and inflation) for selected countries from 2015–2024.

### Prerequisites

Ensure Python is installed, then install dependencies by running:

```bash
pip install -r requirements.txt
```

### How to Run

1. Navigate to the `Python/` directory:
   ```bash
   cd Python
   ```
2. Execute the script:
   ```bash
   python economic_analysis.py
   ```

### Output Summary

After running the script, the following will be generated:

-  **Console Output**: A summary table displaying average GDP growth and inflation rates per country.
-  **Charts**:
  - `gdp_growth_chart.png`: Line chart showing GDP growth trends (2015–2024).
  - `inflation_2024_chart.png`: Bar chart comparing 2024 inflation rates across countries.
-  **Excel Report**:
  - `economic_data_analysis.xlsx`: Contains the summary table and both charts embedded.

These outputs provide a concise economic snapshot to support analysis and reporting needs.
