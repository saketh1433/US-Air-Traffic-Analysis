# International Passenger and U.S. Air Traffic Analysis

## Overview
This project presents an analytical deep dive into the trends of international passenger and U.S. air traffic to assist airlines in making informed strategic decisions. The analysis uses datasets from the U.S. Department of Transportation's "U.S. Airline Traffic by Airport" and "International Passenger Report." Key insights include passenger and freight trends, seasonal demand patterns, and the impacts of global events on air travel.

## Project Objectives
- **Identify Key Trends**:
  - Understand the growth patterns of passenger volumes and freight loads over the last decade.
  - Explore seasonal and regional variations in air traffic.
- **Analyze Market Performance**:
  - Highlight high-demand routes and major airline hubs.
  - Investigate market share distribution across carriers.
- **Support Decision-Making**:
  - Provide actionable recommendations for resource allocation and operational optimization.

## Datasets
### 1. U.S. Airline Traffic by Airport
- **Source**: U.S. Department of Transportation
- **Key Features**:
  - State, City, Airport, and IATA codes.
  - Passenger, Freight, and Mail volumes.
  - Yearly trends from key states: Alaska, California, Georgia, Illinois, and Massachusetts.

### 2. International Passenger Report
- **Source**: Bureau of Transportation Statistics
- **Key Features**:
  - U.S. and international airport codes.
  - Monthly and yearly passenger volumes for nonstop international flights.
  - Carrier and flight type classifications (scheduled or charter).

## Tools and Technologies
- **Programming Languages**: Python
- **Libraries**: Pandas, Matplotlib, NumPy, Google BigQuery
- **Data Storage**: Google Cloud BigQuery
- **Visualization**: Matplotlib charts for trend and distribution analysis.

## Key Findings
1. **Passenger Growth Trends**:
   - Consistent growth until 2020, with significant dips during major events like the 2008 financial crisis and COVID-19 pandemic.
   - Seasonal peaks in summer and winter driven by vacations and holidays.
2. **High-Demand Routes**:
   - Top-performing routes include JFK to London Heathrow (LHR) and LAX to Tokyo Narita (NRT).
   - Transatlantic and transpacific routes dominate in passenger volumes.
3. **Freight Insights**:
   - Freight volumes surged during the pandemic due to increased e-commerce activity.
   - Alaska and California lead in freight tonnage due to strategic hubs like ANC and LAX.
4. **Market Share Analysis**:
   - American Airlines (AA) and United Airlines (UA) dominate market share, with British Airways (BA) leading among international carriers.

## Entity Relationship Diagram (ERD)
The ERD visualizes the relationship between U.S. airport data and international passenger data. Airports serve as the linking key to unify both datasets for comprehensive analysis.

## Key Questions Explored
1. **Demand Trends**:
   - How do passenger volumes vary by year, quarter, and season?
   - Which routes experience the highest traffic volume?
2. **Market Analysis**:
   - Which carriers dominate market share, and how do they perform regionally?
   - What are the busiest U.S. and international airport pairs?
3. **Freight Analysis**:
   - How has the distribution of freight loads varied across states?
   - What are the key hubs for freight transport in the U.S.?
4. **Operational Insights**:
   - How can airlines optimize resource allocation for high-demand routes?

## Recommendations
- **Demand Optimization**:
  - Scale flight capacities during peak seasons.
  - Focus marketing efforts on high-demand routes during vacation periods.
- **Operational Efficiency**:
  - Enhance route management for transatlantic and transpacific flights.
  - Leverage high-performing hubs for freight and passenger services.
- **Risk Mitigation**:
  - Diversify revenue streams to withstand economic and global disruptions.

## Repository Structure
/project ├── data/ │ ├── us_air_traffic.csv │ ├── international_passenger.csv ├── analysis/ │ ├── traffic_trends_analysis.ipynb │ ├── freight_analysis.ipynb ├── visualizations/ │ ├── passenger_trends.png │ ├── market_share.png ├── README.md

## How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/<username>/<repo-name>.git

## Contributors
- Saketh Bollina
- Aaryan Bammi
- Chaitali Deshmukh
- Crystal Leatvanich
- Junhan Chen
- Kuang-Ching (Amanda) Ting
