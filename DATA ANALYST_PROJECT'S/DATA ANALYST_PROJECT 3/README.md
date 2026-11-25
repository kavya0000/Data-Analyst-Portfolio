**#### Financial Data Analysis \& Forecasting**



**\*\*Financial Analytics | Project 3\*\* | \*\*Analyst:\*\* Poleboina Kavya **



**#### Project overview**



**This project explores investor behavior, portfolio preferences, and savings objectives using financial survey data (Finance\_data.csv). The notebook validates data completeness, ranks preferred investment avenues, applies forecasting techniques, and builds an interactive Plotly Dash dashboard to communicate financial insights. **



**#### Dataset**



**\* \*\*File:\*\* Finance\_data.csv (40 investor records, 24 columns)**

**\* \*\*Key Fields:\*\* gender, age, Investment\_Avenues, Mutual\_Funds, Equity\_Market, Debentures, Government\_Bonds, Fixed\_Deposits, PPF, Gold, Objective, Purpose, Duration, Invest\_Monitor, Expect, Source**



**#### Tech stack**



**Python, pandas, NumPy, Matplotlib, Seaborn, Plotly Dash, scikit-learn, Google Colab / Jupyter Notebook **



**#### What the notebook does**



**StepWhat was done**

**\*\*1. Data cleaning\*\***

**Verified 40 rows and 24 columns with 0 missing values and 0 duplicate records**

**\*\*2. Trend analysis (EDA)\*\***

**Aggregated total investment scores across 7 avenues and segmented preferences by age, gender, and duration**

**\*\*3. Data visualization\*\***

**Created 5 comparative charts highlighting avenue popularity, return expectations, and investor demographics**

**\*\*4. Forecasting\*\***

**Modeled projected investment trends based on historical allocation patterns**

**\*\*5. Interactive dashboard\*\***

**Built an interactive web dashboard using Plotly Dash for dynamic exploration**

**\*\*6. Insights generation\*\***

**Summarized overall portfolio health ($1,120.00 total / $28.00 average per respondent) and top asset classes**



**#### Results: investment avenue rankings**



**RankInvestment AvenueTotal Score / Allocation**

**\*\*1\*\***

**\*\*Gold\*\*239**

**\*\*2\*\***

**\*\*Debentures\*\*230**

**\*\*3\*\***

**\*\*Government Bonds\*\*186**

**\*\*4\*\***

**\*\*Fixed Deposits\*\*143**

**\*\*5\*\***

**\*\*Equity Market\*\*139**

**\*\*6\*\***

**\*\*Mutual Funds\*\*102**

**\*\*7\*\***

**\*\*PPF (Public Provident Fund)\*\*81**



**#### Key decisions and why**



**\* \*\*Complete-case verification:\*\* Confirmed 0 nulls and 0 duplicates across all 24 survey attributes before computing avenue totals so every respondent carried equal weight.**

**\* \*\*Comparing fixed-income vs. market-linked assets:\*\* Ranking traditional safe-haven assets (Gold: 239, Debentures: 230, Government Bonds: 186) alongside Equity (139) and Mutual Funds (102) clearly highlights investor risk aversion.**

**\* \*\*Interactive Dash integration:\*\* Paired static notebook charts with a Plotly Dash layout so stakeholders can filter investment behavior interactively.**



**#### Screenshots**



**\*\*Chart 1 — Investment Avenue Comparison:\*\***

** **



**\*\*Chart 2 — Investor Demographics \& Preferences:\*\***

** **



**\*\*Chart 3 — Savings Objectives \& Expected Returns:\*\***

** **



**\*\*Chart 4 — Financial Trend \& Forecasting Output:\*\***

** **



**\*\*Chart 5 — Portfolio Distribution Summary:\*\***

** **



**#### Files in this folder**



**\* FINANCIAL\_DATA\_ANALYSIS\_\&\_FORECASTING.ipynb: complete notebook with EDA, forecasting, and Dash dashboard code**

**\* FINANCIAL DATA ANALYSIS \& FORECASTING.ipynb - Colab.pdf: exported PDF report of the executed notebook**

**\* Finance\_data.csv: raw financial survey dataset**

**\* screenshots/: extracted chart images (chart\_1.png – chart\_5.png)**



**#### How to run**



**1. Install the libraries: pip install pandas numpy matplotlib seaborn scikit-learn dash jupyter**

**2. Keep Finance\_data.csv in the same folder as FINANCIAL\_DATA\_ANALYSIS\_\&\_FORECASTING.ipynb.**

**3. Open FINANCIAL\_DATA\_ANALYSIS\_\&\_FORECASTING.ipynb in Jupyter Notebook or Google Colab and choose \*\*Run All\*\*.**

