# 🇲🇾 Malaysia Labour Force Analysis (2010–2025)

**Prepared by:** Hanis Ilya 
**Data Source:** [Department of Statistics Malaysia (DOSM)](https://www.dosm.gov.my)  
**Tools Used:** Python (Google Colab), pandas, matplotlib, seaborn  
**Dataset:** Monthly Principal Labour Force Statistics (2010–2025)

---

## 📘 Overview
This project analyzes **Malaysia's labour force, employment, and unemployment trends** from **2010 to 2025** using official data from the Department of Statistics Malaysia (DOSM).  
The analysis aims to uncover how the **COVID-19 pandemic** and subsequent economic recovery affected the country's labour market dynamics.

---

## 🎯 Objectives
- Examine long-term trends in **employment, unemployment, and participation rates**  
- Understand the **impact of the COVID-19 pandemic** on Malaysia’s labour market  
- Identify **correlations** among key labour force indicators  
- Visualize trends to support **economic and policy insights**

---

## 🧰 Tools & Libraries
- **Python** (Google Colab)
- **pandas** – data cleaning and transformation  
- **matplotlib** – data visualization  
- **seaborn** – advanced statistical plots  

---

## 📊 Data Overview

| Column | Description |
|:--------|:-------------|
| `date` | Month and year (2010–2025) |
| `lf` | Total labour force |
| `lf_employed` | Total employed persons |
| `lf_unemployed` | Total unemployed persons |
| `lf_outside` | Population outside labour force |
| `p_rate` | Labour force participation rate (%) |
| `ep_ratio` | Employment-to-population ratio (%) |
| `u_rate` | Unemployment rate (%) |

---

## 📈 Visualizations

| Visualization | Description |
|:--------------|:-------------|
| ![Figure 1](visualizations/Figure1.png) | Unemployment Rate (2010–2025) |
| ![Figure 2](visualizations/Figure2.png) | Employment vs Unemployment Trend |
| ![Figure 3](visualizations/Figure3.png) | Correlation between Labour Force Indicators |


---

## 🔍 Key Findings

### 1️⃣ Unemployment Rate (2010–2025)
Malaysia’s unemployment rate remained stable between **2010 and 2019**, averaging around **3.3%**.  
A sharp increase occurred in **2020** due to the **COVID-19 pandemic**, peaking above **4.5%** as lockdowns and business closures impacted jobs.  
The rate gradually declined after 2021 as economic recovery measures took effect, reaching **pre-pandemic levels by 2025** — a sign of resilience and strong policy intervention.

---

### 2️⃣ Employment vs Unemployment Trend
Employment and unemployment show an **inverse relationship** — as employment rises, unemployment falls.  
During **2020–2021**, employment dropped significantly while unemployment surged.  
From **2022 onward**, employment rebounded steadily, reflecting **post-pandemic job growth** and the **rise of hybrid and digital industries**.

---

### 3️⃣ Correlation of Labour Force Indicators
Correlation analysis reveals:
- Strong positive correlation between **labour force**, **employment**, and **participation rate**  
- Slight negative correlation between **unemployment** and other indicators  
This suggests that increased labour market participation efficiently translates into more job creation and reduced unemployment — a sign of structural stability in Malaysia’s labour market.

---

## 🧩 Conclusion
Between **2010 and 2025**, Malaysia’s labour market demonstrated **steady recovery and adaptability**.  
The **COVID-19 pandemic** caused short-term disruptions, but employment rebounded as the economy diversified and digital transformation accelerated.  
By **2025**, the unemployment rate had normalized, showing **effective economic policy**, **worker resilience**, and **sustainable growth** in labour participation.



