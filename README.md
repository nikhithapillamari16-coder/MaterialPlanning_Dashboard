# MaterialPlanning_Dashboard
📊Overview
Inventory Optimization Dashboard built in Power BI to monitor stock levels, supplier performance, and identify stockout risks for proactive material planning.

🎯Objective
The goal of this project is to:
Monitor inventory health
Identify potential stockout risks
Improve supplier coordination
Support proactive material planning

Key Features
📦 Inventory Tracking: Monitor inventory levels across SKUs
⚠️ Stock Risk Identification: Flag items as At Risk or Healthy using coverage vs lead time logic
📈 Supplier Analysis: Analyze inventory distribution by supplier
📊 Open PO Monitoring: Track open purchase orders for better procurement visibility
🎯 KPI Metrics:
Total Inventory Value
Total Open PO Quantity
Inventory Health Distribution

🛠️ Tools & Technologies
Power BI
Excel
DAX

⚙️ Logic Used
🔹 Coverage-Based Risk Analysis
Stock Coverage Days = Inventory Quantity ÷ Daily Demand
Daily Demand = Monthly Demand ÷ 30

👉 If:
Stock Coverage Days < Lead Time → At Risk
Stock Coverage Days ≥ Lead Time → Healthy

This approach helps determine whether current inventory can sustain demand until the next replenishment.
