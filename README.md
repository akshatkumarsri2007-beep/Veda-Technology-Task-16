# Veda-Technology-Task-16
#  Simple Profit Analysis — Superstore Dataset

A beginner-friendly data analytics project comparing **total profit across product categories** (Furniture, Office Supplies, and Technology) using Microsoft Excel.

>  **Task 16** — Data Analytics Track, Veda Technology Internship
>  Prepared by: **Akshat Srivastava**

---

##  Objective

To compare total profit across product categories and understand basic profitability using a Superstore-style sales dataset.

##  Dataset

The dataset contains order-level sales records with the following key columns:

| Column | Description |
|---|---|
| `Order ID` | Unique identifier for each order |
| `Order Date` | Date the order was placed |
| `Region` | Sales region |
| `Category` | Product category (Furniture, Office Supplies, Technology) |
| `Sub-Category` | Product sub-category |
| `Quantity` | Units sold |
| `Discount` | Discount applied |
| `Sales` | Total sales value |
| `Profit` | Profit earned |

##  Tools Used

- **Microsoft Excel**
  - Excel Tables
  - PivotTables
  - PivotCharts
  - SUMIFS / AVERAGEIFS formulas

##  Methodology

1. Converted the raw data into an Excel Table for easier analysis.
2. Built a **PivotTable** grouping all orders by `Category`.
3. Calculated for each category:
   - Total Sales
   - Total Profit
   - Average Profit per Order
   - Profit Margin (Total Profit ÷ Total Sales)
4. Created a **PivotChart** to visually compare Sales vs Profit across categories.

##  Results

| Category | Total Sales (Rs.) | Total Profit (Rs.) | Avg. Profit/Order (Rs.) | Profit Margin |
|---|---|---|---|---|
| Furniture | 57,282.80 | 2,377.90 | 26.72 | 4.2% |
| Office Supplies | 20,639.32 | 4,047.76 | 40.48 | 19.6% |
| Technology | 1,01,513.90 | 13,492.42 | 121.55 | 13.3% |
| **Grand Total** | **1,79,436.02** | **19,918.08** | **66.39** | **11.1%** |

##  Key Insights

-  **Technology** is the most profitable category — highest total profit (Rs. 13,492) and highest average profit per order (Rs. 121.55), driven by strong sales volume.
-  **Office Supplies** has the best **profit margin** (19.6%) — it earns proportionally more profit per rupee of sales than any other category.
-  **Furniture** underperforms — despite decent sales (Rs. 57,283), it generates the lowest profit and the lowest average profit per order, suggesting pricing or discounting issues.
- Overall store profit margin stands at **11.1%** across Rs. 1,79,436 in total sales.

##  Conclusion

Technology drives the highest profit and profit-per-order, Office Supplies offers the best margin efficiency, while Furniture underperforms despite strong sales. Focusing on improving Furniture's pricing or discount strategy could help raise its profitability.

##  Repository Contents

```
├── Superstore_Dataset.xlsx           # Raw dataset
├── Simple_Profit_Analysis.xlsx       # PivotTable + PivotChart analysis
├── Simple_Profit_Analysis_Report.pdf # Final report (summary + insights)
└── README.md                         # Project overview (this file)
```
