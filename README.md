## Financial-Performance-Dashboard
This interactive Power BI dashboard tracks revenue, expenses, profitability and budget variance across two fiscal years (FY2024 and FY2025). It is built on a simulated general-ledger (GL) dataset and modelled as a star schema, with DAX measures for margins, year-over-year (YoY) growth and budget variance.
Note: All data in this project is synthetic. It was generated for portfolio purposes and does not represent any real company.

# Dataset Used
- <a href="https://github.com/khalidhmd28/Financial-Performance-Dashboard/blob/main/Financial_Performance_Dataset.xlsx">Dataset</a>

# Business Questions Answered
• How are revenue, net income and net margin trending month by month?
• Which revenue streams and business units drive growth and seasonality?
• How does actual revenue compare with forecast and budget?
• Where is the money going, and which expense accounts are running over budget?
• How did FY2025 perform compared with FY2024?

# Dashboard Contents
• KPI banner: cards for Net Revenue, Gross Profit, Total OPEX and Net Income, with a YoY label when a single year is selected.
• Slicers: Year, Quarter, Business Unit and Department filter the whole page.
• Profitability trend: combo chart with Net Revenue and Net Income as columns and Net Margin % as a line, showing monthly seasonality.
• Revenue mix: stacked column chart of Product, Subscription and Services revenue by month.
• Business unit view: stacked column chart of Net Revenue, Gross Profit and Net Income for Software, Hardware and Services.
• Revenue vs forecast: column and line chart comparing actual revenue with budgeted revenue.
• Expense breakdown: donut chart showing how total cost splits across COGS, Personnel, Technology, Marketing and other sub-categories.
• GL account table: Budget, Actual and Variance % by account, with conditional formatting that flags accounts over budget in red.

# Key Insights (FY2025 vs FY2024)
• Revenue grew about 8.5% year over year, from $5.90M to $6.40M.
• Operating expenses fell about 4%, from $2.45M to $2.35M, so net income rose from $0.55M to $0.92M.
• Revenue is seasonal. Hardware sales spike in November and December, while services revenue peaks at quarter ends (March, June, September, December).
• Net margin climbs through the year, from roughly 6% in January to about 20% in December (FY2025), as revenue grows against a mostly fixed cost base.
• Cost watch-list: Travel & Entertainment and Advertising & Promotion run furthest over budget, while Training & Development comes in under budget.

# Tools and Skills Demonstrated
• Power BI Desktop: report design, slicers, conditional formatting, combo, stacked and donut charts
• Data modelling: star schema, relationships, date table
• Financial analysis: P&L structure, margins, YoY growth, budget vs actual variance
• Data preparation: synthetic GL dataset with seasonality, prepare with Claude and Excel
