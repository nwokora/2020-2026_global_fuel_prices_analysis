# 💹 Global Fuel Prices Analysis (2020-2026)

## 📌 Overview
This comprehensive analysis of global fuel prices from 2020 to 2026 provides a six-year view of how fuel affordability differs across continents and countries. It examines how income levels, subsidy support, and tax burdens interact to shape fuel price pressures, revealing clear regional inequalities in affordability.

This project involved data cleaning and table aggregation in Python using Pandas, followed by data visualization and dashboard creation in Power BI.

## 🎯 Objective
The objective of this analysis is to assess how fuel prices, tax percentages, subsidy support, and income levels shape fuel affordability across different continental regions and countries from 2020 to 2026, and to highlight the regions and countries most affected by affordability pressure.

## 📊 Analysis Questions
1. Average Fuel Prices by Countries.
2. Average Tax Percentage by Countries.
3. Average Fuel Price by Region.
4. Low-Income Countries' Affordability Analysis for Different Subsidy Categories.
5. Average Subsidy by Region.
6. Average Tax Percentage on Fuel by Regions.
7. Average Fuel Prices by Year.
8. Regional Income Level Analysis.
9. Regional Subsidy Level Analysis.

## 🛠️ Tools Used
-  Excel (Initial data preview and quick validation of rows & columns distributions)
-  Python (data cleaning, preparation, table aggregation)
-  Power BI (Analysis visualization)

## 🔗 Data Source
Global Fuel Prices 2020–2026 by BELBIN BENO R M on Kaggle (27,468 rows × 10 columns).
**[Download Dataset](https://www.kaggle.com/datasets/belbino/global-fuel-prices-20202026)**

## 🧹 Data Cleaning and Preparation
- Checked for duplicates (none were found).
- Checked for missing values (none were found).
- Standardized the date column format.
- Converted income_level and subsidy_level into numeric values.
- Aggregated the tables for analysis and visualization.

## 📉 Analysis
- **Average Fuel Price by Countries Analysis** – This analysis compared fuel prices across 84 countries in 7 regions to identify the 10 costliest and 10 most affordable countries. The findings showed that Europe accounted for 8 of the 10 highest-paying countries, while Africa and the Middle East accounted for most of the lowest-paying countries.
- **Regional Fuel Cost Structure Analysis** – These include: Average Fuel Prices, Average Subsidies, and Average Tax Percentages across regions to reveal the distinct patterns behind fuel affordability.
- **Share Percentage by Region and Income Level Analysis** – This analysis examined income distribution across regions to understand how regional income strength influences fuel affordability. The results showed that Oceania recorded 100% high-income share, Europe had 74% high and 26% middle, and North America had 67% high and 33% middle. Africa was dominated by low income at 74%, with 26% middle, while Asia and South America had a mix of the three income levels.
- **Share Percentage by Region and Subsidy Level Analysis** – This analysis explored how subsidy levels vary across regions and how those differences influence fuel prices. The results showed that the Middle East had the highest share of very high subsidy countries at 56%, while Africa and South America also had some countries with very high subsidy levels. In contrast, Oceania recorded 100% low subsidy, and Europe was dominated by a low subsidy at 87%.
- **Low-Income Subsidy Index Analysis** – This analysis examined how subsidy levels help reduce fuel affordability pressure in low-income countries. The best-performing countries were Venezuela, Libya, Egypt, and Nigeria, while Zimbabwe, Rwanda, Zambia, Mozambique, and Uganda ranked among the worst.
- **Yearly Price Analysis** – This analysis tracked fuel price trends over the last six years. The results showed a general upward trend, with average fuel prices increasing from 1.32 in 2020 to 2.37 in 2026. There was a slight dip in 2023, after which prices rose again.

## 🔭 Visualizations
<img width="627" height="254" alt="Average Fuel Price by Region" src="https://github.com/user-attachments/assets/d182547e-5dd3-4fd3-8ae9-3f1d0985add8" />   

**Average fuel prices varied widely by region, with Oceania and Europe recording the highest values overall. The Middle East had the lowest average fuel price, while South America and Africa also had relatively low prices.**

<img width="627" height="254" alt="Average Tax Percentage by Region" src="https://github.com/user-attachments/assets/bc877c97-3214-4388-8399-2d40f03572f1" />   

**Average tax percentages also differed noticeably by region. Oceania and Europe generally had the highest tax burdens, while South America had the lowest average tax percentage, followed by the Middle East.**

<img width="906" height="256" alt="Subsidy Charts" src="https://github.com/user-attachments/assets/e207c749-ec55-4400-bfb4-7cef93a42453" />

**The Middle East stands out with the highest average subsidy, and that matches its high share of Very High subsidy levels, while South America and Africa also show relatively stronger support than most regions. At the other end, Europe and especially Oceania have the lowest average subsidies, with Oceania being entirely in the Low subsidy category and Europe also heavily concentrated there. Overall, the pattern suggests that subsidy support is much stronger in the Middle East and weaker in Europe and Oceania.**

<img width="629" height="255" alt="Share_pct by Region and Income-level" src="https://github.com/user-attachments/assets/baf4febd-65f2-48d7-ba8c-71246bd0bdba" />

**Oceania is the most concentrated in the High category, with Europe and North America also leaning strongly toward High. In contrast, Africa is mostly in the Low category, and South America dominates the Middle level. Asia shows a more mixed split across the three categories, while the Middle East shows a split only between Middle and High, with High making up the larger portion.**

## 💡 Key Insights
Fuel affordability varies significantly across continental regions and countries from 2020 to 2026. The analysis shows that Europe and Oceania generally face the highest fuel prices and tax burdens, while the Middle East and South America record the lowest prices, probably due to strong subsidy support and low taxes. Regions like Oceania, Europe, and North America, with stronger income concentration, are better positioned to absorb the brunt of these low subsidies and high taxes, while Africa may likely face greater affordability pressure due to low income. Overall, fuel affordability is shaped by the combined impact of prices, taxes, subsidies, and income levels, with the greatest strain falling on specific regions and countries that are most exposed to these pressures. Policymakers should therefore balance taxation with targeted subsidies, especially in lower-income regions, to improve affordability.
**[See All Insights](https://github.com/nwokora/2020-2026_global_fuel_prices_analysis/blob/main/insights.md)**

## 📂 Repository Layout  
- **📈 analysis charts** – Final analysis visuals (PNG)
- **🗄️ dataset** – Raw dataset and cleaned CSV files
- **📋 group tables** – Pandas aggregated tables in CSV files
- **⚙️ process charts** – Technical work steps visual (PNG)
- **📖 README.md** – Project overview
- **🔎 Analysis Findings** – All metrics and findings from the analysis
- **💡 insights.md** – All insights from analysis
