📊 Netflix Content Analysis – Power BI Project
📝 Project Overview
This Power BI project explores Netflix’s content library using a publicly available dataset. The goal is to uncover insights into Netflix's global content strategy, genre distribution, content ratings, and trends over time using interactive dashboards.

🎯 Problem Statement
"What does Netflix’s content library reveal about its content strategy across different countries, genres, release periods, and audience types?"

The analysis aims to answer questions such as:

What is the composition of Netflix’s library by type, country, and rating?

Which countries and genres dominate the platform?

How has content evolved over time?

What is the distribution of content by audience rating?

📁 Dataset
Source: Kaggle - Netflix Movies and TV Shows

File: netflix.csv

Fields:

show_id, type, title, director, cast, country, date_added, release_year, rating, duration, listed_in, description

📊 Dashboards Created
1. 📦 Content Overview Dashboard
Total Titles, Movies, and TV Shows

Total contributing countries

Top 3 countries by content count

KPIs and donut charts for content type split

2. 🎭 Content Type & Genre Dashboard
Stacked bar: Content Type vs Genre

Treemap: Top 15 Genres

Pie chart: Ratings distribution by Type

Slicers: Genre & Type

3. 🌍 Geographic Distribution Dashboard
Map: Count of Titles by Country

Bar Chart: Top 10 Countries by content

Matrix: Country vs Genre

Slicer: Filter by Country

4. 📈 Time Trends Dashboard
Line chart: Titles added per year by Type

Multi-line chart: Genre trends over time

Histogram: Releases per year

Filters: Year Added, Release Year

5. 🎯 Content Ratings & Audience Dashboard
Bar chart: Titles by Rating

Grouped Bar: Rating vs Type

Donut Chart: Ratings by Genre

Slicers: Rating, Type

⚙️ Power BI Features Used
Power Query for data cleaning (genre & country splitting, null handling)

Custom columns (Year Added, Genre Cleaned, Country Cleaned)

Slicers and page-level filters

Page Navigation with icons for multi-dashboard experience

Conditional formatting in Matrix visuals

DAX Measures for KPIs and year-wise trends

🧠 Key Insights
The US dominates Netflix’s content, followed by India and the UK

Most content is geared toward mature audiences (TV-MA, R)

Drama, International, and Documentaries are the most common genres

Content addition spiked after 2016

Genres like Anime and Reality TV have grown rapidly in recent years

📌 Tools Used
Power BI Desktop

Power Query

DAX (Calculated Columns & Measures)

🧩 Future Enhancements
Add audience sentiment analysis using reviews (external sources)

Predict genre trends using Python/R in Power BI

Build a recommendation simulation using filters and logic

🙋‍♂️ Author
[Your Name]
Business/Data Analyst | Power BI Enthusiast

[[LinkedIn Profile](https://www.linkedin.com/in/bhavyabalyan/)] | [[Portfolio] (https://www.datascienceportfol.io/bhavyabalyan)] | [GitHub] - https://github.com/BhavyaBalyan]




