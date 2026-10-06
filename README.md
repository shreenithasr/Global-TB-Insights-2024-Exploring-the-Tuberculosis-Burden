# 🌍 Global TB Insights 2024: Exploring the Tuberculosis Burden

> Turning WHO tuberculosis data into meaningful insights through data cleaning, analysis, and interactive visualization.

**Tools:** Microsoft Excel | Power Query | Power BI | DAX  
**Domain:** Healthcare Analytics | Tuberculosis  
**Analysis Year:** 2024

---

## 🦠 At a Glance

Tuberculosis continues to represent a significant global health challenge, but its burden is not distributed evenly across countries and regions.

This project explores the global tuberculosis landscape in 2024 using data from the **World Health Organization (WHO) Global Health Observatory (GHO)**.

Multiple tuberculosis datasets were cleaned, transformed, and consolidated into a structured master dataset. The resulting data was then analyzed through an interactive **Power BI dashboard** to explore TB cases, deaths, incidence, childhood TB, HIV-positive TB, MDR/RR-TB, and treatment coverage.

> From raw WHO datasets → to a cleaned master dataset → to an interactive story of the global TB burden.

---

## 🎯 What Does This Project Explore?

- 🌍 What does the global TB burden look like in 2024?
- 📍 Which countries have the highest estimated TB cases?
- ⚰️ Which countries record the highest number of TB deaths?
- 🗺️ How does TB incidence vary across WHO regions?
- 👧 What is the burden of TB among children aged 0–14?
- 🧬 How are HIV-positive TB cases distributed across countries?
- 💊 How does TB treatment coverage vary?
- 💰 How is the estimated TB burden distributed across World Bank income groups?
- 📊 What relationship can be observed between TB incidence and treatment coverage?

---

### Dataset Information

The WHO tuberculosis datasets contain information on **tuberculosis-related indicators reported across countries, WHO regions, global aggregates, and World Bank income groups**.

The data represents different aspects of the global tuberculosis situation, including:

| Information | What It Represents |
|---|---|
| **TB Incidence** | Estimated occurrence of tuberculosis cases within a population. |
| **TB Cases** | Estimated number of people affected by tuberculosis. |
| **TB Deaths** | Number of deaths attributed to tuberculosis. |
| **New and Relapse Cases** | Reported tuberculosis cases that are newly diagnosed or occur as relapses. |
| **Childhood TB Cases** | Estimated tuberculosis cases among children aged 0–14 years. |
| **HIV-Positive TB Cases** | Tuberculosis cases occurring among people living with HIV. |
| **HIV-Negative TB Death Rate** | TB-related deaths among HIV-negative populations, expressed as a rate. |
| **MDR/RR-TB Cases** | Estimated cases of multidrug-resistant or rifampicin-resistant tuberculosis. |
| **TB Treatment Coverage** | The proportion or level of estimated TB cases covered by treatment, according to the WHO indicator. |
| **Geographical Information** | Identifies the country, WHO region, global level, or World Bank income group associated with each observation. |
| **Time Information** | Indicates the year and time period to which each observation belongs. |
| **Estimate Ranges** | Provides lower and upper bounds (`Low` and `High`) where estimates are reported with uncertainty ranges. |

---

## 📂 Data Sources

### World Health Organization — Global Health Observatory

The datasets used in this project were obtained from the **World Health Organization (WHO) Global Health Observatory (GHO)**.

The data contains tuberculosis-related indicators across countries, regions, and World Bank income groups. For this project, the analysis is focused on **2024**.

**Source:**  
https://www.who.int/data/gho/data/themes/topics/topic-details/GHO/cases-and-deaths

---

## 🎯 Problem Statement

This project seeks to uncover **where, how, and among whom the global TB burden is concentrated in 2024**.

- 🌍 **Where is TB most prevalent?** — Identify countries and regions with the highest TB cases and incidence.
- ⚰️ **Where is the impact greatest?** — Compare TB deaths across countries and regions.
- 👧 **Who is affected?** — Explore childhood and HIV-positive TB cases.
- 💊 **How well are countries responding?** — Compare treatment coverage with TB incidence.
- 💰 **How is the burden distributed?** — Examine TB cases across World Bank income groups.

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

## 🔎 Key Insights

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

- **Microsoft Excel** — Data inspection and preparation
- **Power Query** — Data cleaning, transformation, and consolidation
- **Power BI** — Data modeling, analysis, and visualization
- **DAX** — Measures and analytical calculations

---

## 👩‍💻 Author

**Shreenitha SR**

*Aspiring Data Analyst*

🔗 [GitHub](https://github.com/shreenithasr)

🔗 [LinkedIn](#)
