# Facilities Operations Analytics Dashboard

Developed an end-to-end Power BI dashboard to analyze maintenance expenses, vendor performance, and asset reliability across multiple grocery store locations.

This project simulates a real-world facilities operations environment, enabling stakeholders to monitor costs, identify inefficiencies, and make data-driven decisions.

## Key Features

- **Expense vs Goal Tracking**
  - Dynamic KPI cards comparing actual spend against quarterly targets
  - Variance analysis to highlight over/under budget performance

- **Vendor Performance Analysis**
  - Tracks average work order cost, completion time, and workload distribution
  - Identifies high-cost and low-efficiency vendors

- **Asset Cost & Reliability Insights**
  - Highlights assets driving the highest maintenance costs
  - Supports maintenance planning and replacement decisions

- **Interactive Filtering**
  - City-level and quarter-level slicers
  - Dynamic Top-N analysis for vendors and assets

## Data Model

The dashboard was designed using a star-schema-style model with:

- Fact table for work order activity
- Dimension tables for store, vendor, asset, and date
- Separate store goal logic for quarterly target benchmarking

A key modeling fix in this project involved correctly linking the date dimension to the fact table so quarterly slicers filtered both actual expenses and goal values accurately.

## Tools Used

- Power BI
- DAX
- Power Query
- Dimensional modeling concepts
- Synthetic data for demonstration purposes

## Business Value

This dashboard helps simulate how a facilities or operations team could:

- Monitor maintenance spending by location
- Compare actual expenses against budget goals
- Evaluate vendor efficiency
- Identify costly assets and maintenance patterns
- Support better operational decision-making

## Notes

- All data used in this project is synthetic and was created for portfolio purposes.
- The `.pbix` file is included in this repository.
