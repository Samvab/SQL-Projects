# 🌍 International Debt Analysis — SQL Project

## Business Problem
Countries around the world take on debt from international creditors like the World Bank to fund 
infrastructure, development, and economic growth. But which countries carry the highest debt burden? 
Which debt indicators are most concentrated? This analysis answers these questions using real World 
Bank data to surface insights relevant to financial risk assessment and policy decision-making.

## Dataset
- **Source:** World Bank — International Debt Statistics
- **Size:** 124 countries, 2,357 records
- **Key Fields:** country_name, indicator_name, debt (USD)

## Business Questions Answered
1. What is the total global debt across all countries?
2. Which country has the highest total debt?
3. What is the average debt per debt indicator?
4. Which countries have the highest number of distinct debt indicators?
5. Which debt indicator has the highest total debt globally?
6. What are the top 10 most indebted countries?
7. Which country has the lowest repayment amount?

## Tools Used
- SQL (PostgreSQL / SQLite)
- Python (Pandas, Jupyter Notebook)

## Key Findings
- Total global debt in the dataset exceeds **$3 trillion USD**
- **China** holds the highest total debt among all countries
- The most concentrated debt indicator globally is **long-term debt (DT.AMT.DLXF.CD)**
- Top 10 countries account for over **60% of total recorded debt**
- Several low-income nations appear across **20+ debt indicators**, signalling high financial dependency

## Business Recommendations
- Lenders should flag countries with high indicator diversity as higher risk — they are borrowing 
  across multiple channels simultaneously
- Debt concentration in long-term indicators suggests refinancing risk if interest rates rise
- Policy makers should prioritise debt relief programs for countries appearing in both high-volume 
  and high-indicator-count segments

