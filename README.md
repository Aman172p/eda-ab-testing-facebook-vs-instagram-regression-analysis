
# A/B Testing Comparison: Facebook vs. Instagram
Which ad platform is more effective in terms of conversions, clicks, and overall cost-effectiveness


## Business Problem
As a marketing agency, our primary objective is to maximize the return on investment (ROI) for our clients’ advertising campaigns. We have conducted two ad campaigns, one on Facebook and the other on Instagram, and we need to determine which platform yields better results in terms of clicks, conversions, and overall cost-effectiveness. By identifying the most effective platform, we can allocate our resources more efficiently and optimize our advertising strategies to deliver better outcomes for our clients.
## Tools & Technologies
Python(Pandas, Matplotlib,seaborn,LinearRegression,scipy)
## Data Cleaning & Preparation
Converted date and time columns from object (string) format to datetime to ensure accurate chronological sorting and time-based analysis.

Generated a summary-level table to compare Key Performance Indicators (KPIs) between the Facebook and Instagram test groups.
## Exploratory Data Analysis (EDA)

•Instagram had more frequent higher conversion days in the 6–10 day range, whereas most Facebook conversions occurred at >15 days, identifying a significant variance in campaign performance.

•Identified strong alignment between clicks and conversions across both platforms, with Instagram showing a slightly higher correlation of 0.96 compared to Facebook at 0.94.

•Determined channel effectiveness by comparing mean conversions from Facebook ads (39.99) and Instagram ads (20.93); with a T-statistic of 13.6606, Facebook advertising appears to be a more effective channel for generating conversions.

•Demonstrated reasonably good predictive power with an R2 score of 76.35%, proving the model can effectively predict Facebook ad conversions based on the number of Facebook ad clicks.
## Final Recommendations

•Recommendation: Direct the majority of the advertising budget toward Facebook for long-term volume growth, but utilize Instagram for "flash" sales or time-sensitive promotions.

•Data Justification: Since Facebook has a significantly higher mean conversion (39.99 vs. 20.93), it is the primary driver for scale. However, because Instagram converts more frequently in the 6–10 day window (compared to Facebook's >15 days), it is better suited for shorter marketing cycles.

•Shift from reactive to proactive budget management on Facebook by using click-count data to forecast end-of-month conversions.

