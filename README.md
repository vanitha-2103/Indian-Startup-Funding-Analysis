# 📊 Indian Startup Funding Analysis (2020–2025)

End-to-end Data Analytics project analyzing Indian startup funding trends, investment stages, and sector-wise capital allocation using **SQL, Excel, and Power BI**.

---

## 📌 Business Problem & Objective
Understanding funding distribution, investor sentiment, and geographic hubs across the Indian startup ecosystem to extract data-driven business insights for venture capitalists and business strategists.

---

## 🛠️ Tools & Technical Stack
* **Database:** MySQL (STR_TO_DATE, Window Functions, Group By, Aggregations)
* **Data Processing:** Microsoft Excel (Data Validation, Cleaning, Pivot Tables)
* **Visualization:** Power BI (DAX Measures, Dynamic KPI Cards, Interactive Slicers)

---

## 💡 Key Business Insights
* **Peak Investment Periods:** Funding experienced major surges in **2021 and 2024**, driven by post-pandemic digitization and late-stage investments.
* **Dominant Sector:** **FoodTech** emerged as the top-funded industry, capturing a significant portion of total capital allocation.
* **Top Regional Hub:** **Pune** outperformed other major metro cities in terms of the total number of funded startups.
* **High-Value Deal Types:** **Series B & Series C** funding rounds recorded the highest average deal sizes.

---

## 📊 Dashboard Previews
![Dashboard Overview](dashboard_overview.png)  
![Sector Analysis](sector_analysis.png)

---

## 📁 Repository Structure
* `raw_startup_funding.csv` — Original raw dataset
* `Indian_Startup_Funding_Cleaned.csv` — Processed & cleaned dataset
* `analysis_queries.sql` — MySQL scripts used for ETL, cleaning, and business queries
* `Startup_Funding_Analysis.pbix` — Interactive Power BI Dashboard file

---

## 🧹 Data Cleaning & ETL Steps
* **Date Formatting:** Converted non-standard date strings into standard SQL `DATE` format using `STR_TO_DATE()`.
* **Handling Missing Data:** Treated `NULL` and blank values in key columns (`Amount`, `City`, `Industry`).
* **Data Standardization:** Resolved regional spelling inconsistencies (e.g., standardizing city and sector names).
* **Duplicates Removal:** Deduplicated record entries based on unique venture IDs.

---

## 🔍 Key Queries & Analysis Covered
1. **Yearly & Quarterly Funding Trends:** Tracking capital flow year-over-year.
2. **Industry & Sector Performance:** Identifying top capital-attracting domains.
3. **Geographic Distribution:** Mapping startup density by city.
4. **Investor & Deal-Size Breakdown:** Isolating large-scale deals (>$10M) and top active investors.

---

## 👤 Author
**Vanitha N**  
*Aspiring Data Analyst | SQL | Power BI | Excel*  

* **LinkedIn:** [Vanitha N Profile](https://linkedin.com/in/vanitha-n-161a043b3)  
* **Email:** vanithavijay2103@gmail.com  
* **GitHub:** [vanitha-2103](https://github.com/vanitha-2103)
