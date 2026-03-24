****1. Project Title / Headline**
Meta Ad Performance Dashboard | Power BI + SQL Marketing Analytics Solution An end-to-end digital marketing analytics dashboard built using Power BI and SQL to track ad campaign performance across Facebook and Instagram — offering insights into audience engagement, conversion rates, and ROI for marketing optimization.

**2. Short Description / Purpose**
The Meta Ad Performance Dashboard provides a unified view of digital campaign metrics across multiple platforms. It enables marketing teams to monitor ad reach, clicks, engagement, conversions, and spend efficiency across age, gender, and ad type. The dashboard helps decision-makers identify top-performing campaigns, understand audience behavior, and optimize ad budgets.

**3. Tech Stack**
This project was developed using the following tools and technologies:

SQL Server – For storing campaign, engagement, and spend data; joins and aggregations.

Power BI Desktop – For creating interactive dashboards and visual reports.

Power Query (M) – For cleaning, transforming, and shaping ad performance data.

DAX (Data Analysis Expressions) – For dynamic KPIs like CTR, Conversion Rate, Engagement Rate, and Purchase Rate.

Data Modeling – Star schema with fact table (AdPerformanceFact) and dimensions (CampaignDim, PlatformDim, DateDim, AudienceDim).

Power BI Service – For sharing dashboards, workspace management, and scheduled refresh.

File Format: .sql, .pbix, .png

**4. Data Source**
Source: SQL-based Meta Ads dataset (Facebook + Instagram ad data).

Tables Used:

AdPerformanceFact – Metrics for impressions, clicks, shares, purchases, and spend.

CampaignDim – Campaign details like campaign name, duration, and target audience.

PlatformDim – Facebook and Instagram platform-level info.

AudienceDim – Demographics (age, gender, interest).

DateDim – Calendar table for weekly and monthly analysis.

Data was transformed and loaded via DirectQuery for real-time updates.

**5. Features / Highlights Business Problem**
The marketing team lacked a centralized view of ad performance across platforms, making it difficult to measure engagement, conversion, and ROI effectively.

Goal of the Dashboard

To create an interactive performance monitoring system that:

Tracks campaign KPIs like CTR, Engagement Rate, Conversion Rate, and Purchases.

Segments performance by gender, age, platform, and ad type.

Provides insights into peak engagement times and campaign ROI trends.

Walkthrough of Key Visuals

Overview Page Top KPIs:

Impressions: 339.8K

Clicks: 40.1K

Engagement Rate: 13.58%

CTR: 11.79%

Conversion Rate: 5.07%

Purchases: 2K

Total Budget: $2.5M

Visual Highlights:

Engagements by Gender (Donut Chart): Breakdown of engagement % among Male, Female, and Others.

Engagements by Age (Histogram): Identifies top-performing age brackets (e.g., 25–35).

Weekly Engagement Trend (Bar Chart): Displays week-over-week engagement variations.

Engagement by Event Hour (Line Chart): Shows peak user activity hours.

Analysis by Ad Type (Matrix Table): Compares Stories, Video, and Carousel ads for KPIs.

Filters: Campaign Name, Platform, Month, Dynamic Measure selector.

SQL Tasks Involved

Wrote queries to aggregate campaign data by week, age, and gender.

Used window functions to calculate running totals, CTR, and engagement rate.

Applied CASE and CTE logic to handle missing or inconsistent data.

Optimized queries for Power BI DirectQuery mode performance.

Business Impact & Insights

Improved campaign monitoring with 100% visibility across Meta platforms.

Helped identify the 25–35 age group and male audience as key engagement drivers. 3.Optimized ad budget allocation based on ROI and engagement patterns.

Screenshots / Demos https://github.com/nitj8/Meta-Ad-Performance-Dashboard/blob/main/Meta%20Ad%20Performance%20Dashboard.png
