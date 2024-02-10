# Netflix Movie Duration Analysis

This project explores the changing landscape of movie durations on Netflix from 2011 to 2020. Leveraging Python's pandas and matplotlib libraries, we delve into a dataset containing details of Netflix's offerings to understand trends in movie lengths over the last decade. Our friend, keen on analyzing Netflix's vast catalog, provided initial insights suggesting a decline in the average duration of movies. This analysis aims to explore that assertion further.

## Steps Undertaken in the Analysis:

1. **Data Preparation:**
   - Loading the provided movie durations and years into a pandas DataFrame from a Python dictionary to facilitate easy manipulation and analysis.

2. **Preliminary Visualization:**
   - Creating a line plot to visualize the trend in movie durations over the specified period, indicating a potential decline in average movie length.

3. **Expanding the Dataset:**
   - Importing a more comprehensive dataset from a CSV file (`datasets/netflix_data.csv`) to broaden the analysis scope. This dataset includes various content types and a wider array of attributes like genre, country, and release year.

4. **Data Filtering:**
   - Filtering the dataset to focus solely on movies, excluding TV shows to maintain relevance to the study's focus on movie durations.

5. **Detailed Visualization:**
   - Employing a scatter plot to examine movie durations against their release years, allowing for a nuanced view of the distribution of movie lengths over time.

6. **Exploring Shorter Films:**
   - Further filtering the data to investigate movies under 60 minutes, revealing a concentration in genres like "Children", "Documentaries", and "Stand-Up", which traditionally feature shorter run times.

7. **Enhanced Visualization:**
   - Utilizing color coding in the scatter plot to differentiate between standard feature films and those belonging to the shorter genres identified, providing visual insights into genre-specific duration trends.

8. **Conclusions and Further Analysis:**
   - Observing that non-feature films, particularly in genres such as children's movies and documentaries, contribute significantly to the overall decrease in average movie durations on Netflix.

## Key Insights:

- The initial analysis of the provided data showed a gradual decline in the average duration of movies on Netflix from 2011 to 2020.
- A comprehensive exploration of the full dataset confirmed the presence of shorter films, particularly in genres like "Children", "Documentaries", and "Stand-Up".
- Visual analysis highlighted the impact of these genres on the average movie duration, suggesting that the decline might not be as pronounced when excluding these categories.

## Conclusion:

While there is evidence to suggest that the average movie duration on Netflix has decreased over the last decade, this trend is significantly influenced by the inclusion of non-feature films. Further analysis, potentially incorporating genre-specific trends and viewer preferences, could provide more nuanced insights into the evolution of movie durations on Netflix.

## Future Directions:

- Statistical analysis to quantify the impact of non-feature films on the average duration.
- Exploration of other factors, such as viewer preferences and production trends, that might influence movie durations.
- A deeper dive into genre-specific duration trends to understand the dynamics within each category.
