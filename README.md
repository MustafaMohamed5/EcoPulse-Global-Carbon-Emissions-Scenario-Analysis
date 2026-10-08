# 🌍 EcoPulse: Global Carbon Emissions & Scenario Analysis

An interactive **Power BI** project designed to analyze global carbon emissions ($CO_2$), evaluate historical trends across regions and economic groups (such as G7), and model potential emission scenarios for data-driven decision-making.

---

## 📌 Project Overview

Understanding global carbon footprint patterns is essential for shaping sustainability policies and tracking environmental progress. **EcoPulse** aggregates multi-region emissions data alongside country metadata to provide actionable insights into:
- Global emission trajectory over time.
- Comparative analysis across major economic powerhouses (e.g., **G7 nations**).
- Scenario-based projections to evaluate carbon reduction target compliance.

---

## 📂 Repository Structure

├── GHGHighlights.xlsx               # Raw dataset containing historic greenhouse gas emissions
├── Country_Dimension_Master.xlsx    # Country metadata, regional classifications, and economic groupings (G7, etc.)
├── EcoPulse_Emissions_Analysis.pbix # Interactive Power BI Dashboard report file
└── README.md                        # Documentation


---

## 📊 Key Features & Visualizations

- **Global Emissions Overview**: High-level KPIs tracking cumulative $CO_2$ emissions, yearly growth rates, and top emitting nations.
- **Economic & Regional Segmentation**: Deep-dive slicers comparing **G7 countries** against regional aggregates.
- **Scenario Analysis**: Dynamic forecasting to simulate the impact of policy changes on global net-zero goals.
- **Interactive Data Model**: Star-schema model linking dimension master tables with historical highlight metrics for optimized DAX performance.

---

## 🛠️ Tools & Technologies Used

- **Power BI Desktop**: Data modeling, DAX measures, custom visual design, and interactive filtering.
- **Power Query**: Data extraction, transformation, and cleaning (ETL).
- **Microsoft Excel**: Data structuring for source datasets.
- **DAX (Data Analysis Expressions)**: Time intelligence functions, dynamic ranking, and scenario metrics.

---

## 🚀 How to Run the Project Locally

1. Clone this repository:
   ```bash
   git clone [https://github.com/MustafaMohamed5/EcoPulse-Global-Carbon-Emissions-Scenario-Analysis.git](https://github.com/MustafaMohamed5/EcoPulse-Global-Carbon-Emissions-Scenario-Analysis.git)
2. Open Power BI Desktop.

3. Open the EcoPulse_Emissions_Analysis.pbix file.

4. If prompted to refresh data sources, update the file path to point to GHGHighlights.xlsx and Country_Dimension_Master.xlsx on your local system.

👨‍💻 Author
Mustafa Mohamed Mostafa

Senior Engineering Student & Data Analyst

💼 [LinkedIn Profile](https://www.linkedin.com/in/mustafaabdelhafez/)

🐙 [GitHub Profile](https://github.com/MustafaMohamed5/)
