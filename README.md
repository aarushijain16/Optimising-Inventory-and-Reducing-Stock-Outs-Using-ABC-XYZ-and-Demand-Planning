# Optimising Inventory and Reducing Stock-Outs Using ABC-XYZ and Demand Planning
### Inventory Classification · Safety Stock Modelling · Working Capital Analysis
### SQL (PostgreSQL) · Python · Power BI · ABC-XYZ · Reorder Point Optimisation

---

## Overview

This project builds an end-to-end inventory optimisation framework 
for a multi-category retail business - identifying cash trapped in 
excess inventory, revenue lost to stock-outs, and the optimal 
replenishment logic to balance service levels against holding costs.

Using the publicly available Maven Superstore dataset, I applied 
ABC-XYZ segmentation, safety stock modelling, and reorder point 
calculations to surface the working capital and profit optimisation 
case for a full inventory strategy overhaul.

**Tools:** SQL (PostgreSQL) · Python (Pandas, NumPy) · Power BI · 
ABC-XYZ Analysis · Safety Stock Modelling · Feature Engineering

---

## Business Problem

Retail businesses consistently face the same inventory paradox: 
too much of the wrong stock and not enough of the right stock - 
simultaneously.

Key questions this project addresses:

- Which SKUs are cash traps vs. genuine profit drivers?
- How much revenue is being lost to stock-outs on high-value products?
- Where can safety stock be reduced without hurting service levels?
- How can replenishment decisions be made systematically 
  rather than reactively?

---

## Analytical Approach

**Inventory Classification: ABC-XYZ Matrix**
- ABC analysis by revenue and cost contribution
- XYZ analysis based on demand variability
- Combined ABC-XYZ 9-box matrix to prioritise 
  replenishment decisions by segment

**Replenishment & Risk Modelling**
- Safety stock calculations by SKU using demand variability
- Reorder point modelling based on lead-time demand
- Fill-rate and service-level evaluation by category

**Inventory Health & Leakage Analysis**
- Excess, slow-moving, and dead stock identification
- Stock-out days and lost sales estimation by category
- Inventory turnover and days-of-supply analysis
- Return-rate analysis by product category

**Executive Reporting**
- Power BI dashboard translating inventory analytics 
  into operational decisions for business teams

---

## Key Findings

**~98% of SKUs classified as slow-moving or dead stock**
ABC-XYZ segmentation revealed that the vast majority of SKUs 
contributed negligible revenue while consuming inventory capital. 
A small AX segment (high revenue, low variability) drove most 
of the commercial value - meaning replenishment priority and 
working capital should be heavily concentrated in this segment.

**Technology category identified as highest stock-out risk**
Stock-out analysis revealed the Technology category had the 
most significant lost-sales exposure due to inadequate safety 
stock relative to demand variability. This is the highest-impact 
category for immediate replenishment policy change.

**Excess and aged inventory concentrated in identifiable SKUs**
Dead stock and slow-moving inventory were not evenly distributed - 
they clustered in specific categories and SKUs that can be 
systematically targeted for clearance or discontinuation, 
freeing working capital without broad policy changes.

**Top 10 products drive disproportionate profit contribution**
Pareto analysis confirmed heavy revenue and profit concentration 
in a small number of SKUs - creating both a zero-stockout 
imperative for those items and a rationalisation opportunity 
for the long tail.

---

## Modelled Business Impact

*Financial impacts are modelled estimates based on the public 
Maven Superstore dataset, scaled using industry benchmarks 
to reflect real-world retail economics.*

| Finding | Modelled Impact |
|---|---|
| ~98% slow/dead stock - AX segment prioritisation | ~$10M+ working capital release potential |
| Technology category stock-out losses | ~$15M+ in modelled lost revenue |
| Excess and aged inventory identified | ~$10M+ cash recovery via clearance |
| Holding cost reduction from inventory rationalisation | ~$5M+ annual saving potential |

---

## Strategic Recommendations

- Implement ABC-XYZ classification as the foundation 
  for all weekly inventory review decisions
- Protect AX products with higher service levels and 
  dedicated safety stock buffers
- Reduce safety stock on CZ/BZ SKUs where demand 
  variability is low and revenue contribution is minimal
- Run quarterly clearance cycles targeting dead and 
  slow-moving stock to recover working capital
- Integrate reorder point alerts and safety stock 
  thresholds into ERP or inventory management systems
- Monitor inventory health weekly via Power BI dashboard - 
  turnover, days of supply, stock-out risk by category

---

## Tools & Technologies

| Tool | Usage |
|---|---|
| SQL (PostgreSQL) | ABC-XYZ classification, stock-out analysis, inventory metrics |
| Python (Pandas, NumPy) | Safety stock modelling, reorder point calculations, EDA |
| Power BI | Executive inventory health dashboard |
| Feature Engineering | Star schema, demand variability scoring, synthetic assumptions |

---

## Dataset Note

This analysis uses the publicly available Maven Superstore dataset. 
All financial impacts are modelled estimates - not real business 
outcomes. The methodology and framework directly reflect real-world 
retail inventory analytics practice.

---

*Part of the E-Commerce & Supply Chain Analytics Portfolio*
*[View full portfolio](https://aarushijain16.github.io/sales-demand-customer-growth-portfolio/)*
