TMDB Movies Dataset Analysis

Project Overview

This project explores a dataset of 10,000 movies from TMDB (1960–2015) to uncover key trends and insights. The analysis focuses on relationships between movie metrics like popularity, revenue, and budget, as well as time-based and genre-based performance. The goal is to answer specific analytical questions and present findings using Python.

Dataset Description

The dataset contains information about movies, including:
	•	Budget and Revenue: Both in original USD and inflation-adjusted (2010 dollars).
	•	Popularity: Metric to measure movie popularity.
	•	Genres, Cast, and Directors: Key details about the movie production.
	•	Ratings and Votes: User engagement metrics.
	•	Release Dates: Spanning 1960 to 2015.

Original dataset from Kaggle, provided by Udacity for the Nanodegree program.

Questions Addressed

	1.	Do movies with high popularity achieve high revenue?
	2.	What are the most filmed genres in the dataset?
	3.	Is there a correlation between movie budgets and revenue?
	4.	Which genres generate the highest average revenue and ROI?
	5.	Are newer movies generally more popular?

Data Wrangling & Cleaning

	•	Steps Taken:
	•	Removed duplicates and unnecessary columns.
	•	Handled missing values.
	•	Converted release_date to appropriate data type.
	•	Created new columns: profit and categorized vote_average and profit.
	•	Final Dataset: 10,840 records and 10 key columns.

Tools Used

	•	Programming: Python
	•	Libraries: Pandas, NumPy, Matplotlib, Seaborn
	•	Environment: Jupyter Notebook

Key Findings

	1.	Popularity and Ratings:
	•	Highly rated movies tend to have high popularity.
	•	Action, Science Fiction, and Fantasy are the most popular genres.
	•	Movies with more votes are generally more popular.
	2.	Revenue and Budget:
	•	Adventure, Science Fiction, and Fantasy generate the highest revenue.
	•	Adventure, Comedy, and Horror deliver the best ROI.
	•	Longer movies (runtime > 150 minutes) tend to generate higher revenue.
	3.	Time-Based Analysis:
	•	2011 saw the highest number of movie releases.
	•	Average budgets peaked during the 1990s–2000s.
	•	Movie popularity resurged in the 2000s and peaked in the 2010s.


