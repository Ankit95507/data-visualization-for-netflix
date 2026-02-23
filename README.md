data-visualization-for-netflix
Technologies Used: Python, NumPy, Pandas, Matplotlib, Seaborn
​

Description:
Comprehensive data visualization project analyzing Netflix User/Content Dataset from Kaggle (8,800+ titles, 12 features: title, type, country, release_year, rating, duration, genres, etc.). Performed extensive data manipulation using Pandas/NumPy for cleaning, missing value handling (omitted minor gaps <5%), and feature engineering (genre extraction, duration parsing). Created 12+ publication-ready visualizations using Matplotlib/Seaborn to uncover Netflix's content strategy, growth patterns, and audience preferences.

Visualizations Created:

📊 Bar Charts
Most Watched Content by Genre: Drama (37%), Comedy (25%), International Movies (15%) dominate

Top Countries by Content Volume: US (4,200+ titles, 48%), India (1,200+, 14%), UK (500+)

Content by Rating: TV-MA (mature) leads at 32%, followed by TV-14 (28%)

🥧 Pie Charts
Movies vs TV Shows: Movies (61%) vs TV Shows (39%) – Movies heavily dominate

Age Rating Distribution: Mature content (TV-MA/TV-14) = 60% of catalog

Release Decade Breakdown: 2010s (45%), 2020s (25%), 2000s (20%)

📈 Scatter Plots
Release Year vs Duration: Movies average 97min, TV shows 1-2 seasons; correlation shows longer runtimes post-2015

Content Volume vs Country GDP: US/India outliers with massive output despite economic disparity

Rating vs Popularity: Higher ratings correlate with longer durations (R=0.42)

🔥 Additional Advanced Visuals
Area Chart: Movies vs TV shows addition trends (2019 peak, COVID decline 2020+)

World Map: Average movie duration by country (Western <97min vs South Asia >107min)

Box Plot: Duration outliers by genre (Documentaries longest median 92min)

Heatmap: Genre co-occurrence (Drama+Comedy most frequent pairing)

Key Insights Generated:

Movies dominate (61%) but TV shows growing faster post-2020

US/India control 62% of content despite global reach

Mature content bias: 60% TV-MA/TV-14 ratings

2019 Peak: 700+ titles added before pandemic slowdown

Data Pipeline:

text
Raw Kaggle CSV (8.8K rows) → Pandas Cleaning → NumPy Stats → Matplotlib/Seaborn Plots → Insights
Missing values: <5% omitted | Duration parsing: min→int | Genres: string split
