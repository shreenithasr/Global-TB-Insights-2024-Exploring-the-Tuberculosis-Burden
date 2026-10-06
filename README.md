# 🌍 Global TB Insights 2024: Exploring the Tuberculosis Burden

> Turning WHO tuberculosis data into meaningful insights through data cleaning, analysis, and interactive visualization.

### 🛠️: ![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=for-the-badge&logo=powerbi&logoColor=black)
![Microsoft Excel](https://img.shields.io/badge/Microsoft%20Excel-217346?style=for-the-badge&logo=microsoftexcel&logoColor=white)
![Power Query](https://img.shields.io/badge/Power%20Query-5B2C83?style=for-the-badge&logo=microsoft&logoColor=white)
![DAX](https://img.shields.io/badge/DAX-4472C4?style=for-the-badge&logo=powerbi&logoColor=white)

**Domain:** Healthcare Analytics | Tuberculosis  
**Analysis Year:** 2024

---

## 🦠 At a Glance

Tuberculosis continues to represent a significant global health challenge, but its burden is not distributed evenly across countries and regions.

This project explores the global tuberculosis landscape in 2024 using data from the **World Health Organization (WHO) Global Health Observatory (GHO)**.

Multiple tuberculosis datasets were cleaned, transformed, and consolidated into a structured master dataset. The resulting data was then analyzed through an interactive **Power BI dashboard** to explore TB cases, deaths, incidence, childhood TB, HIV-positive TB, MDR/RR-TB, and treatment coverage.

> From raw WHO datasets → to a cleaned master dataset → to an interactive story of the global TB burden.

---

## 🎯 Objective of the Project

The objective of this project is to analyze WHO tuberculosis data for **2024** to understand the **Global TB burden** and identify key patterns across countries, regions, populations, and income groups.

### 🔎 The Analysis Aims to:

- 🌍 **Identify** countries and regions with the highest TB burden.
- ⚰️ **Analyze** TB cases, deaths, and incidence rates.
- 👧 **Examine** the burden of TB among children and HIV-positive populations.
- 🦠 **Analyze** the distribution of MDR/RR-TB cases.
- 💊 **Compare** TB treatment coverage across countries.
- 💰 **Examine** the distribution of TB cases across World Bank income groups.
- 📊 **Transform** the findings into meaningful, interactive insights using **Power BI**.

---

## 📂 Data Sources

### World Health Organization — Global Health Observatory

The datasets used in this project were obtained from the **World Health Organization (WHO) Global Health Observatory (GHO)**.

The data contains tuberculosis-related indicators across countries, regions, and World Bank income groups. For this project, the analysis is focused on **2024**.

**Source:**  
https://www.who.int/data/gho/data/themes/topics/topic-details/GHO/cases-and-deaths

---

## 🌐 Data Landscape

The project uses **10 WHO tuberculosis datasets**, with each dataset representing a specific aspect of the global tuberculosis burden.

| Dataset | What It Contains |
|---|---|
| **TB Incidence** | Estimated TB incidence rate, representing the occurrence of tuberculosis cases in the population. |
| **TB Incidence Cases** | Estimated number of incident tuberculosis cases. |
| **TB New and Relapse Cases** | Number of newly diagnosed and relapse TB cases. |
| **TB Deaths Excluding HIV** | Estimated TB deaths excluding deaths among people living with HIV. |
| **TB HIV-Positive Incidence** | Estimated TB incidence among people living with HIV. This dataset had no 2024 records and was therefore not included in the 2024 analysis. |
| **TB HIV-Positive Cases** | Estimated number of TB cases among people living with HIV. |
| **TB HIV-Negative Deaths** | Estimated TB deaths among HIV-negative populations, including the corresponding death rate. |
| **TB Cases in Children Aged 0–14** | Estimated number of tuberculosis cases among children aged 0–14 years. |
| **TB MDR/RR-TB Incident Cases** | Estimated number of incident multidrug-resistant/rifampicin-resistant TB cases. |
| **TB Treatment Coverage** | Information on the level of TB treatment coverage reported for the population. |

### Common Information in the Datasets

The datasets contain common fields providing information about each observation:

- **ID** — Unique identifier for the record.
- **Indicator Code** — Code representing the specific TB indicator.
- **Spatial Dimension** — Geographical dimension of the data.
- **Spatial Dimension Value Code** — Code representing the spatial dimension value.
- **Parent Location Code** — Code representing the parent geographical location.
- **Parent Location** — Parent geographical location associated with the record.
- **Time Dimension** — Time period associated with the observation.
- **Numeric Value** — Numerical value of the reported indicator.
- **Time Dimension Value** — Numerical representation of the time period.

For this project, the 10 datasets were **cleaned, validated, consolidated into a TB Master Dataset, and filtered to 2024** for analysis.

---

## 🧹 Data Pre-Processing

The datasets were prepared using **Microsoft Excel and Power Query** through the following steps:

1. **Data Inspection** — Reviewed the structure, columns, and contents of all 10 WHO tuberculosis datasets.

2. **Column Validation** — Identified common columns across the datasets to ensure they could be consolidated correctly.

3. **Empty Column Removal** — Removed columns that contained no data across the datasets.

4. **Missing Value Handling** — Identified missing values in Parent Location and Parent Location Code and handled them using conditional columns.

5. **Data Standardization** — Standardized column names and verified appropriate data types for numerical, date, and categorical fields.

6. **Data Validation** — Checked for duplicate records, negative values, and inconsistencies in geographical classifications.

7. **Dataset Consolidation** — Appended the relevant tuberculosis datasets using Power Query to create a single **TB Master Dataset**.

8. **2024 Filtering** — Filtered the consolidated dataset to include only records relevant to the **2024 analysis**.

---

## 📊 Analysis & Visualisation

The cleaned dataset was analyzed and transformed into interactive Power BI dashboards to explore key tuberculosis indicators and uncover meaningful patterns and comparisons.

### Visualizations Used

- KPI Cards
- Bar Charts
- Column Charts
- Donut Charts
- Treemaps
- Scatter Plot
- Maps
- Slicers

### Areas of Analysis

- **TB Burden** – Analyzes the scale and distribution of TB cases and deaths across countries and WHO regions.
- **TB Incidence** – Examines TB incidence rates across countries and WHO regions.
- **Childhood TB** – Analyzes TB cases among children aged 0–14.
- **HIV-Positive TB** – Explores the distribution of TB cases among HIV-positive populations.
- **MDR/RR-TB** – Compares estimated MDR/RR-TB cases across countries.
- **Treatment Coverage** – Examines treatment coverage and its relationship with TB incidence.
- **Income Group Analysis** – Analyzes the distribution of estimated TB cases across World Bank income groups.
- **Regional Analysis** – Compares TB cases and deaths across WHO regions.

---


## 📊 Power BI Dashboard

The dashboard consists of three interactive pages:

### 🌍 01 — Global Tuberculosis Overview

**A Summary of the Global Tuberculosis Burden | 2024**

Provides a high-level view of TB cases, deaths, incidence, treatment coverage, and geographical distribution.

<img width="3075" height="1763" alt="Global Tuberculosis Insights 2024_page-0001" src="https://github.com/user-attachments/assets/ec3fec28-83f5-4440-8bc2-da255da3f6be" />

---

### 🌎 02 — Country-Wise Analysis

**Comparing Key Tuberculosis Indicators Across Countries | 2024**

Focuses on country-level comparisons of TB cases, deaths, childhood TB, MDR/RR-TB cases, and treatment coverage.

<img width="3075" height="1763" alt="Global Tuberculosis Insights 2024_page-0002" src="https://github.com/user-attachments/assets/284c17d9-ce11-4164-b8fe-6f000fbe6130" />

---

### 📈 03 — Tuberculosis Burden Analysis

**Key Comparisons and Relationships Across Tuberculosis Indicators | 2024**

Explores relationships between TB indicators, including TB incidence vs. treatment coverage, TB cases vs. deaths, childhood TB, and HIV-positive TB cases.

<img width="3075" height="1763" alt="Global Tuberculosis Insights 2024_page-0003" src="https://github.com/user-attachments/assets/12da157c-11bf-477f-a5a1-01d3a490117b" />

---

## 🔎 Key Findings

- **Global TB Burden** – The dashboard reports **10.70M TB cases** and **1.08M TB deaths** in 2024.
- **Country-Level Burden** – **India** has the highest estimated TB cases (**2.71M**) and TB deaths (**300K**), followed by Indonesia.
- **Regional Incidence** – **Africa (207)** and **South-East Asia (201)** record the highest TB incidence rates among the WHO regions analyzed.
- **Childhood TB** – **1.19M TB cases** were reported among children aged 0–14, with India recording the highest number (**289K**).
- **HIV-Positive TB** – **South Africa** has the highest HIV-positive TB cases (**134K**), followed by India (**37K**).
- **MDR/RR-TB** – **India** has the highest estimated MDR/RR-TB cases (**130K**).
- **Regional Case Burden** – **South-East Asia** records the highest number of incident TB cases (**3.7M**), followed by the Western Pacific (**2.9M**) and Africa (**2.6M**).
- **Income Group Distribution** – Lower-middle-income countries account for the largest share of estimated TB cases, at **61.88% (6.49M)**.

---

## 💡 Recommendations

Based on the findings, the analysis highlights the need to:

- **Prioritize TB Control** – Strengthen prevention and control efforts in countries and regions with a high TB burden.
- **Improve Early Detection** – Strengthen screening and early diagnosis in high-incidence areas.
- **Focus on Childhood TB** – Give greater attention to countries with a high burden of TB among children.
- **Strengthen Targeted Interventions** – Address the needs of populations affected by HIV-positive TB.
- **Address MDR/RR-TB** – Strengthen detection, treatment, and monitoring in countries with higher estimated MDR/RR-TB cases.
- **Improve Treatment Coverage** – Continue efforts to expand effective TB treatment coverage, particularly in high-incidence areas.

> **Overall, the analysis highlights the uneven distribution of the global TB burden and the importance of targeted, data-driven TB control strategies.**

---

## 🛠️ Tools Used

- 📊 **Microsoft Excel** — Data inspection and preparation
- 🔄 **Power Query** — Data cleaning, transformation, and consolidation
- 📈 **Power BI** — Data modeling, analysis, and visualization
- 📐 **DAX** — Measures and analytical calculations
  
---

## 👩‍💻 Author

**Shreenitha SR**  
*Aspiring Data Analyst*

Passionate about transforming data into meaningful insights and building data-driven solutions.  
Currently developing skills in data analytics, visualization, and business intelligence.

<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="20"/> **GitHub:** [shreenithasr](https://github.com/shreenithasr)  
<img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/linkedin/linkedin-original.svg" width="20"/> **LinkedIn:** [Shreenitha SR](YOUR_LINKEDIN_URL)  
📧 **Email:** [shreenitha.senthilkumar13@gmail.com](mailto:shreenitha.senthilkumar13@gmail.com)
