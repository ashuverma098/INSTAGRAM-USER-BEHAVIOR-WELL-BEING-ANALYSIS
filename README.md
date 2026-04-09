# INSTA-GRAM-USER-BEHAVIOR-WELL-BEING-ANALYSIS
# 📊 Project Overview
This project is a comprehensive data visualization dashboard designed to analyze Instagram user demographics, engagement patterns, and behavioral trends. It provides a high-level view of user distribution across various factors like geography, income, and education level.
# 🚀 Key Features
- User Segmentation: Breakdown of total users into Premium vs. Non-Premium categories.
- Geographic Insights: Analysis of user concentration by country (USA, India, Brazil, etc.) and living environment (Urban, Suburban, Rural).
- Demographic Profiles: Visualizations for gender distribution, education levels (from High School to PhD), and income brackets.
- Engagement Metrics: Tracking average daily steps, daily minutes on the app, and weekly post frequency.
- Behavioral Correlation: A specialized chart showing the relationship between "Stress Score" and time spent on Instagram feeds.
# 🛠️ Tools Used
- Data Visualization:Power BI
- Design: Custom pink/purple gradient theme for a modern "social media" aesthetic.
# 💡Key Insights from the Data
- Urban Dominance: The majority of users are located in Urban areas, showing a significant drop-off in Rural regions.
- Top Markets: The United States and India represent the largest user bases in this dataset.
- Education & Usage: Approximately 35% of users hold a Bachelor's degree, making them the largest educational demographic.
- The "Stress" Factor: There is a clear linear correlation between the time spent on feeds and the reported stress score of users.
# 🛠️ Data Cleaning & Transformation (ETL Process)
The raw dataset was processed using Power Query Editor to ensure data integrity and high-quality visualizations.
- Data Profiling & Quality Check
- Column Quality: Used Power BI’s "Column Quality" and "Column Distribution" tools to identify outliers and empty values.
- Data Validation: Verified that "Total Users" matched the sum of Premium and Non-Premium users to ensure a "Single Source of Truth".
* 2. Structural Cleaning
* Promoted Headers: Set the first row as headers for consistent naming conventions across all tables.
* Removed Redundant Data: Eliminated duplicate records based on User_ID to prevent skewed averages.
* Renamed Columns: Standardized messy internal labels (e.g., changing avg_post_w to Avg Posts per Week) for user-friendly reporting.
- 3. Handling Missing & Null Values
- Null Treatment: Replaced null values in the "Income Level" and "Education" columns with "Unknown" or "Other" to maintain category completeness.
- Row Removal: Removed completely blank rows that could interfere with total user counts.
# 📈 Key Performance Indicators (KPIs) & Definitions
- To ensure data transparency, the following logic was used to calculate the core metrics displayed in the dashboard.
1. User Growth & Composition
- Total Users (1.05M): A distinct count of unique User IDs across the entire dataset.
- Premium Conversion Rate: Calculated as (Premium Users / Total Users) * 100. Currently, ~22% of the user base is on a Premium plan.
- Non-Binary & "Prefer Not to Say" Representation: Included to ensure inclusive demographic reporting, reflecting modern social media data standards.
 * 2. Engagement Metrics
* Avg Posts per Week (5.96): An average of total posts divided by the number of active weeks per user. This helps identify "Power Users" vs. "Lurkers."
* Avg Daily Minutes (188.35): The mean time spent in-app per session, aggregated daily. At over 3 hours, this indicates high platform stickiness.
* Avg Daily Steps (8.00K): A health-tracking metric used to correlate physical activity with digital screen time.
- 🔍 Advanced Analysis (DAX & Logic)
- The Stress Correlation Matrix: This section uses a matrix to identify if high app usage correlates with happiness/stress levels across different socioeconomic tiers globally.
- Content Theme by Gender: A clustered column chart analyzing preferred themes (Fitness, Food, Tech, etc.) segmented by Female, Male, Non-binary, and "Prefer not to say."
- Security Status: A verification metric tracking "Users by 2-Factor Authorization" to measure platform trust and security.
# 🔮 Forecasting & Predictive Analysis
This project leverages Power BI’s built-in forecasting models (exponential smoothing) to predict future trends based on 15 years of historical user data.
- 1. User Growth Projection (2025 - 2030)
- Methodology: Applied an Exponential Smoothing model to the "Number of Users Added per Year" dataset with a 95% confidence interval.
- Result: Forecasts suggest a steady increase in user acquisition, particularly in emerging markets like Brazil and South Africa, despite nearing platform saturation in     Urban USA.
- 2. Behavioral Trend Prediction: The "Stress Peak"
- Analysis: Based on the "Books Read vs. Stress Score" correlation, a trend analysis was performed to predict potential "digital burnout" phases.
- Insight: Forecasting indicates that without intervention in Reel consumption limits, average user stress scores could rise by 12% over the next fiscal year
# 🏁 Conclusion
- This project demonstrates the power of data storytelling by transforming over 1 million rows of raw social media data into a multi-layered analysis of user behavior. By bridging the gap between demographics and psychological wellness, this dashboard provides a 360-degree view of the modern digital user.
- Key Takeaways:
- Technical Proficiency: Demonstrated mastery of the full data lifecycle—from complex data cleaning in Power Query to advanced statistical modeling and forecasting in Power BI.
- Behavioral Insight: Proved that engagement isn't just a number; it correlates deeply with lifestyle factors like employment, education, and physical health.
- Security & Growth: Provided a roadmap for platform growth by identifying high-potential markets and quantifying the current state of user security (2FA).
# 📬 Contact & Portfolio
If you have any questions about the methodology or would like to discuss the findings further, feel free to reach out!
- LinkedIn: www.linkedin.com/in/ashu-verma-386046212
- Email: ashuv098verma@gmail.com
