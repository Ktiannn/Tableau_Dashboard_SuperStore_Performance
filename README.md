# Tableau Dashboard SuperStore Performance
This project was developed as a team collaboration. I was specifically responsible for Overview Dashboard and Sales & Profit Dashboard, while my teammates focused on Category Dashboard.
## Project Overview
  This project analyzes the **"Superstore Dataset"** (5,000 orders, 2014–2017) using **Tableau** to identify growth drivers and profitability leaks. The goal is to evaluate sales trends and provide actionable strategies for profit improvement.

## Highlights
  Based on my findings, the key findings of this report are structured into two major highlights, each derived from our two Tableau dashboards: Overview Dashboard and Sales & Profit Dashboard.

### **1. Overview Dashboard Analysis**
  
 * **KPIs:** Sales grew steadily from **$483k (2014) to $728k (2017)**. However, a **declining AOV (Average Order Value)** suggests growth is driven by sheer volume rather than value—a potential long-term risk.

 * **"High Sales,Low Profit"Pattern:** Copiers are the efficiency leaders ($49k sales / $17k profit), while Tables are the primary loss-maker (deep red). Phones and Chairs exhibit a "High Sales, Low Profit" pattern, likely due to excessive discounting.

 * **Over-Dependence:** Extreme dependence on California, New York, and Texas creates vulnerability. Expanding market penetration in mid-tier states is recommended.

<details>
  <summary>Click to view Overview Dashboard</summary>
  <br>
  <img src="./img/My_Dashboard_1_Overview.png" width="600">
</details>

### **2. Sales & Profit Dashboard Analysis**

  * **The 20% Profitability Red Line:** Profitability remains stable only when discounts are below 20%. Beyond this threshold, profit margins collapse, particularly in the "Over 50%" bracket.

  * **Concentration of Losses:** High-discount orders are heavily clustered in the "Loss Zone" (below the 0% profit line), proving that excessive discounting is the primary driver of systematic losses.

<details>
  <summary>Click to view Sales & Profit Dashboard</summary>
  <br>
  <img src="./img/My_Dashboard_2_Sales_Profit.png" width="600">
</details>
  
  Created a "TOP/BOTTOM 5" filters, after we enable this filter we clearly identified the stark gap between the best and worst-performing states.

* **Profit Leaders:** California and New York remain our strongest markets, maintaining high profitability with average discounts of only 10-15%.

* **Loss-making "Red Zones":** In contrast, states such as Texas, Ohio, and Pennsylvania suffer the heaviest losses, The most loss-making cities have average discounts exceeding 40%.

**Strategic Risk:** We are currently "buying sales" at a significant loss in these Bottom 5 states. We recommend an immediate 20% discount cap for these "Red Zone" cities and a re-evaluation of pricing strategies for low-margin sub-categories.

<details>
  <summary>Click to view After "TOP/BOTTOM 5" filters is ON and Top/Bottom State Performance</summary>
  <br>
  
  <img src="./img/My_Dashboard_2_Sales_TopBottom5.png" width="600">

  #### Top State (California) Performance 
  <img src="./img/My_Dashboard_2_Sales_California.png" width="600">

  #### Bottom State (Texas) Performance
  <img src="./img/My_Dashboard_2_Sales_Texas.png" width="600">

  </details>
  
---

### Quick Links
* [**Read Final Report (PDF)**](./SuperStore_Analysis_Report.pdf)
* [**Full SuperStore Dashboard (TWBX)**](./SuperStore_Analysis_Full_Project.twbx)
* [**Raw Dataset (CSV)**](./Sample_Superstore_final.csv)
