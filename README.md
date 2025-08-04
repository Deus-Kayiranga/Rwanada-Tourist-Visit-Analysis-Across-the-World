# Rwanda-Tourist-Visit-Analysis-Across-the-World
This project aims to analyze tourism trends in Rwanda by identifying peak tourist seasons, analyzing the origin of tourists, and visualizing changes in tourist numbers over the years. The results will help generate data-driven recommendations for improving tourism strategies.

## 📍 Project Overview

This project aims to explore and analyze **Rwanda's tourism trends** over several years using public datasets from national and international sources. The primary focus was to:

- Identify **peak tourist seasons**
- Understand **tourist origins**
- Visualize **park visit patterns** and their correlation with international arrivals
- Develop **data-driven recommendations** for enhancing Rwanda's tourism strategies

---

## 🗃️ Datasets Used

1. **International Tourist Arrivals** – From Rwanda Development Board (RDB)
2. **National Park Visit Records** – Per park, annually
3. **Visitor Origin Breakdown** – Countries contributing the highest number of tourists

> Format: `.csv`  
> Source: RDB & International Development Reports (NISR, UNWTO, etc.)

---

## 🔧 Tools Used

- 🐍 **Python (Jupyter Notebook)** – Data preparation, EDA, modeling
- 📈 **Power BI Desktop** – Interactive visualization and dashboard creation
- 📁 **Pandas & Scikit-Learn** – For data manipulation and machine learning
- 🌐 **GitHub** – Version control and documentation

---

## 📊 Power BI Dashboard

A comprehensive and interactive Power BI dashboard was created to explore:

- 📆 Tourist arrival patterns by **year and season**
- 🏞️ Visits to major national parks like **Volcanoes**, **Nyungwe**, and **Akagera**
- 🌍 **Country-wise** tourist contribution
- 📉 Correlation between **tourist influx** and **park visits**
- 🕒 Seasonality using monthly breakdowns and trends

---

## Here is the Dashboard for my power Bi

<img width="1211" height="661" alt="Screenshot 2025-08-04 092651" src="https://github.com/user-attachments/assets/026d9757-1e6c-46ef-b396-2aef2a81f823" />

## Here are the merged datasets

<img width="767" height="194" alt="Screenshot 2025-08-04 101442" src="https://github.com/user-attachments/assets/cc6065e1-b8c5-4b17-b743-01869b4d390f" />

## 📁 Python Analysis Highlights (Jupyter)

### ✅ Data Understanding & Cleaning
- Handled null values and cleaned categorical inconsistencies
- Parsed time-based features from raw columns (Year, Month)
- Merged park visit and international arrival datasets

## Here are the merged datasets

<img width="767" height="194" alt="Screenshot 2025-08-04 101442" src="https://github.com/user-attachments/assets/cc6065e1-b8c5-4b17-b743-01869b4d390f" />


### 📈 Exploratory Data Analysis
- Descriptive stats (mean, median, mode, std, percentiles)
- Correlation heatmaps and trend line analysis
- Outlier detection on park visits and tourist origins

### 🧠 Feature Engineering
- Extracted features like:
  - `visit_efficiency_score` – % of tourists visiting parks
  - `tourism_growth_rate` – YoY growth by park and country
  - `season_peak_flag` – indicator for high/low seasons

### 🤖 Modeling
1. **Data Collection**:
   - Obtained and compiled datasets from reliable tourism data sources in Rwanda.
2. **Data Cleaning**:
   - Removed duplicates, handled missing values, and formatted timestamps.
3. **Feature Engineering**:
   - Extracted year, month, and seasonal indicators from dates.
   - Grouped by countries, time periods, and categories for better analysis.
---

## 📌 Key Findings

- **Volcanoes National Park** leads in visit numbers every year
- Peak seasons are typically around **July–August** and **December**
- Tourist origins are largely from **Europe**, **North America**, and **neighboring African countries**
- Strong correlation between **arrival volumes** and **park visits**
- Tourism Efficiency metric revealed underutilized years despite high arrival counts
- There is a steady recovery post-COVID-19 in 2022–2023.


## ✅ Conclusion

This project successfully analyzed Rwanda's tourism trends using Python for data preprocessing and Power BI for interactive visualization. The analysis revealed key insights such as seasonal fluctuations in tourist visits, leading countries of origin, and patterns in national park attendance. By transforming raw data into meaningful visual narratives, this project not only supports informed decision-making for stakeholders but also highlights opportunities for improving Rwanda’s tourism strategies.

Future enhancements may include integrating weather data, incorporating economic indicators, or forecasting tourism demand using advanced models. This project serves as a strong foundation for data-driven tourism planning and policy formulation in Rwanda.
