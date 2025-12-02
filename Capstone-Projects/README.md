#Capstone-Projects
# 🌍 East Africa Digital Connectivity
**Tracking Mobile & Internet Growth Across East Africa**

---

## Project Description
East Africa Digital Connectivity explores how access to mobile and internet services has evolved across East African countries from 2000–2023. Using publicly available World Bank and ITU datasets, the project analyzes adoption trends, regional disparities, and growth patterns, and examines how digital connectivity correlates with socioeconomic factors such as GDP per capita and urbanization.

Through data cleaning, exploratory analysis, and interactive visualizations in Streamlit, the project provides a clear picture of how digital infrastructure is expanding — and which countries are leading or lagging.

---

## Problem Statement
Digital connectivity is a critical driver of economic growth, innovation, and social inclusion. While East Africa has experienced rapid mobile and internet penetration over the last two decades, progress is uneven across countries and regions.

Many rural and low-income populations remain underserved due to gaps in infrastructure, affordability, and digital literacy. Without a clear understanding of these disparities, policymakers risk making decisions that leave vulnerable communities behind.

This project addresses the gap by leveraging open data to:
- Identify **trends** in mobile and internet adoption.
- Highlight **regional leaders and laggards**.
- Provide **data-driven recommendations** for inclusive digital development.

---

## Research Questions
1. **RQ1:** How have mobile subscriptions and internet usage evolved over time in East Africa?
2. **RQ2:** Which East African countries have the highest and lowest internet penetration in the latest year?
3. **RQ3:** What is the relationship between GDP per capita, urbanization, and internet usage?
4. **RQ4:** What is the share of total East African mobile subscriptions by country?
5. **RQ5:** How does the variability of mobile subscriptions differ across countries over the last 10 years?
6. **RQ6:** How has fixed broadband adoption grown compared to mobile internet?
7. **RQ7:** What is the distribution of GDP growth rates in East Africa over the years?
8. **RQ8:** How does internet penetration vary geographically across East Africa?
---

## Target Audience
- **Policymakers:** For planning digital infrastructure investments and bridging the connectivity gap.
- **Telecom Regulators:** To monitor adoption trends and evaluate policy effectiveness.
- **Researchers & Economists:** To study the link between connectivity and economic growth.
- **NGOs & Development Agencies:** To design targeted programs for underserved communities.

---

## Planned Features
- **Data Collection & Cleaning:** Fetch World Bank open data via API, clean and preprocess using Pandas & NumPy.
- **Exploratory Data Analysis (EDA):** Identify trends, patterns, and correlations.
- **Geospatial Mapping:** Use GeoPandas + Folium/Plotly to visualize country-level disparities.
- **Interactive Dashboard:** Build with Streamlit to allow users to explore data by year, country, and indicator.
- **Insights & Recommendations:** Summarize findings with evidence-backed explanations.

---

## Technologies / Concepts
- **Python:** Data fetching, wrangling, and visualization.
- **Pandas / NumPy:** Data manipulation.
- **Altair / Plotly:** Interactive visualizations.
- **GeoPandas / Folium:** Geospatial analysis and mapping.
- **Streamlit:** Interactive web application.
- **World Bank API:** Primary data source.

---

## Data Sources
- **World Bank Data API** – Indicators:
  - Mobile subscriptions per 100 people (IT.CEL.SETS.P2)
  - Internet users (% of population) (IT.NET.USER.ZS)
  - GDP per capita (NY.GDP.PCAP.CD)
  - Urban population (% of total) (SP.URB.TOTL.IN.ZS)
  - Fixed broadband subscriptions (IT.NET.BBND.P2)
- **ITU** – Complementary telecom statistics.

---

## Success Criteria
The project will be considered successful if it:
- Cleans and integrates data for all East African countries from 2000–2023.
- Produces an interactive Streamlit dashboard with multiple chart types.
- Answers each research question with clear data-driven insights.
- Provides practical recommendations for policymakers and stakeholders.

---
## Website   https://connect-eastafrica-insights.lovable.app/
