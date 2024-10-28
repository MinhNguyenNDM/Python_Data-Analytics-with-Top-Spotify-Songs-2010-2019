## Spotify Song Analysis (2010–2019)
### Project Overview:
This project analyzes Spotify song data spanning from 2010 to 2019, focusing on trends in song popularity, genre distribution, and the relationship between various musical features. Using Python libraries such as pandas, seaborn, and matplotlib, I conducted data wrangling, exploratory data analysis, and created visualizations to uncover patterns in the data.

### Process & Methodology:

1. Data Importing & Cleaning:
* Imported multiple CSV files, each representing a different year, using os and pathlib to create a single, concatenated dataset.
* Renamed columns for clarity, and standardized column names, focusing on relevant attributes like popularity, genre, danceability, and energy.

2. Exploratory Data Analysis (EDA):
* Line Chart: Tracked the trend in song popularity over time, highlighting yearly shifts in music preference.
* Bar Chart: Illustrated the top 10 most common genres across the dataset to understand genre distribution.
* Scatter Plot: Examined the relationship between energy and danceability to explore how these factors correlate in popular songs.
* Histogram: Plotted the distribution of song durations, showing the prevalence of different track lengths.
* Box Plot: Compared loudness (dB) levels across years, shedding light on production trends.

3. Insights Gained:
* Top Genres and Artists: Identified the most popular genres and artists with the highest number of hits, with artists like Katy Perry having significant representation.
* Genre Trends: The stacked area chart showed how genre popularity fluctuated over time, offering insights into genre evolution.
* Popularity & Danceability: The regression plot demonstrated a positive relationship between danceability and popularity, suggesting that more danceable tracks tend to be more popular.
* Energy and BPM: Explored the association between energy and BPM, with energy often rising with faster tempos.

4. Conclusions & Next Steps:
This analysis provided insights into popular song attributes over the decade. Future improvements include incorporating regression modeling to predict song popularity and examining lyrical features to assess their impact on popularity.

### Skills Demonstrated:
* Data manipulation and cleaning
* Statistical analysis and data visualization
* Identifying trends and patterns in time-series data
* Summarizing and interpreting music data for deeper industry insights
