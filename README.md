# Spotify Musical Attributes Analytics
## Overview
This project explores the relationships between various musical attributes and their impact on user preferences using Spotify data. The entire analysis is covered in a Jupyter Notebook environment. Statistical techniques such as regression analysis, t-tests, hypothesis testing, and correlation analysis were utilized to uncover insights into the factors of music attributes. Statistical techniques such as regression analysis, hypothesis testing, and correlation analysis were utilized to uncover patterns and relationships among musical attributes. Various data visualization techniques, ranging from scatter plots to heatmaps, were implemented to effectively communicate these insights.
The questions that I am trying to answer are:
- How does the distribution of mode (major or minor) affect danceability and energy of tracks?
- Is there a correlation between tempo and danceability?
- Is there a correlation between loudness and energy?
- Do tracks with higher energy tend to have higher danceability?
- Do tracks with higher valence tend to have higher danceability?
- How does tempo vary across different levels of valence?
- How does the presence of spoken words (speechiness) affect the perceived energy and danceability of tracks?
- Is there a relationship between acousticness and instrumentalness?
- Do acoustic tracks tend to have lower loudness compared to non-acoustic ones?
- Are live performances (higher liveness values) associated with certain musical characteristics?

## Notebook Description
- **Spotify Musical Attributes Analytics**: Title of the Jupyter Notebook file
- **Quick Data Overview**: Quick examination of the dataset
- **Impact of Mode Distribution on Danceability and Energy of Tracks**: section that answers the question “How does the distribution of mode (major or minor) affect danceability and energy of tracks?”
- **Correlation Between Tempo and Danceability**: section that answers the question “Is there a correlation between tempo and danceability?”
- **Correlation Between Loudness and Energy**: section that answers the question “Is there a correlation between loudness and energy?”
- **Correlation of High Energy and High Danceability**: section that answers the question “Do tracks with higher energy tend to have higher danceability?”
- **Correlation of High Valence and High Danceability**: section that answers the question “Do tracks with higher valence tend to have higher danceability?”
- **Variance of Tempo Across Different Levels of Valence**: section that answers the question “How does tempo vary across different levels of valence?”
- **Impact of Speechiness on Energy and Danceability of Tracks**: section that answers the question “How does the presence of spoken words (speechiness) affect the perceived energy and danceability of tracks?”
- **Relationship Between Acoustiness and Instrumentalness**: section that answers the question “Is there a relationship between acousticness and instrumentalness?”
- **Comparing Loudness Levels: Acoustic vs. Non-Acoustic Tracks**: section that answers the question “Do acoustic tracks tend to have lower loudness compared to non-acoustic ones?”
- **Association Between Liveness Values and Musical Characteristics**: section that answers the question “Are live performances (higher liveness values) associated with certain musical characteristics?”

## Key Features
- **Data Exploration**: Examined the Spotify dataset to understand the distribution and characteristics of musical attributes.
- **Regression Analysis**: Investigated the impact of major and minor modes and spoken words on the danceability and energy levels of tracks using Ordinary Least Squares (OLS) regression analysis.
- **Hypothesis Testing**: Performed t-tests to assess the effect of music mode on danceability and energy levels, and to evaluate the influence of loudness intensity on both acoustic and non-acoustic tracks for statistical significance.
- **Correlation Analysis**: Explored correlations between musical attributes using Pearson’s correlation coefficient to identify the strength and direction of relationships between two variables.
- **Visualizations**: Visualized findings using scatter plots, hexbin plots, joint plots, regression plots, box plots, and heatmaps to effectively convey and interpret the results.

## Credits
Kaggle for providing the dataset which was created with Spotify Top Songs Charts and Spotify Web API.

Link to the dataset: https://www.kaggle.com/datasets/julianoorlandi/spotify-top-songs-and-audio-features

Open-source libraries such as Pandas, Matplotlib, Seaborn, Statsmodels, and SciPy for their contributions to data analysis and visualization.
