# Task_4

## Investment Behavior Dashboard using Power BI

## Dataset:I took Finance_data.csv as Dataset

## Overview

This Power BI project visualizes and analyzes investment behavior data from a financial survey using the Sales_Financial dataset. The aim is to identify key investment patterns, preferences, and reasons behind financial decisions across different demographics.

## Dataset

- File Name: Sales_Financial.csv
- Columns Include:
  - Demographics: Gender, Age
  - Investment Types: Mutual Funds, Gold, PPF, Stock Market, Fixed Deposits, etc.
  - Reasons for Choosing Investments
  - Investment Objective, Purpose, Duration, and Monitoring Method

## Tools Used

- Power BI Desktop
- Power Query Editor
- DAX (Data Analysis Expressions)
- CSV file as data source

## Dashboard Features

### 1. KPIs (Top Section)
- Total number of respondents
- Average age of investors
- Total number of Gold/PPF/Stock Market investors

### 2. Visualizations

#### A. Pie Chart: Investment Objectives
- Shows the purpose of investing (e.g., Retirement, Wealth Creation)

#### B. Bar Charts: Reasons for Investment Types
- Separate bar charts showing reasons for choosing:
  - Mutual Funds
  - Equity Market
  - Bonds
  - Fixed Deposits

#### C. Combined Bar Chart (Advanced)
- All reasons unpivoted into a single chart for comparison across investment types

#### D. Slicers
- Filters to view data by Gender, Investment Objective, or Age Group

## Design Guidelines Followed

- Clean Layout: KPIs on top, charts below in a grid
- Consistent Theme: Applied Power BI theme from the View tab
- Clear Labels: Every visual has titles and data labels for clarity
- Alignment: Charts and visuals are aligned with consistent spacing

## How to Use the Dashboard

1. Open Power BI Desktop
2. Load the dataset Sales_Financial.csv
3. Transform data in Power Query (including unpivoting relevant columns)
4. Build visuals using the fields and DAX formulas
5. Use slicers to filter data and explore specific insights

## Tools used
- Power Bi Desktop
- Custom Finance Dataset
