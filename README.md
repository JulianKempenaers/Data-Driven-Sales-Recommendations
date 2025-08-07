# Data Driven Sales Recommendations

### Goal
Develop and model a new metric to evaluate the effectiveness of three sales strategies.

### :hammer_and_wrench: Tools & Skills
- R (data analysis, statistics, visualisation, cleaning)
- Jupyter lab for interactive report generation

### :bookmark_tabs: Full Report
[The full Sales Effectiveness Analysis **report can be found here**](notebook.ipynb)

---

## :memo: Key findings
<img src="/Figures/fig1.png" alt="New metric for measuring sales method efficacy" width="900" />

<img src="/Figures/fig2.png" alt="Key findings" width="900" />

- The combined Email and Call **generated higher revenue per customer** and larger quantities of item sales per purchase.
- Modeling the Effective Revenue per Contact Minutes (ERCM) revealed that 'Email + Call' is likely to have the **highest return on investment**.
- Calls have the **lowest return on investment** abd take the longest time.
- Emails without a follow-up call saw an initial spike in total revenue, but rapidly decreased across the 6 weeks. **Medium return on investment**

## Business Recommendations
- Focus sales efforts on 'Email' and 'Email + Call' strategies, and abandon the 'Call' strategy for the next six weeks
- All **Contact minutes per customer** should be documented at time of contact from now on, regardless of whether a purchase was made or not.
- Analyse **real ERCM** values with the **next 6 weeks** to conclude which sales strategy is most effective.
