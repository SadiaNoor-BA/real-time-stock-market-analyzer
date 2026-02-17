# Real-Time Stock Market Analyzer & Financial Engineering Hub
## Project Overview
This project is a high-performance Financial Engineering dashboard built in **Power BI**. It provides a dynamic, real-time environment to monitor market volatility, compare asset performance, and generate automated narrative insights. By integrating live market data through **API protocols**, the hub eliminates manual data entry and provides instant technical analysis for decision-making.

## Business Problem
Financial analysts often struggle with fragmented data sources and "stale" reports that do not reflect intra-day market shifts. This project solves these challenges by:

**Automating Data Retrieval:** Removing the lag between market movements and reporting.

**Comparative Momentum Tracking:** Normalizing different stock prices to a "% from Start" basis to compare performance directly.

**Reducing Analytical Overhead:** Using AI-driven narratives to summarize complex trends instantly.

## Technical Stack

**BI Tool:** Power BI Desktop / Service.

**Data Source:** Alpha Vantage API (JSON).

**Languages: * M-Code:** For custom API connection strings, dynamic parameterization (Ticker/API Key), and data transformation.

**DAX:** For advanced time-series analysis and financial measures.

**Modeling:** Flat-file transformation into a time-centric schema.

## Key Features & Analytics
**Dynamic API Integration:** Built a flexible ETL pipeline using **Power Query Parameters** allowing users to switch tickers (e.g., AAPL, MSFT, NVDA) without modifying code.

**10-Day Moving Average (MA):** A sophisticated DAX measure used to smooth price fluctuations and identify short-term trend reversals.

**Performance Normalization:** Developed a **% from Start** calculation to visualize relative gains/losses across multiple stocks on a single axis.

**Automated Smart Narratives:** Integrated a natural language layer that identifies the steepest periods of decline and growth based on the selected date range.

**Operational Metadata:** Implemented a **"Last Data Refresh"** timestamp to ensure data integrity and transparency for stakeholders.

## How to Use
**Clone the Repository:** Download the .pbix file.

**API Key:** Sign up for a free key at Alpha Vantage.

**Parameters:** Enter your API key and desired Ticker symbols into the Power BI "Edit Parameters" menu.

**Refresh:** Click refresh to pull the latest 100 days of market data.

![Project Dashboard](Real Time Stock Market Analyzer.png)

