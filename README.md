# Return Rate Monitoring Dashboard

## Project Overview
This project analyzes customer return behavior to identify patterns and potential root causes of returns. Using Tableau, I explored return rates across time, geography, product categories, sub-categories, and customers to understand where returns are concentrated and what factors may be driving them.

The goal of this analysis is to move beyond simply counting returns and instead provide a repeatable, interactive dashboard that helps stakeholders monitor return performance and investigate return drivers.

## How Returns Are Measured
Returns can be measured in several ways, including total number of returns, total cost of returns, and return rate. This project primarily uses **return rate**, calculated as the average of a binary returned flag, because it allows for meaningful comparisons across products, regions, and time periods regardless of sales volume. Total returns and return costs are better suited for assessing overall financial impact and are recommended as future enhancements.

## Key Insights
- Return rates vary over time, indicating seasonal effects rather than a consistent return pattern.
- Return behavior differs by product category and sub-category, suggesting product characteristics influence returns.
- Some sub-categories show elevated return rates only in specific regions, pointing to potential logistics or regional factors.
- Geographic analysis reveals states with consistently higher return rates.
- Among repeat customers, a small subset exhibits consistently high return rates, suggesting behavioral return patterns rather than occasional dissatisfaction.

## Dashboard Features
The **Return Rate Monitor Dashboard** allows users to:
- View the overall return rate as a high-level KPI
- Explore return trends over time
- Compare return rates across categories and sub-categories
- Identify geographic concentrations of returns
- Use interactive filters (region, product category, sub-category, and order month) to isolate and investigate potential root causes

## Revisions
- The **Return Rate by Sub-Category and Region** view was revised from a stacked bar chart to a highlight table based on instructor feedback, to avoid misleading aggregation of percentage-based return rates and improve interpretability.
- Updated in Story tabs as well. Marked with asterisk on tabs and captions.

## Tableau Public Link
View the interactive Tableau analysis here:
https://public.tableau.com/views/DashboardforMonitoringReturns_ElizabethParr/ReturnRateMonitorDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link

## Analysis Summary
Part 1 analyzes profit and loss centers using paired dimensions.
Part 2 evaluates advertising opportunities by state and month.
Part 3 examines product and customer return behavior.

## Tools Used
- Tableau (data visualization, dashboarding, storytelling)

## Next Steps
Future improvements could include incorporating return cost data, tracking return reasons, and deploying the dashboard for ongoing operational monitoring to support data-driven decisions around product quality, fulfillment, and return policies.

## Author
Elizabeth Parr