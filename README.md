# Netflix Movie Data Analysis

## Project Overview
This project performs Exploratory Data Analysis (EDA) on a movie dataset to understand trends in movie popularity, ratings, and genres. The analysis focuses on cleaning the dataset, transforming variables, and generating insights through visualizations.
The goal of the project is to extract meaningful insights from movie data using Python data analysis libraries.

## Dataset Information
The dataset contains 9,837 movies with 9 columns.

### Main Features
-	Title - Name of the movie
-	Genre - Movie genres (comma separated)
-	Popularity - Popularity score of the movie
-	Vote_Count - Number of votes received
-	Vote_Average - Average rating
-	Release_Date - Movie release date
-	Overview - Movie description
-	Original_Language - Language of the movie
-	Poster_URL - Poster link

## Technologies Used
The project is implemented using the following Python libraries:
-	Python
-	Pandas - Data manipulation
-	NumPy - Numerical operations
-	Matplotlib   Data visualization
-	Seaborn - Statistical visualizations
-	Jupyter Notebook

## Data Cleaning Process
Several preprocessing steps were performed:
1.	Handled missing values in the dataset
2.	Converted data types:
- Vote_Count -> Integer
- Vote_Average -> Float
3.	Converted Release_Date to datetime and extracted the year
4.	Removed unnecessary columns:
- Overview
- Original_Language
- Poster_URL
5.	Identified and examined outliers in Popularity

## Feature Engineering
Additional transformations were performed:

### Rating Categorization
The Vote_Average column was categorized into:
-	Popular
-	Average
-	Below Average
-	Not Popular
This helped in better understanding the distribution of movie ratings.

### Genre Processing
- The Genre column contained multiple genres separated by commas.
-	It was split and exploded so that each row represents one genre per movie.

## Exploratory Data Analysis
The project explores several analytical questions:
-	Which genres are most common?
-	Which movies have the highest popularity?
-	How does rating distribution vary?
-	What genres receive higher average ratings?
-	Relationship between popularity and votes.
Visualizations were created to better understand patterns in the dataset.

## Data Visualization
Visualizations were created using Matplotlib and Seaborn, including:
-	Genre distribution charts
-	Popularity distribution
-	Rating category analysis
-	Genre vs rating comparisons
-	Popularity trends
These charts help identify patterns in movie popularity and ratings.

## Key Insights
-	Certain genres dominate the movie industry.
-	Higher vote counts often correlate with popularity.
-	Movie ratings can be categorized to better understand audience preferences.
-	Data cleaning significantly improves analysis accuracy.
