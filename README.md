# Supply Chain Logistics Optimization for a Global Microchip Producer

## Overview

This project analyzes a real-world supply chain logistics network for a global microchip producer using Python. The dataset includes information about orders, warehouses, freight rates, and customer relationships. The goal is to provide insights into the supply chain network and optimize operations by reducing costs and improving efficiency. 

### Problem Statement

This project aims to analyze the supply chain logistics network for a global microchip producer, focusing on optimizing operations by reducing costs and improving efficiency. The analysis covers orders, warehouses, freight rates, and customer relationships, providing data-driven insights for strategic decision-making.

### Dataset Description

The data is sourced from a Microsoft Excel file, Supply chain logistics problem.xlsx, containing the following sheets:

- OrderList: Detailed information about customer orders, including the product, warehouse, carrier, weight, and destination port.
- FreightRates: Details about carriers, weight bands, shipping rates, modes of transport, and estimated transport days.
- WhCosts: Storage costs per unit for each warehouse.
- WhCapacities: Daily capacity constraints for each warehouse.
- PlantPorts: Mapping of warehouses (plants) to allowed shipping ports.
- ProductsPerPlant: List of products supported by each warehouse.
- VmiCustomers: Special warehouse-customer relationships.

### Analysis Approach

1. Exploratory Data Analysis (EDA): Understand the data structure, detect outliers, and identify key patterns.
2. Correlation Analysis: Examine relationships between shipment volumes, freight rates, and delays.
3. Heatmaps and Visualizations: Visualize shipment flows, carrier performance, and cost distributions.
4. Cost Optimization Analysis: Identify the most cost-effective carriers and routes based on weight range and service levels.
5. Delay Analysis: Assess delays by origin-destination pairs and carrier performance.

### Results

- Conducted a comprehensive analysis of the supply chain logistics data, highlighting inefficiencies and opportunities for improvement.
- Developed visualizations to better understand warehouse utilization, freight costs, and customer order patterns.
- Identified key drivers of high freight costs, including variability in carrier rates and weight bands.
- Found opportunities to balance warehouse loads by redistributing orders to underutilized facilities, which could potentially reduce operational bottlenecks.
- Highlighted customers with high order volumes, enabling targeted strategies for improving service levels and demand forecasting.

### Key Insights

The findings reveal that strategic adjustments, such as optimizing shipping routes, selecting cost-effective carriers, and balancing warehouse capacities, can reduce transportation costs and improve overall supply chain efficiency.

**High Shipment Volume with Minor Delays**:
- PORT04 → PORT09 is the most crucial route due to its high volume.
- Despite the minor average delay, the high volume suggests the potential for a larger cumulative impact on delivery timelines.
- Investigate potential causes for the delays, such as congestion, processing times, or carrier issues.

**Consistently On-Time Routes**:
- PORT09 → PORT09 and PORT05 → PORT09 are consistently on time.
- These routes are efficient but have low shipment volumes.
- Consider whether they can support additional volume to balance the load from more congested routes.

### Source:

https://www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
