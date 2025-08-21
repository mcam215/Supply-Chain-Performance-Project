Global Supply Chain Performance & Cost Optimization
This repository contains the analysis and Tableau dashboard for a project focused on optimizing a global supply chain's delivery performance and logistics costs.

Objective
The primary goal of this project was to design and implement an analytical tool for a global logistics team. This tool provides interactive reports and deep insights into delivery performance and cost efficiency, enabling data-driven decisions for vendor management, shipment routing, and cost negotiations.

Dataset
The analysis was performed on the SCMS_Delivery_History_Dataset, sourced from Kaggle. It contains historical data on shipments, including vendors, costs, delivery dates, and product details.

Link: SCMS_Delivery_History_Dataset on Kaggle

Tools & Technologies
Data Cleaning & Transformation: Python (Pandas)

Data Querying: SQL

Data Visualization & Dashboarding: Tableau

Analysis & Key Findings
Process
The project followed a structured analytical process:

Data Cleaning and Transformation: Performed extensive data wrangling in Python to handle missing values, correct data types (e.g., converting dates and costs to numeric formats), and standardize categorical data like vendor names.

Feature Engineering: Created new calculated metrics to provide deeper insights, including On-Time Delivery (OTD) Rate, Delivery Lead Time, Total Logistics Cost, and Freight Cost as a Percentage of Line Item Value.

Dashboard Development: Designed and built two interactive dashboards in Tableau to visualize KPIs and allow for dynamic filtering by country, shipment mode, and vendor.

Key Findings
Overall OTD: The analysis revealed an overall On-Time Delivery Rate of 88.51%, indicating strong but improvable performance.

Shipment Mode Impact: Air Charter and Truck modes achieved a perfect 100% OTD rate, while the higher-volume Air (88.89%) and Ocean (84.34%) modes were the primary sources of delays.

Lead Time Variance: A significant difference in average lead times was found between modes (e.g., Air at 88 days vs. Ocean at 144 days), impacting planning and customer expectations.

Cost Concentration: A critical insight was that the ARV and HRDT product groups accounted for over 99% of total logistics costs, making them prime targets for optimization efforts.

Recommendations
Based on the findings, the following actionable recommendations were developed:

Re-evaluate Shipment Mode Strategies: Conduct a detailed cost-benefit analysis to determine if shifting volume from standard Air and Ocean to more reliable modes like Air Charter is financially viable to improve the OTD rate for critical shipments.

Initiate a Targeted Cost-Reduction Initiative: Focus all initial cost-saving efforts on the ARV and HRDT product groups, as they represent the largest opportunity for impact. A deeper analysis into their specific cost drivers is recommended.

Key Deliverables
Tableau Dashboard 1: Global Delivery Performance Overview: A holistic view of delivery reliability and speed.

Tableau Dashboard 2: Logistics Cost Analysis: A breakdown of total logistics spend and cost efficiencies.
