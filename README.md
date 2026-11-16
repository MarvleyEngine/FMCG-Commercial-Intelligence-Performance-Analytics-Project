# FMCG-Commercial-Intelligence-Performance-Analytics-Project
This project focuses on analysing commercial performance across Ghana and Guinea using sales transaction data and market intelligence indicators.

The objective is to transform raw commercial data into actionable business insights that support revenue growth, profitability improvement, market positioning and strategic decision-making.

Using Power BI, the project develops an interactive Commercial Intelligence Dashboard that enables management to monitor key performance indicators, evaluate regional and channel performance, understand product contribution, assess market presence and identify opportunities for commercial growth.

The analysis moves beyond descriptive reporting by connecting business performance indicators to practical management recommendations.

Business Problem

Commercial teams need visibility into how sales, revenue and profitability are performing across markets, regions, products and distribution channels.

However, monitoring overall revenue alone does not provide sufficient insight into:

Which markets and regions are driving commercial performance?

Which products generate the highest revenue and contribution margin?

Where are revenue and volume declining?

Are commercial targets being achieved?

Which channels offer the greatest profitability opportunities?

How does the company's market share compare with competitors?

Where should management prioritise commercial investments?

This project addresses these questions through an interactive analytical reporting solution.

Project Objectives

Evaluate overall commercial performance using volume, net sales revenue and contribution margin.

Analyse monthly sales trends and identify periods of growth and decline.

Compare actual performance against budget targets.

Identify high-performing and underperforming countries and regions.

Evaluate revenue and profitability across distribution channels.

Analyse product, brand, pack-size and category performance.

Assess market share and numeric distribution using market intelligence data.

Translate analytical findings into actionable commercial recommendations.

Dataset Overview

1. Commercial Transaction Dataset

The primary transaction dataset contains 4,539 records covering January to September 2025.

It contains 14 columns, including:

Data Category

Key Fields

Transaction

Transaction_ID, Date

Geography

Country, Region

Distribution

Channel

Customer

Customer_ID, Customer_Name

Product

SKU

Volume

Volume_UC

Sales

Gross_Sales_USD, Discounts_USD, Net_Sales_Revenue_USD

Cost and Profitability

COGS_USD, Contribution_Margin_USD

2. Market Intelligence Dataset

The market intelligence component supports competitor and market positioning analysis.

Key fields include:

Country

Category

Quarter

Brand_or_Competitor

Value_Market_Share_Pct

Numeric_Distribution_Pct

Category_Growth_Rate_Pct

Total_Category_Volume_UC

Market_Dynamics_Notes

The company's brands are identified using the ECCBC brand naming convention.

Note: The market intelligence data is a separate analytical input from the transaction extract.

Tools & Technologies

Power BI: Interactive dashboard development and business reporting.

DAX: KPI calculations, time intelligence, performance comparisons and analytical measures.

Power Query: Data cleaning, transformation and preparation.

Microsoft Excel: Initial data inspection and validation.

Data Analytics: Trend analysis, comparative analysis and commercial performance evaluation.

Key Performance Indicators

The dashboard tracks the following indicators:

KPI

Business Purpose

Actual Volume

Measures sales volume in units of cases

Net Sales Revenue (NSR)

Measures revenue after discounts

Contribution Margin (CM)

Evaluates profitability after cost of goods sold

Volume vs Budget %

Measures volume performance against target

NSR vs Budget %

Measures revenue performance against target

CM vs Budget %

Measures contribution margin performance against target

Market Share %

Measures the company's share of category value

Numeric Distribution %

Measures distribution reach across the customer universe

Additional analytical measures include:

Net Sales Revenue per Unit Case.

Contribution Margin per Unit Case.

Contribution Margin Percentage.

Month-on-Month performance.

Revenue and contribution by region, channel and product.

Competitor and category comparisons.

Key Findings

The transaction analysis produced the following findings:

Overall Performance

Actual volume: approximately 247.8K UC.

Net Sales Revenue: approximately $2.41M.

Contribution Margin: approximately $765.13K.

Contribution margin percentage: approximately 31.8%.

Monthly Performance

May recorded the highest monthly net sales revenue at approximately $309.05K.

However, revenue declined by approximately 20.1% between May and September, while volume declined by approximately 13.5%.

This indicates that the revenue slowdown should be investigated beyond volume alone, particularly through realised pricing, discounting and product mix.

Regional Performance

The three largest revenue-generating regions were:

Eastern: approximately $621.40K.

Greater Accra: approximately $548.58K.

Ashanti: approximately $419.85K.

Together, these regions contributed approximately 66% of total net sales revenue.

Channel Performance

Traditional Trade generated the highest revenue in the transaction dataset, at approximately $1.22M.

On-Premise / HoReCa recorded a contribution margin percentage of approximately 36.1%, making it an attractive channel for further commercial evaluation.

Product Performance

SKU-203 generated the highest net sales revenue, approximately $339.17K.

However, its contribution margin percentage was approximately 27.8%, indicating an opportunity to investigate its pricing, cost structure and discounting.

Market Intelligence

The dashboard also provides market share, numeric distribution and category-level comparisons.

These indicators help assess competitive positioning and identify potential opportunities to improve market presence and distribution reach.

Management Recommendations

The analysis supports the following priorities:

Investigate the revenue slowdown after May by separating volume, price and product-mix effects.

Protect and strengthen performance in Eastern, Greater Accra and Ashanti.

Review SKU-203 pricing, discounting and cost efficiency to improve profitability.

Evaluate expansion opportunities in On-Premise / HoReCa.

Improve product, customer, country and channel data standardisation.

Use market share and numeric distribution analysis to identify competitive gaps and prioritise distribution expansion.

Project Deliverables

Interactive Power BI Commercial Intelligence Dashboard.

Commercial performance and KPI analysis.

Regional and distribution channel performance analysis.

Product and profitability analysis.

Market share and numeric distribution analysis.

Management recommendations.

Interview presentation summarising key findings.

Business Value

This project demonstrates how commercial data can be transformed into meaningful management intelligence.

By integrating sales performance, profitability, regional distribution and market intelligence, the solution provides a consolidated view of business performance and helps management identify where to protect revenue, improve margins and pursue growth opportunities.

Disclaimer

This is a portfolio and analytical case study. The dataset is used for demonstration and analysis purposes and should not be interpreted as verified company financial reporting.

The transaction dataset covers January–September 2025. Market intelligence indicators are sourced separately and should be interpreted within their respective reporting periods.

All financial values are presented in USD.
