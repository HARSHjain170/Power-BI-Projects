# 📊 Power BI Business Intelligence & KPI Dashboards

[![Power BI](https://img.shields.io/badge/Power_BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)](https://powerbi.microsoft.com/)
[![DAX](https://img.shields.io/badge/DAX-Data%20Analysis%20Expressions-orange?style=for-the-badge)](#)
[![Data Modeling](https://img.shields.io/badge/Data%20Modeling-Star%20Schema-blue?style=for-the-badge)](#)
[![Status](https://img.shields.io/badge/Status-Complete-success?style=for-the-badge)](#)

A repository of production-grade **Microsoft Power BI** executive reports demonstrating end-to-end Business Intelligence implementation: ETL data extraction, Star Schema data modeling, advanced DAX time-intelligence calculations, and user-centric UI/UX design.

---

## 📂 Dashboard Portfolio

### 1. 🍃 Air Quality & Environmental Analytics (`airquality.pbix`)
- **Objective**: Monitor atmospheric pollutants (PM2.5, PM10, CO, NO2, SO2, O3) and Air Quality Index (AQI) dynamics across geographical stations and temporal intervals.
- **Key DAX Measures**:
  - `AQI Severity Index`: Dynamic categorization based on WHO thresholds (Good, Moderate, Unhealthy, Hazardous).
  - `Rolling 7-Day Average Pollutant Concentration`: Smoothing volatile daily sensors.
- **Visuals & Layout**:
  - Geo-spatial mapping of high-pollution clusters.
  - Multi-line temporal trends highlighting seasonal smog peaks.
  - Interactive slicers for pollutant selection and date ranges.

### 2. 🛒 Customer Behavior & RFM Dashboard (`customer_behaviour.pbix`)
- **Objective**: Transform customer purchase records into segmentation insights (Recency, Frequency, Monetary).
- **Key DAX Measures**:
  - `Customer Lifetime Value (CLV)`: Cumulative revenue per active customer.
  - `Churn Propensity Score`: Calculated based on recency lapse days.
  - `Repeat Purchase Rate`: Ratio of multi-order buyers to total customer census.
- **Visuals & Layout**:
  - Cohort retention heatmaps.
  - Dynamic decomposition tree drilling down into churn factors.
  - Pareto chart (80/20 rule) identifying the revenue-driving top 20% consumer bracket.

### 3. 📈 Business KPI & Performance Reporting (`custom_prac.pbix`)
- **Objective**: Comprehensive operational tracking covering regional sales distributions, margin efficiency, and delivery SLA compliance.
- **Key DAX Measures**:
  - `YoY Sales Growth`: Year-over-year comparative revenue calculation.
  - `Profit Margin %`: Gross margin ratio dynamically formatted.
  - `Target Variance`: Real-time variance tracking against monthly organizational targets.

---

## 🛠️ BI Architecture & Best Practices Followed

- **Data Modeling**: Pure Star Schema architecture separating central Fact tables from clean Dimension tables (Date, Customer, Product, Geography) with 1-to-many single-directional relationships.
- **Date Dimension**: Dedicated custom calendar dimension table enabling robust time-intelligence formulas (`TOTALYTD`, `SAMEPERIODLASTYEAR`, `DATESINPERIOD`).
- **Performance Optimization**: Minimized calculated columns in favor of optimized DAX measures; applied query folding in Power Query.
- **Design & UX**: Harmonious dark/modern themes, clear visual hierarchy, accessible color palettes, and intuitive tooltips.

---

## 💻 How to View Dashboards

1. Download or clone this repository:
   ```bash
   git clone https://github.com/HARSHjain170/Power-BI-Projects.git
   ```
2. Open any `.pbix` file using **[Power BI Desktop](https://powerbi.microsoft.com/desktop/)**.

---

## 👨‍💻 Author

**Harsh Jain**  
Data Scientist & Data Analyst  
- GitHub: [@HARSHjain170](https://github.com/HARSHjain170)  
- Email: harshjain17074@gmail.com  
- Location: Ahmedabad, Gujarat, India
