# ERP Order-to-Cash Analytics

## Overview
This project demonstrates an end-to-end ERP Order-to-Cash (O2C) analytics solution using Power BI.
It focuses on Accounts Receivable tracking, payment performance, and overdue invoice analysis.

The project is designed to reflect real-world business reporting used by finance, ERP, and analytics teams.

## Business Problem
Organizations need visibility into:
- Total invoiced revenue
- Payments received
- Outstanding Accounts Receivable (AR)
- Overdue invoices impacting cash flow

This dashboard helps decision-makers monitor financial health and identify risk areas.

## Dataset Description
The project uses structured CSV datasets representing ERP transactions:

- customers.csv: Customer master data (region, segment)
- orders.csv: Sales order information
- invoices.csv: Invoice amounts and due dates
- payments.csv: Payment transactions against invoices

## Data Model
The data model follows standard ERP relationships:
- Customers → Orders → Invoices → Payments
- One-to-many relationships are enforced for accurate aggregation

## Key Metrics (KPIs)
- Total Invoice Amount
- Total Paid Amount
- Accounts Receivable Outstanding
- Overdue Accounts Receivable

All KPIs are calculated using DAX measures in Power BI.

## Dashboard Features
- Executive-level KPI cards
- AR Outstanding and Overdue analysis
- Clean and simple layout for business users
- Measures formatted in thousands (K) for readability

## Tools Used
- Power BI Desktop
- DAX (Data Analysis Expressions)
- GitHub for version control and documentation

## How to Use
1. Download the CSV files from the data folder
2. Open the Power BI file from the powerbi folder
3. Refresh data connections if required
4. Explore the dashboard visuals and KPIs

## Project Structure
- data: CSV datasets
- powerbi: Power BI report file
- screenshots: Dashboard images
- sql: Reference SQL logic (optional)
- notes: Business and modeling notes

## Author
Ajay Jayshree  
Master’s Student – Management Information Systems
