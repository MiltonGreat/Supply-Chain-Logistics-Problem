# Supply Chain Logistics Analysis

### Overview

This project analyzes a real-world supply chain logistics network for a global microchip producer using Python. The dataset includes information about orders, warehouses, freight rates, and customer relationships. The goal is to provide insights into the supply chain network and optimize operations by reducing costs and improving efficiency. 

### Dataset Description

The data is sourced from a Microsoft Excel file, Supply chain logistics problem.xlsx, containing the following sheets:

- OrderList: Detailed information about customer orders, including the product, warehouse, carrier, weight, and destination port.
- FreightRates: Details about carriers, weight bands, shipping rates, modes of transport, and estimated transport days.
- WhCosts: Storage costs per unit for each warehouse.
- WhCapacities: Daily capacity constraints for each warehouse.
- PlantPorts: Mapping of warehouses (plants) to allowed shipping ports.
- ProductsPerPlant: List of products supported by each warehouse.
- VmiCustomers: Special warehouse-customer relationships.

### Exploratory Data Analysis (EDA)

EDA helps understand the data distribution and uncover key insights. Visualizations include:

- Orders by Warehouse: Number of orders processed by each warehouse.
- Service Levels: Distribution of service levels (e.g., Door-to-Door, Door-to-Port).
- Shipping Modes: Frequency of air vs. ground shipments.
- Order Weights: Distribution of order weights.
- Freight Rates by Carrier: Variability in shipping rates among carriers.
- Warehouse Capacities: Utilization levels of warehouse capacities.
- Customer Distribution: Top customers by number of orders.
- Products Supported by Warehouse: Number of products each warehouse stocks.

### Key Insights

- Warehouse Utilization: Certain warehouses are near capacity, indicating potential bottlenecks.
- Freight Cost Variability: Significant differences in freight rates between carriers highlight optimization opportunities.
- Customer Segmentation: Identifying top customers and their order patterns enables better demand planning.

### Source:

https://www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
