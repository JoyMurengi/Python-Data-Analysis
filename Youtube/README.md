YouTube Statistics Analysis Project
Overview

This project explores global YouTube performance data for the year 2023 to uncover trends, patterns, and insights that explain what contributes to success on the platform. The dataset covers information about top YouTube channels worldwide, including subscriber counts, total video views, estimated earnings, content categories, and country-specific indicators.

Dataset

The analysis uses a dataset from Kaggle titled “Global YouTube Statistics 2023.” It contains 995 YouTube channels and includes a wide range of key attributes:

Youtuber – Channel name

Subscribers – Total number of subscribers

Video Views – Lifetime video views

Uploads – Number of uploaded videos

Category – Content type (Music, Gaming, Education, etc.)

Country – Country of origin

Earnings – Estimated monthly and yearly earnings

Subscribers (Last 30 Days) – Newly acquired subscribers

Video Views (Last 30 Days) – Views gained recently

Created Year – Year the channel was launched

Channel Type / Channel Type Rank – Type classification and ranking

Video Views Rank / Country Rank – Rank based on views and country presence

Lowest/Highest Monthly and Yearly Earnings – Income estimates

Socioeconomic Indicators – Education enrollment, population, unemployment rate, urban population

Geographic Coordinates – Latitude and longitude

Data Cleaning

Several preprocessing steps were applied to improve data quality:

Removed Irrelevant Columns
Eliminated fields such as Abbreviation, created_month, Latitude, and Longitude due to lack of usefulness in the analysis.

Handled Missing Values

Removed entries missing key fields like Country, created_year, and channel_type_rank.

Filled numerical gaps (e.g., subscribers_for_last_30_days, video_views_for_the_last_30_days) using median values.

Filled missing categorical entries (category, channel_type) using mode.

Standardized Dates
Converted created_year into a datetime format for accurate time-based insights.

Data Analysis & Insights
1. Top 10 YouTubers by Average Video Views

Identified the highest-performing YouTube channels globally based on average views per video.

Key Insight:
Most top performers fall under Shows, Music, and People & Blogs, emphasizing the broad appeal of these categories.

2. Average Views per Upload for Top Creators

This section examines how many views top creators get for each video on average.

Key Insight:
The findings help determine whether creators benefit more from frequent uploads or from producing fewer but higher-quality videos.

3. Relationship Between Subscribers and Total Video Views

A scatter plot analysis explores whether subscriber count correlates with total view count.

Key Insight:
There is a clear positive correlation between subscribers and views, though some large channels with low views indicate inactivity or inconsistent posting patterns.

4. Average Views and Subscribers by Category

Bar chart comparisons highlight how various YouTube content categories perform.

Key Insight:

Categories like Shows, Trailers, and Film & Animation attract large followings.

Niche categories such as Science & Technology or Travel & Events have smaller yet loyal audiences.
This shows creators can choose between broad reach and niche engagement depending on their strategy.

5. Earnings Distribution Across Categories

Analyzes income variation across different categories based on estimated monthly and yearly earnings.

Key Insight:
Entertainment-driven categories—especially Shows and Music—rank highest in earnings. While smaller categories generate less revenue, strong audience loyalty can still lead to profitable results.

6. Countries with the Most Popular YouTube Channels

Ranks countries based on the number of top-performing YouTube channels.

Key Insight:
The USA, India, and Brazil lead globally due to their large populations, high internet usage, and active creator ecosystems. These regions represent valuable target audiences.

Conclusion

This project highlights the major factors influencing YouTube channel success, including subscriber growth, video views, revenue potential, and regional distribution. Understanding these dynamics can help content creators and brands refine their strategies, improve engagement, and maximize monetization.

Whether you're a creator seeking to grow or a marketer studying digital trends, these insights provide a solid foundation for optimizing YouTube performance.
