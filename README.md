# Netflix_report_by_Using_Power_BI
1. Introduction
Netflix is one of the leading streaming platforms globally, offering thousands of movies and TV shows across multiple genres and languages.
With increasing competition from Amazon Prime, Disney+, and other platforms, it is crucial to analyze Netflix’s content library to understand its trends, strengths, and opportunities for expansion.

2.This project focuses on analyzing Netflix’s dataset to extract insights related to:
Content distribution (Movies vs TV Shows).
Trends over time.
Popular genres, ratings, and countries.
Potential gaps in content strategy.

3. Dataset Overview
Source: Kaggle – Netflix Movies & TV Shows Dataset
Total Records: ~8,800 titles
Key Columns:
type → Movie or TV Show
title → Name of the show/movie
director → Director(s)
cast → Actors
country → Country of production
date_added → When it was added to Netflix
release_year → Original release year
rating → Content rating (TV-MA, PG, R, etc.)
duration → Duration in minutes / seasons
listed_in → Genres

4. Methodology
Data Cleaning:
Removed null values in director, cast, country.
Converted date_added to datetime format.
Extracted new columns: year_added, month_added.
Split duration into minutes (for movies) and seasons (for TV shows).
Exploratory Data Analysis (EDA):
Content trends by year.
Country-wise distribution.
Genre and rating analysis.
Duration insights.
Visualization Tools:
Python (pandas, matplotlib, seaborn).
Power BI (for interactive dashboards).
5. Key Findings

4.1 Movies vs TV Shows
Movies: ~70% of total content
TV Shows: ~30%
Movies still dominate Netflix’s library, but TV shows have grown significantly since 2015.
4.2 Content Growth Over Time
Major spike in content additions between 2015–2020.
Highest number of additions: 2019.
Post-2020, growth slowed due to COVID-19 production challenges.
4.3 Top Content-Producing Countries
United States – Highest number of titles.
India – Large growth in movies and TV shows, especially after 2017.
United Kingdom – Strong contributor in both movies and series.
Insight: Netflix focuses heavily on US content, followed by India and UK, showing global expansion efforts.
4.4 Genre Insights
Popular Genres: Dramas, Comedies, Documentaries, Action & Adventure.
Family/Kids content is limited compared to adult-targeted genres.
4.5 Ratings Distribution
TV-MA (Mature Audience) dominates → 40%+ content.
PG & TV-Y (family/kids) much less → only ~10%.
Netflix mainly targets adult audiences.

5. Visualizations (suggested for dashboard)
Pie Chart: Movies vs TV Shows.
Line Chart: Content growth trend (year-wise).
Map Visualization: Country-wise distribution.
Bar Chart: Top genres and ratings.

6. Insights & Recommendations
Adult-oriented dominance: Netflix should balance its library by adding more family-friendly content.
Regional expansion: India shows strong growth → Netflix should continue investing in regional languages.
TV Shows trend: Increasing demand for TV shows suggests Netflix should prioritize long-running series to build engagement.
Documentaries rise: Growing interest in documentaries presents an opportunity to expand in this niche.

7. Conclusion
This project highlights Netflix’s strategic focus on movies and adult-rated content, while also showing growth in TV shows and regional expansion. By diversifying into family-oriented content and expanding long-running series, Netflix can further strengthen its position in the competitive OTT market.
