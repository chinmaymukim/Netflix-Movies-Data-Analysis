🎬 Netflix Movies Data Analysis
Unlocking Insights from Ratings, Genres & Popularity

📊 A comprehensive exploratory data analysis (EDA) project that dives deep into Netflix-like movie data to uncover trends in genres, ratings, popularity, and release years using Python, Pandas, Matplotlib, and Seaborn.

🚀 Project Overview

This project analyzes a movie dataset inspired by Netflix content to extract meaningful insights about:

🎞️ Most frequent and popular movie genres

⭐ Distribution of movie ratings

🔥 Popularity trends across movies

📅 Year-wise movie production trends

🏆 Movies with highest and lowest popularity

The goal is to transform raw data into actionable insights that can support content strategy, recommendation systems, and business decisions.

🧰 Tech Stack & Tools

Programming Language: Python

Libraries Used:

NumPy – Numerical operations

Pandas – Data manipulation & cleaning

Matplotlib – Data visualization

Seaborn – Advanced visual analytics

📥 Dataset Description

The dataset (mymoviedb.csv) contains 9,827 movies with the following attributes:

Column Name	Description
Release_Date	Movie release year
Title	Movie title
Popularity	Popularity score
Vote_Count	Total number of votes
Vote_Average	Average rating
Genre	Movie genres
Original_Language	Language of the movie
Poster_Url	Movie poster link
Overview	Short description
🧹 Data Cleaning & Preprocessing

✔ Converted release dates into year format
✔ Removed unnecessary columns (Overview, Language, Poster URL)
✔ Checked and handled missing values
✔ Categorized Vote_Average into meaningful labels
✔ Split multi-genre movies and exploded them for accurate analysis
✔ Converted genres into categorical data types

📌 Result: Clean, structured dataset with 25,552 genre-level records

📊 Exploratory Data Analysis (EDA)
🎞️ Genre Analysis

Drama is the most frequent genre

Movies often belong to multiple genres, increasing content diversity

⭐ Ratings Distribution

Movies were categorized into:

not_popular

below_avg

average

popular

📈 Ratings are fairly evenly distributed, indicating a balanced dataset.

🔥 Popularity Insights

Lowest popularity movies:

The United States vs. Billie Holiday

Threads

High popularity often correlates with Action, Adventure, and Sci-Fi genres.

📅 Year-wise Movie Trends

Movie production increases significantly in recent years, showing Netflix’s expanding content strategy.

📈 Visualizations Included

Genre distribution bar chart

Vote average category distribution

Popularity comparison

Release year histogram

All visualizations were created using Seaborn & Matplotlib for clarity and storytelling.

🏆 Key Insights & Results

✅ Most Frequent Genre: Drama
✅ Balanced Rating Distribution: No extreme bias
✅ Content Boom: Recent years dominate movie releases
✅ Genre Diversity: Multi-genre movies are common
✅ Business Insight: Action & Drama dominate popularity metrics

🧩 Problems Solved

✔ Data cleaning & transformation

✔ Genre normalization using explode

✔ Rating categorization using quantiles

✔ Trend discovery via visual analytics

✔ Insight extraction for decision-making

💡 Use Cases

This analysis can serve as a foundation for:

🎯 Recommendation systems

📊 Content performance evaluation

📈 Business & marketing strategy

🤖 Machine learning models

📌 Conclusion

This project demonstrates my ability to:

Work with real-world datasets

Perform end-to-end exploratory data analysis

Apply data visualization to tell compelling stories

Extract insights that drive data-informed decisions

✨ A strong example of my data analysis and Python skills.

📬 Let’s Connect

If you found this project interesting or have suggestions, feel free to connect!
⭐ Don’t forget to star the repository if you like it.
