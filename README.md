EV Charging Network Performance & Infrastructure Analytics

An end-to-end performance and infrastructure analysis of municipal and global Electric Vehicle (EV) charging networks. This project evaluates network performance, charging efficiency, hardware reliability, and revenue distribution based on municipal transaction records and global charging station metadata.

Executive Summary & Key KPIs

Across 102,781 charging sessions recorded in Palo Alto, California (2018–2020), the municipal charging network delivered 912,390.80 kWh of energy, generated $229,879.81 in revenue, and offset 383.20 metric tons of CO2 emissions.

Primary Metrics

Total Charging Sessions: 102,781 completed sessions
Total Energy Delivered: 912,390.80 kWh
Total Network Revenue: $229,879.81
Average Tariff Rate: $0.252 per kWh
Average Session Revenue: $2.24
Average Energy per Session: 8.88 kWh
Active Charging Efficiency: 86.5% (1.92 hours active charging / 2.22 hours total plug duration)
Active User Base: 14,009 unique drivers
Environmental Impact: 383.20 metric tons CO2 offset (114,504.93 gallons of gasoline saved)
Datasets & Documents Overview

Global Station Metadata (detailed_ev_charging_stations.xlsx)

Scope: 5,000 EV charging station profiles across urban, suburban, and highway locations.
Key Attributes:
Operators Analyzed: ChargePoint, EVgo, Greenlots, Ionity, and Tesla.
Connector Standards: J1772, CCS, CHAdeMO, Type 2, and Tesla.
Operational Metrics: Daily energy delivered, charging capacity (kW), cost structures ($/kWh), maintenance frequency, and utilization density indices.
Executive Performance Report (final report.docx)

Scope: 3-year performance breakdown of Palo Alto municipal charging stations.
Core Insights:
Level 2 Infrastructure: Accounts for 99.97% of total sessions (102,749 sessions) and $229,871.81 in revenue using J1772 connectors.
Level 1 Infrastructure: Legacy trickle chargers accounted for only 32 sessions ($8.00 total revenue).
Hardware Reliability: ChargePoint CT4020 series units processed 77.5% of total volume with an error rate under 0.05%.
Top Performing Municipal Stations

Revenue distribution across Palo Alto's network is highly concentrated in core commercial corridors. The top 5 stations alone generated $70,500.09 (30.7% of total network revenue):

Rank | Station Name | Location | Sessions | Energy (kWh) | Revenue ($) 1 | PALO ALTO CA / HAMILTON #2 | Santa Clara County | 7,102 | 68,656.07 | $17,506.80 2 | PALO ALTO CA / WEBSTER #1 | Santa Clara County | 6,432 | 61,373.61 | $15,729.72 3 | PALO ALTO CA / HIGH #3 | Santa Clara County | 5,214 | 49,500.01 | $12,878.02 4 | PALO ALTO CA / WEBSTER #2 | Santa Clara County | 5,188 | 48,928.42 | $12,678.56 5 | PALO ALTO CA / BRYANT #6 | Santa Clara County | 4,890 | 43,870.09 | $11,705.99

Key Trends & Behavioral Patterns

Multi-Year Growth: Network revenue grew 14.8% YoY from 2018 ($86,451.14) to 2019 ($99,243.36). Volume decreased in 2020 ($44,185.31) due to regional COVID-19 lockdown measures starting in March 2020.
Peak Arrival Hours: Plug-in activity peaks during business hours between 9:00 AM and 1:00 PM, reaching a maximum at 12:00 PM (9,771 sessions).
Idle Dwell Time: Vehicles remain plugged in for an average of 2.22 hours, but active charging finishes in 1.92 hours, leaving an average 18 minutes of idle dwell time per session.
Strategic Recommendations

Implement Idle Fees: Introduce a $0.10/minute fee after a 15-minute grace period once charging completes to free up high-demand ports during peak hours (9:00 AM – 1:00 PM).
Expand High-Demand Corridors: Add dual-port Level 2 chargers or DC Fast Chargers along Hamilton Avenue and Webster Street to capture unmet charging demand.
Decommission Level 1 Outlets: Phase out legacy Level 1 outlets in favor of standard Level 2 chargers to increase total throughput and operational standardization.
Repository Structure

ev-charging-analytics/ |-- detailed_ev_charging_stations.xlsx
|-- final report.docx
`-- README.md
