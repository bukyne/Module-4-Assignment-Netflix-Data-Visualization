# Module-4-Assignment-Netflix-Data-Visualization
This project analyzes the provided Netflix Data for visual analytics. It includes data preparation, cleaning, exploration, and visualization to identify popular genres and ratings distribution using Python and R.

Requirements
Python libraries: pandas, matplotlib, seaborn
R libraries: ggplot2, dplyr

Files
- Netflix_shows_movies.csv: The cleaned dataset.
- most_watched_genres.png: Visualization of most watched genres.
- ratings_distribution.png: Visualization of ratings distribution.
- ratings_distribution_R.png Visualization of ratings distribution in R
- README.md: Instructions for accessing and understanding the code.


Setup
1. Clone the Repository
2. Install Packages - Python: pandas, matplotlib, seaborn and R: ggplot2, dplyr

Instructions
1. Data Preparation:
   The dataset was unzipped and renamed to 'Netflix_shows_movies.csv'.

2. Data Cleaning:
   Missing values in the dataset are addressed by filling them with 'Unknown'.

3. Data Exploration:
   Data descriptions and statistical analysis are generated using pandas. Here is a summary of the dataset: 

Total Entries: 6234 
Unique Titles: 6172 
Most Common Country: United States 
Most Common Genre: Children & Family Movies, Comedies 

4. Data Visualization:
   Visualizations representing the most watched genres and the distribution of ratings are created using Seaborn and Matplotlib.

5. R Integration:
   One of the charts or visualizations is implemented in R.
   - Load the clean dataset into R.
   - Prepare the data for visualization
   - Use ggplot2 to create the visualization for the ratings distribution. 

Usage
1. Run the Python code to perform data analysis and generate visualizations.
   Output: most_watched_genres.png and ratings_distribution.png

2. Run the R script to integrate visualization.
   Output: ratings_distribution_R.png

Results
Top Genres: International Movies, Dramas, Comedies.
Ratings: Most content is TV-MA or TV-14.
