📺 Netflix Shows Exploratory Data Analysis (EDA)
This project explores the Netflix titles dataset from Kaggle, containing information on TV Shows and Movies available on Netflix. The analysis includes data cleaning, handling missing values, and visualization of trends across type, country, and time.

📂 Dataset
Source: Netflix Shows Dataset on Kaggle
File used: netflix_titles.csv

Key fields:
type → Movie or TV Show
title → Name of the content
director, cast, country → Metadata
date_added → When added to Netflix
release_year → Original release year
rating → Content rating (PG, TV-MA, etc.)
duration → Runtime (movies) or seasons (TV shows)
listed_in → Genre(s)
description → Synopsis

🛠 Steps Performed
🔹 Data Cleaning
Checked for missing values.
Replaced missing director, cast, country with "No Data".
Dropped duplicates and remaining nulls.
Converted date_added to datetime.

🔹 Exploratory Analysis & Visualizations
Movie vs TV Show Distribution
Horizontal stacked bar showing proportions of movies vs TV shows.
Content by Country
Top 10 countries producing Netflix content.
Split by movies vs TV shows (100% stacked bar).
Content Added Over Time
Area chart showing growth of movies and TV shows by year.
Content Added by Month
Seasonal patterns of when Netflix adds most content.
Lag Between Release Year & Netflix Addition
Gap between when content was released and when it was added to Netflix.
Separate analyses for Movies and TV Shows.

📊 Key Insights
Movies dominate Netflix’s catalog (around 70%+).
United States, India, and the UK lead in content production.
Netflix has accelerated TV Show additions in recent years, catching up to movies.
Seasonal peaks: content tends to be added around July–September and December.
On average, content is added to Netflix a few years after release, but this varies by country.

📈 Visualizations
The notebook generates:
Stacked bar charts
Area charts (content growth)
Bar charts (top countries)
Line/scatter plots (lag analysis)

⚙️ Tech Stack
Python (Pandas, NumPy, Matplotlib)
Kaggle environment for execution

📌 How to Run
Clone/download the repo or open Kaggle notebook.
Place netflix_titles.csv inside /input/ folder.
Run the notebook to reproduce the analysis & charts.

📝 Future Work
Perform genre-level analysis (which genres dominate by country/year).
Add text analysis on descriptions (sentiment, keyword trends).
Build a recommendation engine prototype.

🏆 Outcome
This analysis provides a clear understanding of Netflix’s content library structure, growth trends, and global diversity.
