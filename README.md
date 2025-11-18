# Gun Background Checks & Census Analysis

This project explores patterns in US gun background checks using NICS data merged with state-level census information. The aim is to understand how background check activity varies across states, how it has changed over time, and which demographic or economic factors are associated with higher gun-check rates.

## 🔍 Project Overview

The analysis focuses on three key questions:

1. **Which census characteristics are most associated with high gun checks per capita?**
2. **Which states experienced the highest growth in background checks from 2016 to 2017?**
3. **What is the overall national trend in gun background checks over time?**

The project includes data wrangling, exploratory data analysis (EDA), and statistical summaries using Python.

## 🗂 Data Sources

- **NICS Firearm Background Check Data**  
  Monthly state-level background checks (handgun, long-gun, permit and total checks).

- **US Census State Characteristics**  
  State-level demographic and economic variables such as income, poverty, disability, housing costs, population density and more.

The datasets were cleaned and merged into a single analytical table at the state–month level.

## 📈 Key Findings

- National background checks increased by **56.9%** from **2016 to 2017**.  
- **Kentucky** showed the largest increase in both relative and absolute terms.  
- Higher gun checks per capita are weakly associated with **higher poverty**, **higher disability rates**, and a **larger white population share**.  
- Lower gun-check rates tend to occur in states with **higher income**, **higher housing costs**, **greater population density**, and **more diverse populations**.
