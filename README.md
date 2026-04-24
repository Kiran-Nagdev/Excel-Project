## Excel-Project
Service Delivery &amp; SLA Performance Analysis
🔹 Project Overview

This project focuses on analyzing service delivery performance and SLA (Service Level Agreement) adherence using Excel-based data. The goal is to identify operational inefficiencies, detect delay patterns, and provide actionable insights to improve service performance.

🔹 Dataset Description

The dataset contains 1,000 service records covering the period January 2026 – March 2026.

### Key Columns:

* Service_ID – Unique identifier for each request
* Request_Date – Date when the service was requested
* Completion_Date – Date when the service was completed
* SLA_Deadline – Expected completion deadline
* Priority – High / Medium / Low
* Status – Completed or Delayed
* Team – Ops, Vendor, Field, Tech
* Issue_Type – Type of service request
* Resolution_Time_Hours – Time taken to resolve the request

### Objectives
* Evaluate SLA adherence across service requests
* Identify delay patterns and root causes
* Analyze team-wise performance
* Measure resolution efficiency
* Provide data-driven recommendations for improvement

### Data Processing & Analysis
* Cleaned and structured raw data for analysis
* Derived key metrics such as:
* SLA Met (Yes/No)
* Delay Duration
* Resolution Time
* Performed Exploratory Data Analysis (EDA) to identify trends and anomalies

### Key Insights
* SLA Adherence: ~47.5% (indicating high delay rate)
* Delayed Requests: ~52.5% of total records
* Average Resolution Time: ~88 hours
* Team Performance: Field team showed the lowest SLA compliance
* Primary Issue: High resolution time leading to SLA breaches

### Dashboard & Visualization

An interactive Excel dashboard was created using:

* Pivot Tables & Pivot Charts
* Slicers for filtering (Team, Priority, Date)
* Conditional Formatting to highlight SLA breaches
* Dashboard Highlights:
* SLA Adherence KPI
* Team-wise performance comparison
* Delay trends over time
* Priority vs delay analysis

### Tools & Technologies
* Microsoft Excel
* Pivot Tables
* Charts & Visualization
* Conditional Formatting
* Formulas (IF, COUNTIFS, etc.)
