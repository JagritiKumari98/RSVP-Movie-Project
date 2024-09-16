# RSVP-Movie-Project
RSVP Movies Data Analysis
Project Overview
This project analyzes movie data using MySQL, focusing on key insights such as genre popularity, release patterns, and movie ratings. The goal is to understand which genres and production companies perform well and how movie release trends vary, particularly in March, the peak release month.

Key Findings
Movie Data Gaps: The dataset contains essential columns like title, year, duration, and production_company, but some fields have null values.
March Dominance: March sees the highest number of movie releases, making it a significant month for movie debuts.
Genre Popularity: Drama is the most produced genre, with an average duration of 107 minutes. Thriller ranks in the top 3 for production volume.
Movie Ratings: Ratings range from 1 to 10, with a median rating of 7. The top 10 movies average 9.6 in ratings.
Production Companies: Production houses like Dream Warrior Pictures and National Theatre Live consistently produce highly-rated movies (average rating > 8).
Country-Based Insights: German movies typically receive more votes per movie compared to Italian ones, indicating stronger audience engagement.
Recommendations
Focus on Drama and Thriller: Given their high production and popularity, prioritizing these genres can increase success.
Target March Releases: Releasing movies in March aligns with industry trends and could optimize visibility.
Database Information
The MySQL database contains key tables and columns:
Movies Table: Stores movie details such as title, year, duration, genre, and production_company.
Ratings Table: Stores movie ratings and audience votes.
Production Companies Table: Contains information about the production houses.
Data Gaps and Cleaning
Null values in fields like title, year, duration, and production_company were handled during data cleaning.
Project Structure
Data Preprocessing: Cleaned and prepared the MySQL database by handling missing data.
Genre Analysis: Analyzed popular genres and their average duration using SQL queries.
Ratings and Votes: Examined movie ratings and votes distribution across countries.
Release Trends: Analyzed seasonal movie releases, highlighting March as the peak release month.
Tools Used
MySQL
MySQL Workbench (IDE)
Python (Pandas, NumPy, Matplotlib, Seaborn) for additional data analysis and visualization.
