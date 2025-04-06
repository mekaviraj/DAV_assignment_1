# DAV_assignment_1

📘 Dataset Information – IMDb Movie Dataset

This dataset contains detailed information about movies and shows listed on IMDb.

🔹 Columns:

id → Unique identifier for each movie/show

title → Name of the movie or show

genre → Genre category (e.g., Drama, Action, Comedy)

rating → IMDb rating (e.g., 8.2)

year → Year of release

votes → Number of user votes

duration → Runtime in minutes

certificate → Age rating (e.g., PG-13, R, U)

description → Short summary or plot of the movie/show

director → Name(s) of the director(s)

stars → Main actors/actresses

📌 Source: IMDb Movie Dataset (Kaggle or IMDb official sources)

-------------------------------------------------------------------------------------------

IMDb Movie Dataset Analysis
Overview
This project is based on analyzing an IMDb movie dataset using Python. The goal is to explore patterns in movie ratings, durations, genres, and certifications using basic data analysis techniques.

Tools & Libraries Used

Python: Main language used

Pandas: For loading, cleaning, grouping, and pivoting data

Google Colab: Platform used to write and run the code

 Steps Performed

Data Cleaning & Preparation

Loaded IMDb data using pandas

Dropped missing values using dropna()

Converted columns like "certificate" and "genre" to category type for easier analysis

GroupBy Operations

Counted number of movies per genre, certificate, and year

Found average ratings and durations grouped by certificate and genre

Found which genre and certificate had the highest-rated movie

Used idxmax to get top movies in different categories

Pivot Tables

Created pivot tables to find average rating and duration per certificate and genre

Performed multiple aggregation functions (min, max, mean) on ratings and durations

Counted number of movies per genre and certificate using pivot tables

📌 Conclusion
This project used pandas GroupBy and pivot_table to explore how movies differ based on genre, certificate, and other attributes. It helped identify patterns such as which genres or certificates have longer or higher-rated movies.
