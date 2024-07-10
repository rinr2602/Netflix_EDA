# Netflix Originals Data Analysis

## Introduction
This project provides an in-depth exploratory data analysis (EDA) of Netflix Originals, focusing on movies, documentaries, and specials released up until June 1, 2021. The dataset, sourced from Kaggle, includes information on the title, genre, premiere date, runtime, IMDb score, and language of each Netflix original.

## Dataset
The dataset, `NetflixOriginals.csv`, contains 584 records and the following columns:
1. **Title** - Title of the Netflix Original
2. **Genre** - Genre of the Netflix Original
3. **Premiere** - The date and year of when the Netflix Original was first premiered
4. **Runtime** - The duration of the movie in minutes
5. **IMDB Score** - The average rating of the movie given by viewers
6. **Language** - Language of the movie or documentary or special

## Requirements
To run the analysis, the following libraries are required:
- numpy
- pandas
- matplotlib
- seaborn

Install the required libraries using:
```bash
pip install numpy pandas matplotlib seaborn
```

## Data Preparation
1. Import the necessary libraries.
2. Load the dataset.
3. Display the first few records and get an overview of the dataset.

## Data Exploration
1. **Basic Statistics**
   - **Shape of the dataset:** 584 records and 6 features.
   - **Data Types:** Titles, genres, premiere dates, and languages are of `object` type, runtime is `int`, and IMDb score is `float`.
   - **Descriptive Statistics:** Average runtime is 93.57 minutes, shortest is 4 minutes, and longest is 209 minutes. Average IMDb score is 6.27, with the lowest being 2.5 and the highest 9.0.

2. **Genre Analysis**
   - **Number of Genres:** 115 different genres.
   - **Top Genres:** Documentary, Drama, Comedy, Romantic Comedy, and Thriller.

3. **Language Analysis**
   - **Number of Languages:** 38 different languages.
   - **Top Languages:** English, Hindi, and Spanish.

4. **Missing Values and Duplicates**
   - No missing or null values.
   - No duplicate records.

5. **Premiere Date**
   - Converted to datetime format for further analysis.

## Exploratory Data Analysis (EDA)
1. **Basic Statistics**
   - **Average Runtime:** 93.57 minutes.
   - **Distribution of IMDb Scores:** Most scores are around 6-7, following a Gaussian distribution.

2. **Genre and Runtime Analysis**
   - **Highest Average Runtime Genre:** Heist film/Thriller with 149 minutes.
   - **Top 10 Genres Runtime Distribution:** Visualized using boxplots.

3. **IMDb Score Analysis**
   - **Highest IMDb Score:** 9.0 for "David Attenborough: A Life on Our Planet".
   - **Lowest IMDb Score:** 2.5 for "Enter the Anime".
   - **Correlation between Runtime and IMDb Score:** Weak negative correlation.

4. **Language Distribution**
   - **Movies per Language:** Visualized using bar plots.
   - **IMDb Scores by Language:** Analyzed for patterns.

5. **Premiere Date Analysis**
   - **Movies Released per Year:** Distribution of releases over the years.
   - **Trend in IMDb Scores Over the Years:** Decreasing trend after a peak in 2015.
   - **Genre Popularity Over the Years:** Visualized using stacked bar plots and heatmaps.

6. **Cross-Category Analysis**
   - **Highest Average IMDb Score by Genre:** Animation/Christmas/Comedy/Adventure.
   - **Relationship between Language and IMDb Score:** Analyzed unique languages.
   - **Runtime and IMDb Scores Over the Years:** Scatter and line plots to show trends.

7. **Outliers and Distribution**
   - **Outliers in Runtime and IMDb Scores:** Identified using boxplots.
   - **Runtime Distribution Across Genres:** Focused on the top 10 genres.

## Conclusion
This project provides a comprehensive analysis of Netflix Originals, exploring various aspects such as genre, language, runtime, and IMDb scores. The analysis reveals interesting insights and trends in Netflix's original content.

## How to Use
1. Clone the repository.
2. Install the required libraries.
3. Run the Jupyter Notebook to reproduce the analysis.
