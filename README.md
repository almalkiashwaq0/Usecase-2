# 🌍 World Happiness Analysis (2015–2019)

This project analyzes the **World Happiness Reports** from **2015 to 2019** to identify the factors influencing happiness levels across countries.  
It combines multiple datasets, cleans and preprocesses the data, performs exploratory analysis, and visualizes key findings.

---

## 🎯 **Project Purpose**
The main objectives of this project are:
- To analyze global happiness scores across **five years** (2015–2019).
- To clean and unify datasets from different years into one structured format.
- To identify the **most important factors** affecting happiness.
- To visualize trends, correlations, and rankings across countries and regions.

---

## 📂 **Dataset Explanation**
The datasets are sourced from the **World Happiness Reports** between 2015 and 2019.  
Each CSV file contains happiness data for one year.

| Year | Filename     | Rows | Columns | Description |
|------|------------|------|---------|------------|
| 2015 | `2015.csv` | 158  | 12 | Includes happiness scores, rankings, and related factors. |
| 2016 | `2016.csv` | 155  | 13 | Similar to 2015 but with updated column names. |
| 2017 | `2017.csv` | 155  | 12 | Slight changes in methodology introduced. |
| 2018 | `2018.csv` | 156  | 11 | Reduced features, focusing on key happiness drivers. |
| 2019 | `2019.csv` | 156  | 11 | Highlights top contributors like GDP, health, and social support. |

### **Key Columns**
- **Country / Region** → Name of the country or region  
- **Happiness Score** → Overall happiness index (0–10 scale)  
- **Economy (GDP per Capita)** → Contribution of economic strength  
- **Family / Social Support** → Impact of relationships and networks  
- **Health (Life Expectancy)** → Average healthy lifespan  
- **Freedom** → Perceived freedom of life choices  
- **Generosity** → Level of charitable giving  
- **Corruption Perception** → Trust in government and institutions  

---

## 🧹 **Data Cleaning Steps**
- Renamed columns to maintain consistent naming across years.  
- Filled missing numerical values using **median imputation**.  
- Dropped rows with excessive missing data.  
- Added a **Year** column and merged all datasets into a single **clean DataFrame**.

---

## 📊 **Key Insights**

### **1️⃣ Factors Influencing Happiness**
The factors are ranked by their impact on the **Happiness Score** based on correlation strength:

| Rank | Factor                            | Impact |
|------|----------------------------------|----------------------|
| **1** | Economy (GDP per Capita)        | ⭐⭐⭐⭐⭐ |
| **2** | Family / Social Support         | ⭐⭐⭐⭐ |
| **3** | Health (Life Expectancy)       | ⭐⭐⭐ |
| **4** | Freedom                        | ⭐⭐ |
| **5** | Trust (Government Corruption) | ⭐ |
| **6** | Generosity *(weak influence)* | ⭐ |

---

### **2️⃣ Regional Observations**
- **Western Europe** and **North America** consistently rank the highest.  
- **Sub-Saharan Africa** and **South Asia** consistently score the lowest.  
- Countries with **economic stability** and **strong social support systems** enjoy higher happiness.

---

### **3️⃣ Yearly Trends (2015 → 2019)**

**Top Countries by Year:**
- **2015** → Switzerland  
- **2016** → Denmark  
- **2017** → Norway  
- **2018** → Finland  
- **2019** → Finland
  
This analysis highlights how these countries maintained their top positions due to strong economies, better life expectancy, and excellent social support systems.

---

### **4️⃣ Correlation Highlights**
- Economy, Family, Life Expectancy, Freedom, and Trust → **positively correlated** with Happiness.  
- Generosity shows a **weak or negative correlation**.

---

## 🧩 **Conclusion**
- **GDP, Family, Health, and Freedom** are the most influential drivers of happiness.  
- **Generosity** has little effect on overall happiness.  
- **Finland** has consistently dominated as the happiest country in recent years.  
- The global happiness gap **persists**, showing unequal well-being across regions.

---

## 👩‍💻 **Author**
**Ashwaq Almalki**  
Data Scientist & Analyst | Machine Learning Enthusiast  
