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
The three sales strategies that were analysed: 
<div>
<img width="549" height="265" alt="image" src="https://github.com/user-attachments/assets/8dd63ec5-b60a-4ef6-828a-e494cabb7760" />
</div>
<br><br>


<div>
<img width="450" height="600" alt="image" src="https://github.com/user-attachments/assets/1c59a459-a0ba-48c2-83e4-69604f17219e" />
<img width="450" height="600" alt="image" src="https://github.com/user-attachments/assets/3bed9c37-ddbf-4994-b73b-ab399653d7a8" />
</div>


- While 'Email' Initially attracts the most customers, it is likely not suitable for maintaining sufficient numbers long-term.
- The combined approach may be better for maintaining high revenue long-term



### Proposed metric for quantification of success:
**Effectve Revenue per Contact Minute (ERCM)**
<br><br>
$$𝐸𝑅𝐶𝑀 =𝐶𝑜𝑛𝑣𝑒𝑟𝑠𝑖𝑜𝑛  𝑅𝑎𝑡𝑒×𝑅𝑒𝑣𝑒𝑛𝑢𝑒/(𝐶𝑜𝑛𝑡𝑎𝑐𝑡 𝑀𝑖𝑛𝑢𝑡𝑒𝑠)$$<br><br>
<img width="450" height="512" alt="image" src="https://github.com/user-attachments/assets/299892dc-8470-4d0f-b1fc-ec709625bba0" />

<br><br>
- The combined Email and Call **generated higher revenue per customer** and larger quantities of item sales per purchase.
- Modeling the Effective Revenue per Contact Minutes (ERCM) revealed that 'Email + Call' is likely to have the **highest return on investment**.
- Calls have the **lowest return on investment** abd take the longest time.
- Emails without a follow-up call saw an initial spike in total revenue, but rapidly decreased across the 6 weeks. **Medium return on investment**

## Business Recommendations
- Focus sales efforts on 'Email' and 'Email + Call' strategies, and abandon the 'Call' strategy for the next six weeks
- All **Contact minutes per customer** should be documented at time of contact from now on, regardless of whether a purchase was made or not.
- Analyse **real ERCM** values with the **next 6 weeks** to conclude which sales strategy is most effective.
