# Inventory Management Optimization Project

## Project Overview

This project simulates a real-world **inventory management and supply chain analytics system** built in Excel.  
The objective is to analyze product demand, classify inventory using **ABC–XYZ analysis**, and design optimized inventory policies using **Safety Stock, Reorder Point (ROP), and Economic Order Quantity (EOQ)**.

The project includes a dataset of **120 SKUs with 12 months of historical demand** and several operational and financial metrics used to evaluate inventory performance.

This project demonstrates how supply chain analysts can combine **data analysis, inventory optimization, and business KPIs** to improve inventory decision-making.

---

# Dataset Description

The dataset contains **120 products (SKUs)** and includes:

### Demand Data
- Monthly demand (Jan – Dec)
- Annual demand
- Demand variability

### Product Information
- Standard cost
- Unit price
- Lead time (days)

### Inventory Metrics
- Beginning inventory
- Ending inventory
- Average inventory

### Order Fulfillment Data
- Units ordered
- Units shipped
- Units sold
- Backorders

### Stockout Metrics
- Lost sales
- Units short
- Stockout events
- Stockout penalty cost
- Stockout cost

---

# Demand Analysis

## ABC Classification

Products are classified based on **revenue contribution**:

Revenue = Annual Demand × Unit Price

Classes:

- **A items** → High revenue contribution
- **B items** → Moderate revenue contribution
- **C items** → Low revenue contribution

This helps prioritize inventory management efforts.

---

## XYZ Analysis

Products are also classified based on **demand variability** using the **coefficient of variation (CV)**:

CV = Standard Deviation / Average Demand

Classes:

- **X** → Stable demand
- **Y** → Moderate variability
- **Z** → High demand variability

Combining ABC and XYZ allows better inventory strategies for different product types.

---

# Inventory Optimization

The project calculates key inventory parameters for each SKU.

### Safety Stock

Safety stock is calculated using:

SS = Z × σ × √LT

Where:

- Z = service level factor
- σ = demand standard deviation
- LT = lead time

---

### Reorder Point (ROP)

ROP = Demand During Lead Time + Safety Stock

This determines when a new order should be placed.

---

### Economic Order Quantity (EOQ)

EOQ determines the optimal order size:

EOQ = √((2DS)/H)

Where:

- D = annual demand
- S = ordering cost
- H = holding cost

---

# Financial Impact Analysis

The dashboard also evaluates the financial impact of inventory performance.

### Potential Revenue
Maximum possible revenue if all demand is satisfied.

Potential Revenue = Demand × Unit Price

### Real Revenue
Actual revenue generated from fulfilled orders.

Real Revenue = Units Sold × Unit Price

### Stockout Cost
Cost incurred due to stockouts.

Stockout Cost = Lost Sales × Stockout Penalty Cost

These metrics help quantify the business impact of inventory decisions.

---

# Dashboard KPIs

The dashboard includes key supply chain performance indicators:

- Potential Revenue
- Real Revenue
- Stockout Cost
- Lost Sales
- Inventory Value
- Revenue Capture Rate
- Top 10 SKUs by Potential Revenue
- ABC–XYZ product segmentation

---

# Tools Used

- Microsoft Excel
- Pivot Tables
- Inventory Management formulas
- Supply Chain Analytics techniques

---

# Project Objectives

This project demonstrates the ability to:

- Perform **demand analysis**
- Implement **ABC–XYZ inventory classification**
- Calculate **Safety Stock, ROP, and EOQ**
- Analyze **stockout impacts**
- Build an **inventory performance dashboard**
- Translate operational metrics into **financial insights**

---

# Author

This project was developed as part of a personal learning journey in **Supply Chain Analytics and Inventory Management**.