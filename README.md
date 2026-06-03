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

# What did you learn in the process? 
With this project, I figured out that data structures, really do show up in real-world financial systems more than I expected. I got a sharper feel for how queues can stand in for transaction processing, and also how arrays are good at holding past liquidity data in an efficient way, and all of these thoughts wouldn't come up if I didn't do this assignment, despite me having interest towards computational finance and risk management. On top of that, I improved my understanding of object-oriented programming a bit, by seeing classes that split up responsibilities, so the whole system stays easier to maintain. It all kind of makes sense over time, and I could see the connections more clearly on the application side. 

# What were the benefits of working with GenAI? 
While GenAI generated useful code quickly, not all outputs were immediately correct and optimized. Some generated sections required debugging, modification, and validation to ensure they met the project requirements with some personalization not included to them and requires users to still instruct them what to do in order to match our preferences. It was important to carefully review the generated code and try running it rather than assuming it was fully accurate. 

# What were the drawbacks? 
The first thing for sure is that GenAI has their own limit. Often times, during my time adding features and personalization, the GenAI traverses through all code all over again, not the specific parts, which used more limit than they should've used. Also, I see inefficiency in the code because some might be debugged by only 20 lines but GenAI uses more codes than it actualy needs. 

# Any other thoughts? 
GenAI assignments are good for end of quarter assignment because it really connects my mind towards how what I learned this quarter actually is applicable in the real world
