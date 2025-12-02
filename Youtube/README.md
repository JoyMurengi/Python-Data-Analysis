## YouTube Statistics Analysis Project
### Overview

This project examines global YouTube performance data for 2023 to reveal trends, patterns, and insights that explain what drives success on the platform. The dataset contains information on top YouTube channels worldwide, including subscribers, total views, estimated earnings, content categories, and country-level indicators.

### Dataset

The analysis uses the Kaggle dataset "Global YouTube Statistics 2023" (995 channels). Key columns include:

Youtuber – Channel name

Subscribers – Total number of subscribers

Video Views – Lifetime video views

Uploads – Number of uploaded videos

Category – Content type (Music, Gaming, Education, etc.)

Country – Country of origin

Earnings – Estimated monthly and yearly earnings

Subscribers (Last 30 Days) – New subscribers in the last 30 days

Video Views (Last 30 Days) – Views gained in the last 30 days

Created Year – Year the channel was created

Channel Type / Channel Type Rank – Classification and ranking by channel type

Video Views Rank / Country Rank – Ranking by views and country presence

Lowest/Highest Monthly & Yearly Earnings – Estimated income ranges

Socioeconomic Indicators – Tertiary education enrollment, population, unemployment rate, urban population

Latitude / Longitude – Country geographic coordinates

### Data Cleaning

Preprocessing steps applied before analysis:

Removed irrelevant columns
Dropped fields such as Abbreviation, created_month, Latitude, and Longitude as they were not needed for the core analysis.

Handled missing values

Dropped rows missing critical fields like Country, created_year, and channel_type_rank.

Replaced missing numeric values (e.g., subscribers_for_last_30_days, video_views_for_the_last_30_days) with the median.

Filled categorical gaps (category, channel_type) with the mode.

Standardized dates
Converted created_year to a datetime-compatible format for time-based analysis.

### Analyses & Key Insights
1. Top 10 Channels by Average Video Views

Identified the ten channels with the highest average views per video.

Insight: Top channels are often from Shows, Music, and People & Blogs, indicating these categories consistently generate large audience interest.

2. Average Views per Upload for Top Creators

Measured average views per upload for leading creators.

Insight: This highlights whether creators benefit more from frequent uploads or from producing fewer, higher-quality videos.

3. Relationship Between Subscribers and Total Video Views

Explored correlation between subscriber counts and total views using a scatter plot.

Insight: There is a strong positive correlation—channels with more subscribers generally accumulate more views. Outliers (high subscribers but low views) may indicate inactivity or irregular posting.

4. Average Views and Subscribers by Category

Compared average views and subscriber counts across content categories with bar charts.

Insight:

Shows, Trailers, and Film & Animation attract the largest audiences.

Niche categories (e.g., Science & Technology, Travel & Events) have smaller but often more engaged audiences.
Creators can choose broad categories for rapid growth or niches for deeper engagement.

5. Earnings Distribution Across Categories

Analyzed estimated monthly and yearly earnings by category.

Insight: Entertainment categories (especially Shows and Music) show the highest earning potential. Niche categories can still be profitable when creators sustain strong engagement. Wide earning ranges indicate revenue depends heavily on popularity and engagement.

6. Countries with the Most Popular Channels

Ranked countries by the number of top-performing channels.

Insight: The United States, India, and Brazil lead, driven by large populations, high internet use, and active creator communities. These markets are prime targets for audience growth.

### Conclusion

This analysis surfaces important factors that influence YouTube success: subscriber growth, view patterns, earnings potential, and geographic distribution. Creators and marketers can use these insights to refine content strategy, boost engagement, and improve monetization.

### Next steps / Recommendations:

Focus content strategy on categories aligned with growth goals (broad reach vs. niche engagement).

Monitor both short-term (30-day) and lifetime metrics to detect shifts in channel momentum.

Localize content or target campaigns in high-opportunity countries (e.g., USA, India, Brazil).
