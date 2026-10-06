# 🌍 Global TB Insights 2024: Exploring the Tuberculosis Burden

> **Turning WHO tuberculosis data into meaningful insights through data cleaning, analysis, and interactive visualization.**

**Tools:** Microsoft Excel | Power Query | Power BI | DAX | Data Modeling  
**Domain:** Healthcare Analytics | Tuberculosis  
**Analysis Year:** 2024

---

## 🦠 At a Glance

Tuberculosis continues to represent a significant global health challenge, but its burden is not distributed evenly across countries and regions.

This project explores the **global tuberculosis landscape in 2024** using data from the **World Health Organization (WHO) Global Health Observatory (GHO)**.

Multiple tuberculosis datasets were brought together, cleaned, transformed, and consolidated into a structured master dataset. The resulting data was then analyzed through an interactive **Power BI dashboard** to uncover differences in TB cases, deaths, incidence, childhood TB, HIV-positive TB, MDR/RR-TB, and treatment coverage.

> **From raw WHO datasets → to a cleaned master dataset → to an interactive story of the global TB burden.**

---

# 🎯 What Does This Project Explore?

The project is designed to answer questions such as:

- 🌍 What does the global TB burden look like in 2024?
- 📍 Which countries have the highest estimated TB cases?
- ⚰️ Which countries record the highest number of TB deaths?
- 🗺️ How does TB incidence vary across WHO regions?
- 👧 What is the burden of TB among children aged 0–14?
- 🧬 How are HIV-positive TB cases distributed across countries?
- 💊 How does TB treatment coverage vary?
- 💰 How is the estimated TB burden distributed across World Bank income groups?
- 📊 What relationship can be observed between TB incidence and treatment coverage?
- 🔎 How do TB cases and deaths compare across WHO regions?

---

# 🧭 Project Journey

The project follows a structured data analytics workflow:

```text
WHO TB Datasets
       ↓
Data Inspection
       ↓
Data Cleaning
       ↓
Data Transformation
       ↓
Data Validation
       ↓
Dataset Consolidation
       ↓
TB Master Dataset
       ↓
2024 Data Filtering
       ↓
Power BI Data Modeling & Analysis
       ↓
Interactive Dashboard
 ↓
Insights into the Global TB Burden

## 📂 Data Sources
World Health Organization — Global Health Observatory
The original datasets were obtained from the World Health Organization (WHO) Global Health Observatory (GHO).
The raw data contains tuberculosis-related indicators reported across countries, regions, global classifications, and World Bank income groups over multiple years.
For this project, the analysis is restricted to 2024.
Original Data Source:
https://www.who.int/data/gho/data/themes/topics/topic-details/GHO/cases-and-deaths
      
## 🎯 Problem Statement
This project seeks to uncover where, how, and among whom the global TB burden is concentrated in 2024.
- 🌍 Where is TB most prevalent? — Identify countries and regions with the highest TB cases and incidence.
- ⚰️ Where is the impact greatest? — Compare TB deaths across countries and regions.
- 👧 Who is affected? — Explore childhood and HIV-positive TB cases.
- 💊 How well are countries responding? — Compare treatment coverage with TB incidence.
- 💰 How is the burden distributed? — Examine TB cases across World Bank income groups.

## 🧾 Data Attributes
Attribute	Description
Indicator	Name of the TB indicator
Location	Country, region, or income group
Location Type	Type of geographical classification
Period	Year of the observation
Numeric Value	Numerical value of the indicator
Value	Reported value
Low / High	Lower and upper estimates
Parent Location	Parent geographical location
Source Data Set	Original WHO dataset
