🎬 Netflix Content Analysis Dashboard

🧭 Table of Contents

📌 Project Title & Short Description

❓ Problem Statement

🎯 Business Objectives

🧠 Project Objective / Summary

🗂️ Dataset / Data Source

🧰 Tools / Technologies Used

⚙️ Steps / Methodology

📊 Analysis / Dashboard Creation and Screenshots

🔍 Insights & Findings

💼 Business Impact

🧩 Challenges & Learnings

🔮 Future Improvements

🧑‍💻 Installation Instructions

▶️ Usage / How to Run

🌐 Live Demo / Deployment Link

📚 References / Resources

👥 Authors / Contributors

⚖️ License

📌 Project Title & Short Description

Netflix Content Analysis Dashboard — a comprehensive data analytics and visualization project exploring Netflix’s global content trends across countries, genres, durations, and release years.

It combines Python-based data preprocessing with Tableau dashboards to uncover insights into Netflix’s evolving content strategy and audience focus.

❓ Problem Statement

With over 8,000 titles from 190+ countries, Netflix faces the challenge of understanding content performance and distribution patterns.
This project addresses key questions such as:

Which countries produce the most Netflix content?

What are the most common genres and ratings?

How has Netflix’s content evolved over time?

What’s the average duration of movies and number of seasons for TV shows?

By analyzing historical Netflix data, we aim to discover meaningful insights that support content strategy, audience targeting, and investment planning.

🎯 Business Objectives

Identify top-performing countries and genres for Netflix content.

Understand growth trends over time to support production forecasting.

Compare Movies vs TV Shows in terms of volume and trends.

Derive duration and season-based insights for strategic planning.

Build interactive Tableau dashboards for business decision support.

🧠 Project Objective / Summary

This end-to-end analytics project demonstrates how raw OTT data can be cleaned, processed, and transformed into actionable business insights.

The analysis helps Netflix answer:

What genres or formats drive engagement?

Which markets contribute the most?

How content types differ by duration, rating, and time period?

The final output — two interactive Tableau dashboards — visually communicate these findings to business stakeholders.

🗂️ Dataset / Data Source

Dataset Name: Netflix Movies and TV Shows

Source: Kaggle - Netflix Titles Dataset

Total Records: 8,807

Key Columns:
show_id, type, title, country, date_added, release_year, rating, duration, listed_in

Processed Fields Created:

Main Genre (from listed_in)

Duration Minutes (numeric format for movies)

Seasons (numeric for TV shows)

Content Age (current year - release year)

🧰 Tools / Technologies Used
Category	Tools
Programming	Python, Jupyter Notebook
Data Processing	Pandas, NumPy
Visualization	Tableau, Matplotlib, Seaborn
Dashboarding	Tableau Public
Documentation	Markdown, GitHub
Data Source	Kaggle Netflix Dataset
⚙️ Steps / Methodology
1️⃣ Data Loading & Inspection

Imported raw data from Kaggle using Pandas.

Checked for missing values, duplicates, and data types.

2️⃣ Data Cleaning & Transformation

Handled missing values in director, cast, and country.

Normalized text columns (genre, duration, rating).

Created calculated fields:

Main Genre → Primary genre extraction

Duration Minutes → Numeric value for movie durations

Seasons → Extracted from TV show durations

Year Added and Month Added from date_added

3️⃣ Exploratory Data Analysis

Analyzed content types (Movies vs TV Shows).

Found top 10 producing countries and most frequent genres.

Visualized trends in content additions by year.

4️⃣ Dashboard Creation

Built two Tableau Dashboards:

Netflix Overview Dashboard
Covers overall content mix, top countries, growth trends, and rating distribution.

Genre & Duration Insights Dashboard
Deep dive into genre trends, movie duration averages, and TV season distribution.

📊 Analysis / Dashboard Creation and Screenshots
🎬 Netflix Content Overview Dashboard

This dashboard summarizes the distribution of content across countries, years, ratings, and type (Movie/TV Show).
It provides a high-level understanding of Netflix’s growth and diversification.

🎭 Genre & Duration Insights Dashboard

Focuses on top genres, movie durations, and TV season counts.
Useful for production teams analyzing audience interest and runtime efficiency.

🔍 Insights & Findings

Massive Growth Post-2015:
Netflix’s content library tripled between 2015–2020.

Global Content Shift:
The USA leads in volume, followed by India, UK, and Japan.

Genre Focus:
“International TV Shows” and “Dramas” are the most common categories.

Duration Patterns:
Average movie length ≈ 90 mins; Documentaries are shortest.

TV Seasons:
Majority of shows have 1–3 seasons — aligns with binge-watch model.

Ratings Distribution:
Family-friendly content (TV-MA, TV-14) dominates the catalog.

💼 Business Impact
Area	Impact
Content Planning	Identifies genres and countries driving engagement.
Production Strategy	Duration and season patterns guide content investment.
Market Expansion	Highlights regions (India, US) for localized production.
Viewer Retention	Data-driven storytelling helps in curating high-demand genres.
Forecasting	Year-over-year growth trends aid strategic forecasting.
🧩 Challenges & Learnings
⚙️ Challenges

Handling inconsistent duration formats (“90 min”, “2 Seasons”).

Extracting first genre from multi-genre entries.

Managing null values in fields like country, rating, and date_added.

Designing dashboards with clear filters and responsive layout.

🧠 Learnings

Deepened understanding of data cleaning pipelines.

Learned regex operations for numeric extraction.

Gained proficiency in Tableau calculated fields and dashboard design.

Understood how to link EDA findings with business outcomes.

🔮 Future Improvements

Add IMDb ratings and sentiment analysis to enrich insights.

Automate updates with a Python ETL pipeline (scheduled refresh).

Integrate Machine Learning for content recommendation or trend prediction.

Create a Streamlit web app to explore dashboards interactively.

Expand analysis to include competitors like Prime Video or Disney+ for comparison.

🧑‍💻 Installation Instructions
# Clone repository
git clone https://github.com/<your-username>/Netflix_Content_Analysis.git

# Navigate to project
cd Netflix_Content_Analysis

# Install dependencies
pip install -r requirements.txt

▶️ Usage / How to Run

Open the notebooks in /notebooks/ for Python analysis.

View Tableau dashboards in /tableau_dashboards/Netflix_Overview_Dashboard.twbx.

Refer to /visuals/ for exported EDA graphs and plots.

🌐 Live Demo / Deployment Link

🔗 Tableau Public: View Dashboard

📚 References / Resources

Netflix Dataset (Kaggle)

Tableau Public Help Docs

Pandas Documentation

Matplotlib + Seaborn User Guide

👥 Authors / Contributors

👤 Author: Suriya
📧 Email: suriyasanchez@gmail.com

📍 Location: Chennai, India
🌍 LinkedIn
 | Tableau Public

⚖️ License

This project is licensed under the MIT License — free for educational and analytical use.

✅ Final Note:
This project demonstrates end-to-end Data Analysis Lifecycle — from data ingestion and cleaning in Python to business visualization in Tableau — providing a complete picture of Netflix’s evolving content ecosystem.

It reflects strong analytical, visualization, and storytelling skills suitable for Data Analyst, BI Developer, or Data Visualization roles.