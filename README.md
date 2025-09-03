<img width="2196" height="1234" alt="CHIKA POWERBI PROJECT 1" src="https://github.com/user-attachments/assets/b03e3be0-35d3-4dc0-bbed-8845f7b08faf" />
# Inventory-Optimization-Analysis
This project analyzes stock inflows,outflows, and balances across multiple retail stores using data from the Inventory transactions table.

## Executive Summary

This project analyzes stock inflows, outflows, and balances across multiple retail stores using the Inventory Transactions dataset.

## Key Findings:

* Kano store received the highest inflow of Beans.

* Rice is the most frequently moved product with the highest movement ratio.

* Beans show risk of stockouts in some months.

Seasonal trends strongly affect inventory levels.

By leveraging Power BI visuals and DAX measures, management can make informed decisions, avoid under/overstocking, and improve operational efficiency.

## Business Understanding

Challenge: Inefficient inventory distribution across stores.

Goals:

Reduce carrying costs

Minimize overstocking and understocking

Improve profitability through optimized stock management

Why It Matters:
Inventory optimization ensures products are available when needed without tying up too much capital in excess stock.

## Data Understanding

Source: Inventory Transactions Table

Key Fields: Date, Store, Product, Quantity In, Quantity Out, Unit Price

Coverage: Multiple months across all stores

## Data Cleaning Steps:

Removed null values

Standardized product names

Ensured proper date formatting

## Methodology

Imported dataset into Power BI

Cleaned data using Power Query

Created calculated columns & DAX measures:

Net Stock = In – Out

Movement Ratio = Out ÷ In

Built visuals: bar charts, matrices, slicers

Applied filters for store-level analysis

## Insights

Kano Store: Top receiver of Beans inflow

Rice: Highest movement ratio → needs constant monitoring

Beans: Risk of stockouts during peak demand months

Seasonality: Inventory trends fluctuate across periods

## Recommendations

Monitor high-movement products (Rice) closely.

Create stockout alerts for Beans.

Adjust stock levels dynamically based on seasonal patterns.

Optimize store-specific supply to reduce carrying costs and prevent shortages.

## Conclusion

This analysis provided actionable insights into product inflows, outflows, and stock balances across multiple stores. The findings demonstrate how management can reduce inefficiencies, prevent stockouts of high-demand products such as Beans and Rice, and optimize supply through better redistribution and procurement strategies. Moving forward, the next steps include integrating live transaction data for real-time monitoring, automating replenishment alerts within Power BI, and refining predictive models to ensure stock levels remain aligned with seasonal demand.
