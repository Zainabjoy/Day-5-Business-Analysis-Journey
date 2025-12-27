# Day-5-Business-Analysis-Journey

## Transportation &amp; Assignment Problems (Excel)

### Transportation Problem

### A transportation problem focuses on finding the most efficient way to distribute goods from multiple sources (e.g., factories) to multiple destinations (e.g., stores).

Key elements:

Supply (capacity) at each source

Demand at each destination

Shipping cost or distance between each source–destination pair

Transportation problems are modeled as linear programming problems with:

Supply constraints (shipments ≤ capacity)

Demand constraints (shipments ≥ demand)

Objective: minimize total cost or distance

### Solving Transportation Problems in Excel

Create a cost table with sources, destinations, supply, and demand.

Create a shipment table where cells represent decision variables.

Use SUM() to calculate total shipments per source and destination.

Use SUMPRODUCT() to calculate total transportation cost.

Solve using Excel Solver (Simplex LP) with supply and demand constraints.

### Assignment Problems

An assignment problem determines the best one-to-one assignment of agents to tasks (e.g., workers to jobs).

Each agent is assigned to exactly one task

Each task receives exactly one agent

Objective is usually to minimize cost or time

Assignment problems are a special case of transportation problems where all supplies and demands are equal to 1.
They are solved in Excel using the same Solver approach.

### Tools Used

Microsoft Excel

Excel Solver

Linear Programming concepts
