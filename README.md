# Edutech-Lead-Conversion-Analysis

**Author:** Pujitha
**Date:** October 2025  
**Tools Used:** Python, Pandas, Matplotlib, Seaborn  
**Environment:** Jupyter Notebook

---

## Project Overview
This project focuses on cleaning, validating, and analyzing an Edutech sales leads dataset to identify factors affecting lead conversions.  
The dataset contained multiple data quality issues such as inconsistent formatting, missing values, incorrect data types, and anomalies in date and categorical fields.  
The goal was to produce a cleaned dataset and extract meaningful business insights for decision-making.

---

##  Data Cleaning Steps
1. **Removed junk characters and newlines** from column names and cells.  
2. **Converted data types** — dates into datetime, numeric columns into floats.  
3. **Handled missing values** — filled numeric NaNs with medians and categorical ones with “Unknown.”  
4. **Removed duplicates** using `Lead ID` as a unique identifier.  
5. **Standardized text fields** (title-cased, stripped whitespace).  
6. **Validated logical consistency** — ensured conversion dates were after lead generation dates.  

Result: a **fully clean dataset (132 rows × 15 columns)** ready for analysis.

---
📄 [Download Project Report (PDF)](docs/Edutech_Lead_Analysis_Report.pdf) 

## Exploratory Data Analysis (EDA)
### Conversion Rate by Region
- Highest conversions observed in **East (29%)** and **West (29%)** regions.  
- **North region** underperformed (21%) → improvement opportunity.  

### Sales Performance by Salesperson
- **John** achieved the best conversion rate (37%) and highest revenue.  
- **Priya** had the lowest conversion rate (15%) → potential training/lead quality issue.  

### Lead Source vs Conversion Rate
- **Google Ads** leads converted best (40%).  
- **Organic** and **Social Media** performed moderately (28–29%).  
- **Referral leads** underperformed (7%), suggesting weak incentive or tracking.

---

## Key Insights & Recommendations
- **Focus on Google Ads** — best ROI on paid marketing.  
- **Strengthen North region** performance through improved follow-up strategy.  
- **Standardize data entry** to avoid duplicated/mixed category labels.  
- **Train underperforming sales reps** (especially Priya) based on top performers’ methods.  

---

## Learning Outcomes
- Mastered real-world data cleaning: handling missing, inconsistent, and mixed-format data.  
- Practiced exploratory analysis using Pandas groupby, aggregation, and visualization.  
- Translated data results into clear business insights and recommendations.

---
