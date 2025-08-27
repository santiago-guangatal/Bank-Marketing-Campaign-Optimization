# Bank Marketing Campaign Optimization

This project analyzes a real-world dataset from a bank’s direct marketing campaigns.  
The goal is to understand customer profiles, evaluate channel and campaign effectiveness, and provide actionable recommendations to **increase term deposit subscriptions** while reducing marketing costs.

---

## Project Overview
- **Dataset**: The dataset used in this project comes from the **[Bank Marketing Dataset on Kaggle](https://www.kaggle.com/competitions/playground-series-s5e8/data)**.  
It contains customer demographic, financial, and campaign contact information used to study the likelihood of subscribing to a term deposit.
- **Objective**: The objective is to deliver actionable recommendations that help optimize future marketing strategies.
- **Key Steps**:
  1. Data collection & initial exploration  
  2. Data cleaning & preprocessing  
  3. Exploratory Data Analysis (EDA)  
  4. Data visualizations to address business questions  
  5. Insights, conclusions, and recommendations  

---

## Business Questions
1. **Customer Profiling**  
   - What demographic and financial characteristics (age, job, marital status, education, account balance, loans, etc.) distinguish customers who subscribed to a term deposit?  

2. **Channel & Campaign Effectiveness**  
   - Which communication channels (cellular, telephone, etc.) are most effective?  
   - Does prior contact history impact subscription likelihood?  
   - What is the best timing (month, day, recency of last contact) for contacting customers?  
   - How do call duration and frequency of contact affect success rates?  
   - How does the outcome of previous campaigns influence current results?  

---

## Tech Stack
- **Python**: Data analysis and visualization  
- **Libraries**:  
  - `numpy`, `pandas` → data manipulation  
  - `matplotlib` → data visualization  
  - `scipy` → chi-square tests and statistical analysis  

---

## Key Findings
- **Customer Profile**:  
  - Seniors, students, and retirees have the highest subscription rates.  
  - Singles, highly educated customers, and those with higher balances are more likely to subscribe.  
  - Customers with loans or defaults are less likely to convert.  

- **Channel & Campaign Effectiveness**:  
  - **Cellular contact** is more effective than telephone.  
  - Prior successful contact boosts conversion dramatically (up to 76%).  
  - Best months: **March, September, December**.  
  - Longer calls lead to higher conversion (calls >10min → 49% success).  
  - Fewer, well-timed contacts are more effective than repeated attempts.  

---

## Conclusions & Recommendations
1. **Targeting**: Focus on seniors, students, retirees, and financially stable customers without loans or defaults.  
2. **Channel**: Use mobile (cellular) as the primary communication channel.  
3. **Timing**: Concentrate efforts in March, September, and December; prioritize early-month calls.  
4. **Strategy**: Train agents to hold longer conversations and avoid over-contacting.  
5. **Lead Management**: Prioritize leads with positive outcomes in past campaigns.  

---
