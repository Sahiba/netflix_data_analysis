## Netflix Data Analysis and Visualization

### Overview

This project focuses on analyzing a dataset of Netflix titles, including movies and TV shows. The analysis involves reading, cleaning, transforming, analyzing, and visualizing the data to gain insights into Netflix’s content catalog.

### Dataset Details

### Columns:

	•	show_id: Unique identifier for each title.
	•	type: Indicates whether the title is a “Movie” or “TV Show.”
	•	title: Name of the movie or TV show.
	•	director: Name of the director (if available).
	•	country: Country of origin.
	•	date_added: Date the title was added to Netflix.
	•	release_year: Year the title was released.
	•	rating: Content rating (e.g., PG, TV-MA).
	•	duration: Duration of the movie or number of seasons (for TV shows).
	•	listed_in: Genres or categories (multiple possible).

### Analysis Tasks

1. Reading the Dataset

	*	Load the dataset into a pandas DataFrame
	*	Display the first 10 rows to get an overview of the data structure.

3. Data Cleaning

	•	Handle Missing Values: Replace or drop rows/columns with missing values, focusing on director and country.
	•	Date Formatting: Convert the date_added column to a datetime format.
	•	Standardize Duration: Create:
	•	duration_min: Movie durations in minutes.
	•	seasons: Number of seasons for TV shows.
	•	Duplicates: Remove duplicate rows.

4. Data Transformation

	•	Categorical Encoding: Transform type, rating, and listed_in into categorical variables.
	•	Create Decade Column: Group release_year into decades (e.g., 1990s, 2000s, 2010s).
	•	Duration Binning: Categorize movies based on duration:
	•	Short: <90 minutes.
	•	Medium: 90–120 minutes.
	•	Long: >120 minutes.

5. Data Analysis

	•	Top Genres: Identify the top 5 most frequent genres/categories.
	•	Country Contribution: Analyze which countries contribute the most titles to Netflix.
	•	Rating Distribution: Investigate the distribution of content ratings across movies and TV shows.
	•	Director Activity: Find the top 5 most prolific directors based on the number of titles directed.
	•	Yearly Content Trend: Analyze trends in the number of titles added to Netflix over the years.
	•	Average Movie Duration: Calculate the average duration of movies.

6. Data Visualization

	•	Genre Popularity: Bar plot for the top 5 genres.
	•	Country Contribution: Horizontal bar plot for the top 10 countries.
	•	Rating Distribution: Pie or bar chart showing content rating distributions.
	•	Yearly Trends: Line plot showing the number of titles added each year.
	•	Movie Length: Histogram showing the distribution of movie lengths.

### How to Use

	1.	Clone this repository.
	2.	Load the netflix_data.csv file into your working environment.
	3.	Follow the notebook steps to complete the analysis and visualization tasks.

### Future Improvements

	•	Incorporate advanced visualizations with interactive dashboards.
	•	Analyze trends by combining Netflix data with external datasets like IMDb scores.
	•	Develop predictive models to analyze future Netflix trends.
