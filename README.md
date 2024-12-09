# Customer Support Performance Analysis Project

## Overview
This repository contains a comprehensive Power BI dashboard project that analyzes and visualizes key performance metrics for a call center. The dashboard provides insights into customer support performance, operational efficiency, and agent performance, enabling data-driven decision-making.

## Features
- **Interactive Dashboard**: Explore data through slicers for date, topic, and agent.
- **Key Metrics**:
  - Total Calls
  - Call Answer Rate
  - Resolution Rate
  - Call Abandonment Rate
  - Average Satisfaction Score
- **Detailed Analysis**:
  - Calls by Time Bucket and Topic
  - Satisfaction Distribution
  - Agent Performance Metrics
  - Trends for Answered and Abandoned Calls
- **Visual Types**: KPI cards, bar charts, pie charts, line charts, scatter plots, and tables.

## Screenshots

### **Page 1: Customer Support Performance**
![Customer Support Performance](https://github.com/RishabhInsights/CustomerSupportPerformanceAnalysis-PowerBI-project/blob/main/CustomerSupportPerformanceAnalysis/Dashboard/Screenshot%20(46).png)

This page provides an overview of:
- Calls by Time Bucket
- Key performance indicators (Total Calls, Call Answer Rate, etc.)
- Trends for Answered and Abandoned Calls
- Distribution of Calls by Topic

### **Page 2: Customer Satisfaction and Operational Efficiency**
![Customer Satisfaction and Operational Efficiency](https://github.com/RishabhInsights/CustomerSupportPerformanceAnalysis-PowerBI-project/blob/main/CustomerSupportPerformanceAnalysis/Dashboard/Screenshot%20(47).png)

This page highlights:
- Call Abandonment Rate and Resolution Efficiency
- Satisfaction Distribution and Average Satisfaction by Topic
- Monthly trends for Answered and Abandoned Calls
- Calls Resolved by Topic and Month

### **Page 3: Agent Performance Analysis**
![Agent Performance Analysis](https://github.com/RishabhInsights/CustomerSupportPerformanceAnalysis-PowerBI-project/blob/main/CustomerSupportPerformanceAnalysis/Dashboard/Screenshot%20(48).png)

This page focuses on agent-level insights:
- Average Speed of Answer by Agent
- Total and Abandoned Calls by Agent
- Scatter Plot of Average Talk Duration vs. Calls Handled (Sized by Satisfaction)
- Agent Performance Table with key metrics

## Access the dashboard
To view and interact with this dashboard:
1. Download the `.pbix` file from this repository.
2. Open the file in Power BI Desktop.

## Dataset
The dashboard uses a sample call center dataset with the following columns:
- **Call Id**: Unique identifier for each call
- **Agent**: Name of the agent handling the call
- **Date**: Date of the call
- **Time**: Time of the call
- **Topic**: Call topic (e.g., Technical Support, Payment related)
- **Answered (Y/N)**: Whether the call was answered
- **Resolved**: Whether the call was resolved
- **Speed of Answer**: Time taken to answer the call (in seconds)
- **Average Talk Duration**: Duration of the call
- **Satisfaction Rating**: Customer satisfaction score (1-5)

## How to Use
1. Navigate through the pages using the buttons on the left panel.
2. Use slicers to filter data by date, topic, or agent.
3. Analyze key trends and performance metrics to derive actionable insights.

## Future Enhancements
- Add predictive analytics for forecasting call volumes and satisfaction scores.
- Include benchmarks for comparing performance against industry standards.
- Add annotations to highlight significant trends or outliers.
  
## Acknowledgments
Special thanks to the creators of the sample dataset and the Power BI community for their valuable resources.
