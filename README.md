# Supply Chain Logistics Optimization for a Global Microchip Producer

## Overview

**In the high-stakes world of microchip manufacturing, a supply chain optimized only for cost is a fragile one.** This project conducts a comprehensive resilience audit of a global microchip producer's logistics network, treating it as a complex system requiring strategic governance. We move beyond identifying cost savings to diagnose hidden vulnerabilities, assess single points of failure, and evaluate the network's ability to withstand disruption. Our analysis provides the foundational intelligence for building a Digital Supply Chain Control Tower that balances efficiency with resilience.

### Supply Chain Problem: Efficiency at the Cost of Resilience

Global microchip supply chains are notoriously fragile, where a single disruption can halt production for billions of dollars worth of downstream products. An ungoverned network, even an "efficient" one, harbors critical risks:

- Bottleneck Risk: Over-reliance on critical routes (e.g., PORT04 → PORT09) creates single points of failure where any disruption causes cascading delays.

- Cost Volatility Risk: Unmanaged variability in carrier rates and weight bands exposes the company to unpredictable cost inflation.

- Capacity Rigidity Risk: Imbalanced warehouse utilization prevents the network from dynamically responding to shifts in demand or supplier outages.

### Dataset Description

The data is sourced from a Microsoft Excel file, Supply chain logistics problem.xlsx, containing the following sheets:

- OrderList: Detailed information about customer orders, including the product, warehouse, carrier, weight, and destination port.
- FreightRates: Details about carriers, weight bands, shipping rates, modes of transport, and estimated transport days.
- WhCosts: Storage costs per unit for each warehouse.
- WhCapacities: Daily capacity constraints for each warehouse.
- PlantPorts: Mapping of warehouses (plants) to allowed shipping ports.
- ProductsPerPlant: List of products supported by each warehouse.
- VmiCustomers: Special warehouse-customer relationships.

### Our Approach: The Multi-Dimensional Network Diagnostic

We applied a governance-first framework to audit the supply chain across its key risk dimensions.

1. **The Resilience Stress Test**

Bottleneck Analysis: We identified PORT04 → PORT09 not just as a high-volume route, but as a critical vulnerability. Its high volume, combined with any delay, represents a systemic risk to the entire operation.

Capacity Flexibility Audit: We assessed warehouse utilization to answer: Can the network dynamically re-route orders if a key warehouse fails? The identification of underutilized facilities is not just a cost opportunity—it's a strategic lever for building redundancy.

2. **The Cost & Performance Governance Audit**

Carrier Strategy Analysis: We moved beyond finding the cheapest carrier to evaluating carrier reliability and cost predictability. A cheaper carrier with volatile performance is a higher business risk than a slightly more expensive, reliable one.

Freight Rate Volatility Assessment: The identified variability in carrier rates is a governance failure. A governed system would establish preferred carrier partnerships with stable, negotiated rates to shield the company from market volatility.

3. **The Strategic Opportunity Mapping**

Flow Re-balancing: We identified that consistently on-time routes (PORT09 → PORT09, PORT05 → PORT09) are underutilized. This presents a clear, data-backed action to mitigate bottleneck risk by rebalancing volume away from the high-risk PORT04 route.

### Audit Results & Strategic Recommendations

- Network Resilience - Critical bottleneck on PORT04→PORT09 route.	HIGH RISK. Immediate action required to diversify shipping routes and develop contingency plans for this corridor.
- Cost Management - High variability in freight rates and identified cost-saving opportunities.	MODERATE RISK. Implement a strategic carrier program with negotiated rates to reduce volatility and lock in savings.
- Capacity Utilization - Identified underutilized warehouses and imbalanced loads. STRATEGIC OPPORTUNITY. Formalize a dynamic capacity-sharing protocol between warehouses to build inherent network flexibility.

### Conclusion: Building the Anti-Fragile Microchip Supply Chain

This audit demonstrates that true supply chain optimization is about engineering resilience, not just minimizing costs.

The supply chain is efficient but brittle. It is optimized for steady-state operations but lacks the redundancy and dynamic routing capabilities needed to absorb shocks. The 80/20 rule applies: 80% of the disruption risk is concentrated in 20% of the shipping routes.

### Source:

https://www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
www.kaggle.com/datasets/anisseezzebdi/supply-chain-logistics-problem/data
