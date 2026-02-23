
📊 Cyclistic Membership Conversion Analysis
Executive Summary

This repository presents an end-to-end analysis of Cyclistic, a bike-sharing service, to identify high-potential Casual Riders and inform membership growth strategies. Using 12 months of ride data, SQL, and Tableau, the project uncovers usage patterns, seasonal trends, and commuter behavior, translating insights into actionable recommendations. Key strategies include targeted seasonal campaigns, tiered summer memberships, and peak-hour dynamic pricing, with estimated revenue and conversion gains of 10–15% and 3–6%, respectively.

Business Problem

Cyclistic aims to increase long-term revenue by converting Casual Riders into Annual Members. This analysis identifies behavioral differences and high-probability conversion segments.

Data Overview

-12 months of ride data (02-01-2025 to 01-01-2026)
-Source: Motivate International Inc. (Divvy Data License Agreement)
-Data size: 5,552,092 rows
-Tools: Google Sheets, BigQuery (SQL), Tableau



Methodology
1. Data Acquisition

-12 months of publicly available ride data obtained under the Divvy -DataLicense Agreement.
-Dataset included ride timestamps, rider type, ride duration, and station data.

2. Data Cleaning & Preparation

-Initial exploratory analysis conducted in Google Sheets.
-Standardized date/time formats.
-Removed null and invalid ride durations.
-Engineered new features including:
-Ride duration (minutes)
-Day of week
-Month
-Time-of-day segmentation
-Final cleaned dataset uploaded to BigQuery for large-scale querying.

3. Exploratory Data Analysis (SQL – BigQuery)

-Aggregated ride counts by rider type.
-Compared average ride duration.
-Analyzed weekday vs weekend usage.
-Identified seasonal trends.
-Evaluated hourly ride distribution to detect commute behavior.

4. Visualization & Communication
-Key metrics exported to Tableau Public.
-Developed visual dashboards highlighting behavioral segmentation.
-Findings synthesized into a business-focused presentation with strategic recommendations.

Key Insights

-Casual Riders skew toward weekend and leisure usage.
-Annual Members show consistent weekday commuting behavior.
-A subset of Casual Riders mirrors Member ride frequency.
-Usage declines significantly during winter months.

Strategic Recommendations
1. Target High-Probability Casual Riders for Conversion

Analysis identified a subset of Casual Riders whose ride frequency, duration, and weekday usage closely mirror Annual Members. These riders represent the highest-probability conversion segment.

Action:
Develop targeted digital campaigns (email, in-app messaging, and push notifications) offering limited-time membership incentives to high-frequency Casual Riders.

Business Rationale:
Focusing on behaviorally similar users increases conversion efficiency and reduces customer acquisition costs.

2. Stabilize Revenue Through Seasonal Incentives

Ride volume declines significantly during winter months, impacting overall usage and revenue stability.

Action:
Introduce seasonal promotions such as discounted annual memberships during low-demand months or bundled winter membership extensions.

Business Rationale:
Counter-cyclical pricing strategies can smooth revenue fluctuations and improve annual retention.

3. Optimize Pricing During Peak Commuter Hours

Casual Rider usage increases during commute-aligned hours, suggesting overlap with Member commuting behavior.

Action:
Test dynamic pricing models or peak-hour pricing incentives that highlight the cost savings of Annual Membership during frequent commute periods.

Business Rationale:

-Demonstrating clear financial advantages during peak usage windows can accelerate conversion among routine riders.
-Future Analytical Enhancements
-Build a predictive classification model to estimate membership conversion likelihood.
-Conduct cohort retention analysis to evaluate post-conversion behavior.
-Perform A/B testing on targeted promotional strategies.
-Integrate cost and revenue modeling to quantify projected ROI.
