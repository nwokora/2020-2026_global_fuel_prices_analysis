# 💹 Global Fuel Prices Analysis (2020-2026)

This comprehensive analysis of global fuel prices from 2020 to 2026 provides a six-year view of how fuel affordability differs across continents and countries. It examines how income level, subsidy support, and tax burden interact to shape fuel price pressure, revealing clear regional inequalities in affordability. The analysis shows that fuel costs are generally highest in Europe and Oceania, while the Middle East benefits from lower prices and stronger subsidy support. It also highlights how higher income levels can cushion affordability pressure, whereas lower income levels, weaker subsidies, and heavier tax burdens can worsen it.

## 📂 Repository Layout  
- **📈 analysis charts** – Final analysis visuals (PNG)
- **🗄️ dataset** – Raw dataset and cleaned CSV files
- **📋 group tables** – Pandas aggregated tables in CSV files
- **⚙️ process charts** – Technical work steps visual (PNG)
- **📖 README.md** – Project overview
- **📉 Analysis Findings** – All metrics and findings from the analysis
- **💡 insights.md** – All insights from analysis

## 💡 Key Insights
Global fuel affordability differs widely across regions and countries. Europe and Oceania generally face the highest fuel prices and tax burdens, while the Middle East records the lowest prices and strongest subsidy support. Higher income concentration in some regions helps cushion the burden, whereas lower-income regions face greater pressure. Overall, affordability is shaped not just by fuel prices but by the combined effect of income, taxes, and subsidies. Policymakers should therefore balance taxation with targeted subsidies, especially in lower-income regions, to improve affordability.
**[See Insights](https://github.com/nwokora/2020-2026_global_fuel_prices_analysis/blob/main/insights.md)**

  ## 🛠️ Tools Used
-  **Excel** – Initial data preview and quick validation of rows & columns distributions
-  **Python** – Pandas (data cleaning & preparation) and Matplotlib (visualization)
-  **GitHub** – Hosting documented projects
-  **Markdown** – Documentation (.md files)

 ## 🧠 Skills Demonstrated
- Data transformation from raw to cleaned datasets using pandas
- Datetime standardization `df["date"] = pd.to_datetime(df["date"])`
- Date series indexing and chronological sorting `df = df.set_index("date").sort_index()`
- Missing value detection `df.isna().sum()`
- Duplicate index detection `df.index.duplicated().sum()`
- Daily price range calculation `df["range"] = df["high"] - df["low"]`
- Financial chart visualization of historical stock performance using Matplotlib
- Problem-solving to match and analyze aggregation trends

## 📊 Business Questions Answered
1. Total Trading Volume by Year
2. Average Daily Trading Volume by Year
3. Average Closing Price by Year
4. Average Daily Return by Year
5. Average Daily Return by Month
6. Closing Price with Major Stress Periods Highlighted

## 📉 Analysis Findings
key data points and metrics extracted from the KO analysis.
**[See Findings](https://github.com/nwokora/2020-2026_global_fuel_prices_analysis/blob/main/analysis_findings.md)**

## 📈 Analysis Charts
This folder holds all the final charts and visualizations created from this analysis.
These include resistance trends over time, comparisons by gender, age group, and bacterial species. View charts here:
**[See Charts](https://github.com/nwokora/2020-2026_global_fuel_prices_analysis/tree/main/analysis_charts)**

## ⚙️ Process Charts
Work-in-progress charts showing screenshots of analysis steps.
**[See Charts](https://github.com/nwokora/2020-2026_global_fuel_prices_analysis/tree/main/process_charts)**

## 🗄️ Dataset
**Raw Dataset** – Original KO stock data (1962-2022): open, high, low, close prices + daily volume (~15K trading days).  
**Cleaned Dataset** – Processed CSVs with optimised data types for Power BI analysis.
**[Dataset](https://github.com/nwokora/2020-2026_global_fuel_prices_analysis/tree/main/dataset)**

## 🔗 Data Source
Global Fuel Prices 2020–2026 by BELBIN BENO R M on Kaggle (5,279 rows × 7 columns).
**[Download Dataset](https://www.kaggle.com/datasets/belbino/global-fuel-prices-20202026)**
