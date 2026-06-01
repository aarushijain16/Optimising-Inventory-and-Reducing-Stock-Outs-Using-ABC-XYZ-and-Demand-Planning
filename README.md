# Optimising Inventory and Reducing Stock-Outs Using ABC-XYZ and Demand Planning

# Overview
This project demonstrates how sales and demand-driven inventory analytics can reduce holding costs, prevent stock-outs, and improve cash flow for retail businesses,

Using **SQL, Python, and Power BI,** I built an end-to-end inventory optimisation framework that identifies:

- Cash trapped in excess inventory

- Revenue lost due to stock-outs

- Products that truly drive profitability

- Optimal safety stock and reorder levels

The approach mirrors real-world retail challenges faced by supermarkets, D2C brands, and multi-category retailers.

# Business Problem

Retail businesses often struggle with:

- Excess inventory tying up working capital

- Frequent stock-outs on high-value products

- Poor visibility into which SKUs actually drive profit

- High holding and return costs eroding margins

The key questions addressed:

- Which products are cash traps vs. profit drivers?

- How much revenue is lost due to stock-outs?

- Where can safety stock be reduced without hurting service levels?

- How can inventory decisions directly improve cash flow and profitability?

# Solution Approach

I designed a data-driven inventory planning framework using retail transaction data:

**🔹 Inventory Classification**

- ABC analysis by revenue and cost
- XYZ analysis based on demand variability
- ABC-XYZ 9-box matrix to prioritise replenishment decisions

**🔹 Replenishment and Risk Modeling**

- Safety stock and reorder point calculations
- Lead-time demand analysis
- Fill-rate and service-level evaluation

**🔹 Inventory Health and Leakage Analysis**

 - Excess, slow-moving, and dead stock identification
 - Stock-out days and lost sales estimation
 - Inventory turnover and days-of-supply analysis
 - Return-rate analysis by category

**🔹 Executive Reporting**

- Built a Power BI dashboard translating analytics into actionable business insights

# Key Business Insights and Impact

*(Estimated financial impact scaled to large retail operations)*

- 98% of SKUs were slow or dead stock, while a small AX segment drove most revenue
  → Prioritizing AX items could free $10–25M in working capital

- Technology category lost $15-30M in sales due to stock-outs
  → Adjusting safety stock recovered $10-20M in revenue

- Excess and aged inventory worth $10-25M identified
  → Clearance and discontinuation enabled #3-10M cash recovery

- Top 10 products generated 30-40% of total profit
  → Ensuring zero stock-outs drove 20-30% profit growth

- Annual holding costs estimated at $20-45M
  → Reducing excess inventory saved $5-15M annually

# Strategic Recommendations

- Implement ABC-XYZ classification for weekly inventory reviews

- Protect high-value AX products with higher service levels

- Reduce safety stock on low-risk, low-velocity SKUs

- Run quarterly clearance cycles for slow and dead stock

- Integrate safety stock and reorder alerts into ERP systems

- Use Power BI dashboards for ongoing executive monitoring

# Tools and Technologies

- Python (Pandas, NumPy)

- PostgreSQL (Supabase)

- SQL (window functions, percentiles, aggregations)

- Power BI

- Data Engineering: Star schema, feature engineering, synthetic assumptions

# Why this Matters for Your Business

This project shows how inventory analytics can:

- Free trapped cash

- Reduce operational risk

- Recover lost revenue

- Turn inventory from a cost center into a profit driver

The same framework can be adapted for:

- Retail chains

- E-Commerce Platforms

- D2C brands

- Multi-warehouse operations

# 📌 Note
This analysis uses the publicly available Maven Superstore dataset. Financial impacts are estimated using industry-standard benchmarks to reflect real-world retail scale.

# 💬 How this helps you as a client
If you are facing:

- Overstocking

- Stock-outs

- Poor inventory visibility

- Margin pressure

I can adapt this approach to your real data and deliver:

- SQL models

- Python analysis

- Power BI dashboards

- Clear, actionable recommendations
