**Netflix 1990s Movie Analysis**

This project focuses on analyzing Netflix movies from the 1990s, particularly focusing on Action movies, to demonstrate fundamental data manipulation and visualization techniques using Python's **Pandas** and **Matplotlib** libraries.

**Project Overview**

The dataset used in this project contains various Netflix titles, and the analysis focuses on:

1. Filtering the data to work with movies only.
2. Creating subsets of movies released in the 1990s (1990-1999).
3. Visualizing the distribution of movie durations in the 1990s.
4. Filtering for Action movies from the 1990s and analyzing their duration distribution.
5. Counting the number of Action movies under 90 minutes using both:
 - **Vectorized Pandas** operations.
 - A traditional **for** loop.


**Key Steps**

**1. Loading and Inspecting the Data**

The Netflix dataset is loaded using Pandas and inspected to understand the structure of the data. The dataset contains information about movie titles, genres, release years, and durations.

**2. Data Filtering and Subsetting**

The dataset is filtered to include:

Movies only by selecting rows where the type column equals 'Movie'.
Movies from the 1990s by filtering on the release_year column.


**3. Visualizing Movie Duration Distribution**

Histograms are created to visualize the distribution of movie durations:

**All 1990s movies**: The duration distribution of all movies released in the 1990s is analyzed.
**1990s Action movies**: The data is further subsetted to analyze the duration distribution of Action movies specifically.

**4. Counting Short Action Movies**

Two methods are used to count the number of Action movies under 90 minutes:

**Vectorized Pandas operations** for efficient computation.

**Traditional for loop** using Pandas' .iterrows() method for practice with loops.

**Visualizations**

Two histograms are created:

- **Distribution of 1990s Movie Durations**: A histogram showing the duration distribution of all movies from the 1990s.
- **Distribution of Action Movie Durations in the 1990s**: A histogram showing the duration distribution of Action movies specifically.


**Project Impact**

The analysis of Netflix movies from the 1990s, particularly Action movies, provides insights into the length of content that was prevalent during that decade. 

This information could help streaming platforms like Netflix better understand content trends from that era. 
Specifically, knowing the distribution of movie durations and identifying a significant number of Action movies under 90 minutes can help inform content recommendations, viewer preferences, or even guide decisions related to new content production for viewers who may enjoy shorter Action movies.

The techniques used here—data filtering, subsetting, and vectorized operations—can also be directly applied to business intelligence tasks such as customer segmentation and trend analysis in other sectors like retail or e-commerce.


**Future Improvements**

**1. Analyze Other Genres:**

- Expand the analysis beyond Action movies to include other genres like Comedy, Drama, or Horror. This would provide a broader understanding of content trends in the 1990s.

**2. Explore Release Year Trends:**

- Perform a time-series analysis to see how the release of movies changed over the years in terms of volume or duration. This could offer insights into how the entertainment industry evolved during that decade.

**3. Apply NLP to Movie Descriptions**:

- Since movie descriptions are available, Natural Language Processing (NLP) techniques can be used to analyze the language used in these descriptions. 
For example, sentiment analysis could be applied to understand whether the descriptions of Action movies in the 1990s had more positive, negative, or neutral tones. 
Additionally, key themes or keywords could be extracted to get a better sense of the types of narratives that were common in that genre during the decade


**4. Compare with Current Trends:**
- Compare the 1990s data with current trends to identify shifts in viewer preferences, content length, or genre popularity over time. 
This could be particularly valuable for  Netflix to tailor their catalogs to evolving viewer habits.




**Dependencies**

This project requires the following Python libraries:
- **pandas**
- **matplotlib**
- **mpld3 (if you want to render interactive plots)**


**Dataset**

The dataset (netflix_data.csv) contains the following relevant columns:

- **type**: The type of Netflix title (e.g., Movie or TV Show).
- **release_year**: The year the movie was released.
- **duration**: The length of the movie in minutes.
- **genre**: The genre of the movie.


**How to Run**
1. Ensure the necessary Python packages are installed.
2. Place the dataset (netflix_data.csv) in the same directory as the notebook or script.
3. Run the Jupyter notebook (netflix_movies.ipynb) to view the analysis and visualizations.
