# Movie Rating Analysis Using PySpark

## Project Overview
This project analyzes the IMDb Top 1000 Movies dataset using Apache PySpark. It explores movie ratings, genres, directors, and audience votes to identify trends and insights from movie data.

## Objectives
- Identify the top 10 highest-rated movies.
- Find the top 10 most-voted movies.
- Analyze average IMDb ratings by genre.
- Compare directors based on their movies and average ratings.
- Categorize movies based on their IMDb ratings.
- Visualize the analysis results using graphs.

## Technologies Used
- Python
- Apache PySpark
- Spark SQL
- Pandas
- Matplotlib
- Jupyter Notebook

## Dataset
The project uses the IMDb Top 1000 Movies dataset containing information such as movie titles, release years, genres, IMDb ratings, directors, and number of votes.

- **Total records:** 1,000 movies

## Key Findings
- Average IMDb rating: approximately 7.95.
- Highest IMDb rating: 9.3.
- *The Shawshank Redemption* received the highest IMDb rating in the dataset.
- *The Shawshank Redemption* also had the highest number of audience votes.
- Genre-wise and director-wise analysis was performed to explore rating patterns.

## Project Structure
```text
Movie_Rating_Analysis_PySpark/
├── Dataset/
├── Notebook/
│   └── Movie_Rating_Analysis_PySpark.ipynb
├── Results/
├── Charts/
│   ├── top_10_rated_movies.png
│   ├── top_10_genres_by_rating.png
│   └── top_10_most_voted_movies.png
└── Report/
```

## How to Run
1. Install Python and Java.
2. Install PySpark, Pandas, Matplotlib, and Jupyter Notebook.
3. Download or clone this repository.
4. Open the notebook in Jupyter Notebook.
5. Update the dataset path if required.
6. Run the notebook cells sequentially.

## Conclusion
This project demonstrates how PySpark can be used for data processing and analysis on a movie dataset. It combines Spark SQL, data aggregation, and visualization to extract meaningful insights from IMDb movie data.
