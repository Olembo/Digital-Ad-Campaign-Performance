# Digital Ad Campaign Performance Analysis

**Author:** [Devin Richmond]  
**Tools Used:** Excel, Python (for data cleaning) 
**Data:** Simulated ad campaign data, 2023–2025 (37,000 daily records)

---

## Project Overview

This project analyzes digital advertising campaign data for multiple countries and platforms (2023–2025), focusing on campaign spend, revenue, engagement (impressions, clicks), and efficiency metrics (ROAS, CTR, CPC).  
The goal is to surface actionable insights and recommendations to optimize digital marketing strategy and resource allocation.

---

## Files Included

- **Raw_Data.xlsx**: Original, unmodified dataset  
- **[Workbook]_Cleaned.xlsx**: Cleaned dataset + full EDA, charts, and analysis (multi-tab Excel file)  
- **Issues_Log.xlsx**: Documentation of all data quality issues and resolutions (also a sheet in EDA workbook)  
- **README.md**: This file

---

## Data Cleaning & Preparation

- Standardized date formats and removed non-date values  
- Mapped country codes/abbreviations to full names  
- Unified currency formats and converted all Spend/Revenue to USD  
- Addressed missing, blank, or inconsistent values in all core columns  
- Documented every issue and fix in the Issues Log sheet

---

## Exploratory Data Analysis (EDA)

- **Descriptive statistics**: Spend, Revenue, Impressions, Clicks (row count, blanks, avg, min, max, sum)
- **Distribution analysis**: Spend/revenue/click/impression histograms reveal campaign mix and outliers
- **Segmentation**:  
    - **By country:** Most spend/revenue from 5 major markets; smaller markets contribute little in USD
    - **By platform:** Instagram, Twitter, Facebook, Google, LinkedIn, TikTok
    - **By campaign/channel/status:** Top 10 campaigns account for outsized revenue; many campaigns are “paused” or “ended”
- **Time trend analysis:** Stable spend/revenue/engagement over quarters, with occasional peaks for promotions or campaigns
- **Efficiency metrics:**  
    - **ROAS (Return on Ad Spend)**: Revenue / Spend  
    - **CTR (Click-Through Rate)**: Clicks / Impressions  
    - **CPC (Cost per Click)**: Spend / Clicks  
    - Calculated and visualized by region and platform

---

## Key Insights

- **Spend and revenue are highly concentrated:** Most comes from UK, US, Singapore, Canada, Australia; top 10 campaigns drive most revenue.
- **Most daily campaigns are low-budget:** Only a few have very high spend.
- **Revenue consistently exceeds spend:** High efficiency (ROAS) in Australia, Singapore, Instagram.
- **Platform differences:** Instagram and Twitter deliver higher ROAS; Facebook has highest CTR; Google and LinkedIn lowest CPC.
- **Stable campaign delivery:** Impressions/clicks stable over time; reliable ad delivery and engagement.
- **Many paused or ended campaigns:** Opportunity to reactivate or reallocate budget.

---

## Recommendations

- **Reallocate budget** to high-performing regions (Australia, Singapore) and platforms (Instagram, Twitter).
- **Test increased budgets** in small, high-ROAS markets to check if returns scale.
- **Monitor and diagnose low-revenue days** or underperforming campaigns.
- **Review paused campaigns** for possible reactivation or lessons learned.
- **Focus optimization** on platforms and creatives driving high engagement and ROI.
- **Continue tracking efficiency metrics** (ROAS, CPC, CTR) for ongoing optimization.

---

## What I Learned

- End-to-end data cleaning and documentation in Excel and Python  
- Business-focused EDA and visualization (Storytelling with Data best practices)  
- Framing recommendations for marketing decision-makers  
- Translating messy, real-world data into clear, actionable insights

---

## Folder Structure

├── Raw_Data.xlsx
├── [Workbook]_Cleaned.xlsx
├── Issues_Log.xlsx
└── README.md

---

## Contact

For questions or feedback, please contact **Devin Richmond** at richmonddevin13@gmail.com.
