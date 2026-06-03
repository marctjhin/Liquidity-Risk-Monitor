# Liquidity-Risk-Monitor
The **Liquidity Risk Monitor** is a web-based dashboard designed to help financial institutions monitor and **manage liquidity risk** in real time. The system tracks cash inflows and outflows, calculates liquidity ratios, and alerts users when liquidity levels fall below the predefined thresholds. The dashboard provides visual insights into an organization's liquidity position, which allows treasury managers and risk analysts to make informed decisions regarding cash management and funding requirements. 

# Data Structure and OOP
Liquidity transactions occurs in a chronological order which aligns with a data structure we know as **_Queue_** because it also follows the **FIFO** rule that says First-In-First-Out. This program also uses **_Arrays_** for storing datas such as portfolio assets, forecaset history, etc. Arrays allow efficient storage, sorting, filtering, and visualization of historical liquidity information. 

This program also functions using OOP (Object Oriented Programming) in which inside of it there;s encapsulation, abstraction, etc. 

# Features
- Dashboard Overview
- Total Assets Under Management (AUM)
- Liquid Assets
- Estimated Liquidation Costs
- Average Days to Liquidate
- Portfolio Management
- Asset table displaying all portfolio holdings
- Asset classification by liquidity tier
- Liquidity status indicators
- Liquidity Coverage Ratio (LCR) Monitor
- Real-time LCR calculation
- HQLA (High Quality Liquid Asset) analysis
- Historical LCR trend visualization
- Liquidity Forecasting
1. 30-Day Forecast
2. 90-Day Forecast
3. 1-Year Forecast
- Linear Trend Forecasting
- Exponential Smoothing Forecasting
- Seasonal Forecasting
- Liquidation Simulation
- User-defined redemption targets
- Queue-based liquidation processing
- Shortfall reporting
- Event Logging
- Records simulation activities
- Tracks queue operations
- Displays system alerts and warnings

# Initial Prompt
Build me the Liquidity risk monitor with a dashboard and sample data, making sure to clearly use Queue and Array data structures in the code. make it in javascript and must use object oriented programming principles. Make it to a website dashboard but put everything into 1 file.
