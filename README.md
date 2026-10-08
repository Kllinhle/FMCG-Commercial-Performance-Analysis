# FMCG-Commercial-Performance-Analysis
An interactive Excel-based commercial finance analysis of simulated FMCG sales data, focusing on revenue, profitability, product performance, country/channel performance, and promotion effectiveness.

## Project Overview

This project analyzes 2026 simulated FMCG transaction data covering:

- 30 SKUs
- 4 product categories
- 3 countries
- 3 sales channels
- 3 promotion types
- 1,000 transactions

The objective is to understand the key drivers of revenue and profitability and translate the analysis into actionable commercial insights.

## Key Analysis

### 1. Revenue Dashboard
An interactive dashboard built with Excel PivotTables, PivotCharts, slicers, and a timeline to monitor:

- Revenue
- Gross profit
- Gross margin
- Units sold
- Revenue by category
- Revenue by country
- Revenue by channel
- Monthly revenue trends

Users can dynamically filter the dashboard by country, category, channel, and period.

### 2. Category & Product Analysis
Analyzes profitability across categories and individual products to identify revenue and margin trade-offs.

Key findings include:
- Oral Care has the highest gross margin while also recording the highest unit volume.
- Laundry generates the largest revenue contribution but has the lowest category gross margin.
- Toothpaste 75ml has the highest product-level gross margin but a relatively small revenue contribution.
- Detergent Capsules generates the highest product-level revenue but operates at a comparatively lower margin.

### 3. Country × Channel Analysis
Compares revenue and gross margin across countries and sales channels to identify differences in market and channel performance.

### 4. Promotion Performance
Evaluates promotional and non-promotional transactions based on:

- Revenue
- Gross profit
- Gross margin
- Units sold
- Promotion cost

The analysis also compares promotion performance across product categories.

Promotional transactions show a lower observed gross margin than non-promotional transactions, highlighting the potential margin trade-off associated with discounting.

## Key Business Insight

The analysis demonstrates that revenue growth and profitability do not always move together. High-revenue products and categories can have relatively lower margins, while high-margin products may contribute a smaller share of total revenue.

This highlights the importance of evaluating **sales volume, revenue contribution, margin, product mix, channel mix, and promotional activity together** when making commercial decisions.

## Tools & Skills

- Microsoft Excel
- PivotTables & PivotCharts
- Slicers & Timelines
- Data analysis
- Financial performance analysis
- Profitability analysis
- Commercial / FMCG analysis
- Dashboard development

## Key Assumptions

- Revenue reflects the net selling price after applicable discounts.
- Gross Profit = Revenue − COGS.
- Gross Margin = Gross Profit / Revenue.
- Promotion cost represents the value of discounts applied to promotional transactions.
- Promotion analysis is descriptive and does not establish causality.
- The dataset is simulated for portfolio purposes and does not contain confidential company data.

## Project Structure

- `Cover` – Project purpose, assumptions, and scope
- `Product_Master` – Product and cost information
- `Raw Data` – Transaction-level dataset
- `Revenue Dashboard` – Interactive commercial performance dashboard
- `Category Analysis` – Category-level revenue and profitability
- `Product-level Analysis` – Product revenue and margin analysis
- `Country x Channel` – Market and channel performance
- `Promotion Performance` – Promotion and margin analysis
