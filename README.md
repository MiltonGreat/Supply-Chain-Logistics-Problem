# Supply Chain Logistics Analysis

## Overview

This project analyzes a real-world supply chain logistics network for a global microchip producer using Python. The dataset includes information about orders, warehouses, freight rates, and customer relationships. The goal is to provide insights into the supply chain network and optimize operations by reducing costs and improving efficiency. 

### Problem Statement

Global supply chains face inefficiencies that increase costs and disrupt operations. This project focuses on analyzing the logistics network of a microchip producer to identify areas for cost reduction and operational improvement.


### Dataset Description

The data is sourced from a Microsoft Excel file, Supply chain logistics problem.xlsx, containing the following sheets:

- OrderList: Detailed information about customer orders, including the product, warehouse, carrier, weight, and destination port.
- FreightRates: Details about carriers, weight bands, shipping rates, modes of transport, and estimated transport days.
- WhCosts: Storage costs per unit for each warehouse.
- WhCapacities: Daily capacity constraints for each warehouse.
- PlantPorts: Mapping of warehouses (plants) to allowed shipping ports.
- ProductsPerPlant: List of products supported by each warehouse.
- VmiCustomers: Special warehouse-customer relationships.

### Solution Approach

EDA helps understand the data distribution and uncover key insights. Visualizations include:

- Orders by Warehouse: Number of orders processed by each warehouse.
- Service Levels: Distribution of service levels (e.g., Door-to-Door, Door-to-Port).
- Shipping Modes: Frequency of air vs. ground shipments.
- Order Weights: Distribution of order weights.
- Freight Rates by Carrier: Variability in shipping rates among carriers.
- Warehouse Capacities: Utilization levels of warehouse capacities.
- Customer Distribution: Top customers by number of orders.
- Products Supported by Warehouse: Number of products each warehouse stocks.

### Results

- Conducted a comprehensive analysis of the supply chain logistics data, highlighting inefficiencies and opportunities for improvement.
- Developed visualizations to better understand warehouse utilization, freight costs, and customer order patterns.
- Identified key drivers of high freight costs, including variability in carrier rates and weight bands.
- Found opportunities to balance warehouse loads by redistributing orders to underutilized facilities, which could potentially reduce operational bottlenecks.
- Highlighted customers with high order volumes, enabling targeted strategies for improving service levels and demand forecasting.

### Key Insights

- Freight Cost Variability: Analysis revealed significant cost differences among carriers and weight bands, underscoring the importance of rate negotiations and carrier selection for cost efficiency.
- Warehouse Utilization: Some warehouses operate close to capacity, indicating a need for load balancing and possibly expanding storage capacity in key locations.
- Service Level Optimization: Understanding the distribution of service levels (e.g., Door-to-Door vs. Door-to-Port) can inform decisions about when to use costlier premium services.
- Customer Order Patterns: Identifying top customers by order volume provides actionable insights for better inventory allocation and prioritization.
- Product-Warehouse Mapping: Evaluating the alignment of products to warehouses can improve fulfillment efficiency and reduce lead times.

### Future Directions

- Extend the analysis to include real-time tracking data for dynamic optimization.
- Incorporate demand forecasting to improve inventory planning.

### Source:

https://www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
