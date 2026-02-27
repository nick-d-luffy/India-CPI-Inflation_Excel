This project analyzes India’s Consumer Price Index (CPI) data to understand the key drivers of inflation across categories, time periods, and major economic events.

The objective was to clean raw CPI data, structure it properly, and answer five analytical problem statements covering:

Category-level contribution to inflation

Year-on-year inflation trends

Short-term food inflation volatility

Impact of COVID-19 on inflation

Influence of global crude oil prices

The project demonstrates structured problem solving, time-series analysis, correlation analysis, and clear data storytelling using Excel.

Data Preparation

The raw CPI data was provided in a locked sheet (main_data) to maintain data integrity. All analysis was performed in a separate working_data sheet.

During preprocessing:

Missing and N/A values were identified and handled using average-based imputation.

Dates were standardized to ensure proper time-based analysis.

Urban and rural CPI values were filtered and combined where required.

Smaller CPI items were grouped into broader analytical categories (Food, Clothing, Housing, Health, Essentials, etc.).

Since detailed CPI weights were not provided, a simple average was used when grouping categories to ensure fair comparison and avoid bias from categories with more items.

This ensured the dataset was clean, consistent, and ready for analysis.

Problem 1: Category Contribution to CPI

Objective: Identify which broader category contributes most to overall inflation.

Approach:

Grouped smaller CPI items into broader buckets.

Calculated the average index for each bucket.

Computed percentage contribution relative to total CPI.

Visualized results using a bar chart.

Key Insight:
Inflation pressure was relatively balanced across major categories. Clothing showed a slightly higher contribution, while Food, Housing, and Essentials were close behind.

Business Value:
Helps policymakers and analysts understand which sectors are driving inflation and where intervention may be needed.

Problem 2: Year-on-Year Inflation Trend (2017–2023)

Objective: Analyze long-term inflation trends and identify peak inflation periods.

Approach:

Filtered combined rural and urban CPI data.

Calculated year-on-year (YoY) inflation.

Visualized trends using a line chart.

Linked spikes to macroeconomic events.

Key Insight:
Inflation peaked during the COVID and post-pandemic recovery period, influenced by supply disruptions and global price pressures.

Business Value:
Provides historical context for inflation trends and supports economic forecasting and strategic planning.

Problem 3: Monthly Food Inflation (June 2022 – May 2023)

Objective: Analyze short-term food inflation movements.

Approach:

Filtered 12 months of data.

Calculated month-on-month (MoM) food inflation.

Identified highest and lowest inflation months.

Analyzed internal food category movements.

Key Insight:
Food inflation peaked in early 2023, driven mainly by cereals and vegetables. Later months showed stabilization.

Business Value:
Useful for supply chain planning, retail pricing decisions, and food policy adjustments.

Problem 4: Impact of COVID-19 on Inflation

Objective: Compare inflation patterns before and after March 2020.

Approach:

Divided dataset into Pre-COVID and Post-COVID periods.

Calculated average inflation for key categories.

Measured the difference between periods.

Visualized results for comparison.

Key Insight:
Healthcare and essential goods saw a noticeable increase in inflation after COVID due to higher demand and supply constraints.

Business Value:
Demonstrates how external shocks impact sector-level inflation and consumer spending patterns.

Problem 5: Global Crude Oil Price Influence (2021–2023)

Objective: Measure how crude oil price fluctuations impacted inflation.

Approach:

Collected Brent crude oil data (Jan 2021 – May 2023).

Calculated month-on-month oil price changes.

Used Excel’s CORREL() function to measure correlation between oil prices and inflation categories.

Built a comparison table and visualized the results.

Key Insight:
Transport and fuel categories showed the strongest correlation with oil prices, indicating a clear pass-through effect from global oil markets to domestic inflation.

Business Value:
Helps businesses and policymakers anticipate inflation movement based on oil price trends.

Tools and Techniques Used

Microsoft Excel

Pivot Tables

VLOOKUP

XLOOKUP

CORREL()

Year-on-Year and Month-on-Month calculations

Data cleaning and imputation

Data visualization (bar, line, stacked column charts)

Analytical Skills Demonstrated

Data cleaning and preprocessing

Time-series analysis

Correlation analysis

Structured problem solving

Insight generation

Data storytelling

Translating economic data into decision-relevant insights

Conclusion

This project demonstrates the ability to:

Work with structured economic datasets

Clean and transform raw data into usable insights

Apply analytical methods to real-world economic problems

Communicate findings clearly and professionally

The analysis connects domestic inflation patterns with global economic drivers, showing a strong foundation in analytical thinking and business interpretation.
