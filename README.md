# NASDAQ-100 Sectorial Comparative Analysis
**A Strategic Assessment of Profitability and Financial Resilience**
## 🔗 Live Dashboard
**[View the Interactive Tableau Dashboard here](https://public.tableau.com/views/NasdaqJuxtaposeAnalysis/Story1?:language=en-GB&:sid=&:display_count=n&:origin=viz_share_link)**

## 1. Project Objective
This project analyzes facets of the aggregate financial well-being of NASDAQ-100 constituents. It makes a sector-level juxtaposition of current and projected performance of the index constituents through the lenses of considerations such as profitability, solvency, and liquidity.


## 2. Dataset & Limitations
* **Source:** [NASDAQ-100 Fundamental Data](https://www.kaggle.com/datasets/ifuurh/nasdaq100-fundamental-data) (via Oliver Hennhöfer).
* **Scope:** 45 financial metrics/ratios for all constituents as of 09/2023.
* **Limitations:* **Metric Scope:** Visualized outcomes are bound by the specific ratio availability within the raw source.
    * **Static View:** The analysis is a point-in-time snapshot and does not account for subsequent market volatility or interest rate pivots.
    

## 3. Methodology
* **Refinement:** Standardized company-level metrics and adjusted specific ratios in Excel to better isolate sector-wide trends.
* **Aggregation:** Grouped entities by sector and sub-sector to assess systemic performance rather than idiosyncratic movements.
* **Analysis Lenses:**
    1.  **Profitability:** Comparing 2023 Gross Profit/Assets vs. Yacktman Forward Rates of Return.
    2.  **Obligation Coverage:** Assessing the inverse relationship between the **Cash Ratio** (Liquidity) and **Debt-to-Equity** (Solvency).


## 4. Key Insights

### I. Inverted Leadership: Solvency vs. Liquidity
Analysis reveals an "Inverted Leadership" pattern. **Health Care** leads the index in liquidity (highest Cash Ratios), yet **Communication Services** demonstrates superior solvency (Debt-to-Equity profile). This suggests that while Health Care is "cash-rich," Communication Services possesses a more resilient long-term capital structure.

### II. Projected Mean Reversion
Sectors that dominated 2023 profitability (e.g., Information Technology) show a decelerating trend in **Projected Forward Returns**. Conversely, sectors like **Industrials** exhibit improving future return profiles, signaling a potential rotation away from "peak-cycle" leaders.

### III. Concentration Risk
While **Communication Services** appears solvent at an aggregate level, the drill-down analysis highlights that this strength is heavily concentrated in a few sub-sector giants, rather than being a broad-based sector characteristic.


## 5. Technical Stack
* **Visualization:** Tableau Public
* **Transformation and Optimization:** Excel
* **Documentation:** GitHub.



---
      
