# national-mortality-analytics

# 📊 National Mortality Analytics (SDG 3: Good Health & Well-Being)

### *A Business Data Analytics Project on Malaysia's Health Disparities (2000–2023)*

## 🌟 Executive Summary

This project leverages **Business Intelligence** to analyze 23 years of Malaysian mortality data, specifically targeting **United Nations SDG 3: Good Health and Well-Being**. By transforming raw government data from **OpenDOSM** into an interactive analytical tool, I identified critical healthcare gaps, demographic risks, and the profound impact of the COVID-19 pandemic on national health infrastructure.

## 🚀 Key Business Insights

* **The COVID-19 Surge:** Identified a dramatic **28.8% spike** in mortality during 2021, marking a historical peak of **898,000 deaths** and highlighting the need for enhanced emergency preparedness.


* **High-Risk Demographic Clusters:** Discovered that **Bumi_malay males** represent the highest mortality subgroup (over **1 million deaths**), suggesting a critical need for targeted male-focused health campaigns.


* **Geographic Hotspots:** Urbanized states like **Selangor (2.08M deaths)**, **Johor (1.71M)**, and **Perak (1.60M)** drive the highest mortality totals, likely due to high population density and urban health challenges.


* **Systemic Reporting Gaps:** Analysis revealed that lower death totals in territories like **Putrajaya** and **Labuan** may mask underlying healthcare access barriers or data reporting limitations.



## 🛠️ Technical Implementation

### **Data Engineering & Preprocessing**

* **Dataset Size:** 7,854 records sourced from OpenDOSM.


* **Data Cleaning:** Conducted mean imputation for missing values in the absolute death count column to maintain distribution consistency.


* **Categorical Standardization:** Standardized ethnicity and gender formatting across two decades of records to ensure 100% data integrity.



### **Analytics & Visualization**

* **Descriptive Statistics:** Modeled quartiles and standard deviation to identify a **right-skewed distribution** in national death counts.


* **Intersectional Analysis:** Engineered a **heatmap** via Pivot Tables to visualize the intersection of gender and ethnicity, revealing consistent male vulnerability across all groups.


* **Trend Forecasting:** Developed longitudinal line charts (2000–2023) to visualize population-driven growth versus pandemic-driven spikes.



## 📂 Repository Structure

```text
├── data/               # Raw and cleaned datasets (OpenDOSM source)
├── images/             # Dashboard screenshots and heatmaps
├── report/             # Full Business Data Analytics Report (PDF)
├── .gitignore          # Prevents Office temp files from cluttering the repo
├── README.md           # Project documentation and insights
└── National_Mortality_Dashboard.xlsx  # Interactive Excel tool

```

## 📥 How to Use

1. **Download** the `National_Mortality_Dashboard.xlsx` file.
2. **Open** in Microsoft Excel and enable Macros/Content.
3. **Use Slicers** to filter mortality trends by **State**, **Ethnicity**, or **Year** for real-time visual updates.
