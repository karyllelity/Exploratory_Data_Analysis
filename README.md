# Spotify Songs 2023 - Exploratory Data Analysis (EDA)  

An analysis of the most streamed songs on Spotify in 2023, uncovering trends in track popularity, artist frequency, and musical characteristics.

## Description

This project performs an exploratory data analysis (EDA) on the [Most Streamed Spotify Songs 2023 dataset](https://www.kaggle.com/datasets/nelgiriyewithana/top-spotify-songs-2023). By examining streaming numbers, release dates, and various musical attributes, this analysis seeks to provide insights into what factors contribute to track popularity on Spotify. Through data visualization and statistical analysis, we aim to answer key questions regarding track performance, artist trends, and platform preferences.

### Goal

To clean the dataset, handle missing values, convert data types, and perform exploratory data analysis (EDA) to uncover trends and insights regarding track popularity, artist performance, and platform usage on Spotify in 2023.

### Data Analysis Results

By running the analysis, you will uncover:

- **Most Streamed Tracks**: Identification of the top tracks of 2023 based on streaming numbers.
- **Artist Frequency**: Analysis of the most frequently appearing artists in the dataset.
- **Correlations Between Features**: Insights on how various musical attributes (e.g., energy, danceability, valence) correlate with track popularity, such as which attributes contribute most to the number of streams.
- **Temporal Trends**: Insights into when tracks were released, identifying trends in release years and months.
- **Mode Analysis**: Distribution of tracks between Major and Minor modes and their relation to popularity.
- **Platform Popularity**: Comparison of the most streamed tracks across different platforms (e.g., Spotify Playlists vs. other sources).

## Getting Started

### Dependencies

* **Python**: Required for executing the data analysis code.
* **Libraries**:
  * **pandas** - For data manipulation, cleaning, and efficient handling of large datasets.
  * **matplotlib** - For creating static plots and visualizations.
  * **seaborn** - For enhanced visualization, providing statistical plot styles and functions.
  * **warnings** - Used to filter and ignore non-critical warning messages for a cleaner output. 
* **Jupyter Notebook** (recommended) - Required to run code, explore the dataset, and visualize outputs within the notebook interface.

### Installing

1. **Download the Required Files**  
   Download the following files to your local machine:
   * `spotify-2023.csv` - The raw dataset that will be loaded and cleaned.
   * `Spotify DataSet 2023.ipynb` - The Jupyter Notebook containing the analysis code.
   * `spotify-cleaned.csv` - The final cleaned dataset output after processing.
  
### Executing Program

* Open Jupyter Notebook and load the `Spotify DataSet 2023.ipynb` notebook.
* Run the program by using Shift + Enter to execute the cells in the notebook.

### Key Findings

- **Data Overview**:  
  The dataset has 953 rows and 24 columns. Missing values were handled, and columns like `streams` and `in_deezer_playlists` were converted to numeric. Artists were flattened into individual names.

- **Descriptive Statistics**:  
  A correlation matrix was analyzed. Pie charts visualized the mean, median, and standard deviation of streams.

- **Top Performers**:  
  "Blinding Lights" is the most streamed track. Taylor Swift contributed 31.5% of the top 5 artists.

- **Temporal Trends**:  
  A peak in track releases occurred in 2020, with 350 tracks. The month with the most releases had 121 tracks.

- **Genre & Music**:  
  Danceability_% and Energy_% showed positive correlations with mood. Weak correlations were found between Danceability_% vs Energy_% and Valence_% vs Acousticness_%.

- **Platform Popularity**:  
  Spotify Playlists had the highest track count compared to other platforms.

- **Advanced Analysis**:  
  The top 10 most frequent artists were visualized. 44.6% of tracks are in Major mode, and 55.4% are in Minor mode.

## Recommendation

### Datetime Handling
Combine the date-related columns (e.g., `released_day`, `released_month`, `released_year`) into a single column in the format `YYYY-MM-DD` and convert it to the proper datetime format. This ensures easier manipulation and consistency across your data, enhancing accuracy when working with incomplete or inconsistent data.

## Authors

Contributor names and contact info:

* Karylle Marjorie Gealan
* [@karyllelity](https://github.com/karyllelity)

###  Version History

* 0.1
    * Initial Release of README file.
* 0.2
    * Uploaded the draft `Spotify DataSet 2023.ipynb`.
* 0.3
    * Added `spotify-cleaned.csv`.
* 0.4
    * Uploaded the final version of `Spotify DataSet 2023.ipynb` with completed analysis.
* 0.5
    * Uploaded the final version of README file.
