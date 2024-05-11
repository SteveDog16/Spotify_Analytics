# Spotify Musical Attributes Analytics
## Overview
This project explores the relationships between various musical attributes and their impact on user preferences using Spotify data. The entire analysis is covered in a Jupyter Notebook environment. Statistical techniques such as regression analysis, t-tests, hypothesis testing, and correlation analysis were utilized to uncover insights into the factors of music attributes. Statistical techniques such as regression analysis, hypothesis testing, and correlation analysis were utilized to uncover patterns and relationships among musical attributes. Various data visualization techniques, ranging from scatter plots to heatmaps, were implemented to effectively communicate these insights.
The questions that I am trying to answer are:
- How does the distribution of mode (major or minor) affect danceability and energy of tracks?
- Is there a correlation between tempo and danceability?
- Do tracks with higher energy tend to have higher danceability?
- How does the presence of spoken words (speechiness) affect the perceived energy and danceability of tracks?
- Is there a relationship between acousticness and instrumentalness?
- Are live performances (higher liveness values) associated with certain musical characteristics such as tempo, energy, or valence?
- Do tracks with higher valence tend to have higher danceability?
- Is there a correlation between loudness and energy?
- Do acoustic tracks tend to have lower loudness compared to non-acoustic ones?
- How does tempo vary across different levels of valence?

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
