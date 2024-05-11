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

# Data
The dataset comes from Kaggle under a dataset called “Spotify Top Songs and Audio Features”. It is publicly available for everyone to use. Here is the link to the dataset. https://www.kaggle.com/datasets/julianoorlandi/spotify-top-songs-and-audio-features. Data used in the Jupyter Notebook file include:
- **Mode**: Indicates whether a track is in a major or minor key, specifying the type of scale from which its melodic content is obtained. For example, a major mode might convey a happier or brighter mood, while a minor mode might transmit a more somber or melancholic mood.
- **Danceability**: Describes how suitable a track is for dancing based on different musical elements such as tempo, rhythm stability, beat strength, and overall regularity. A higher value indicates that the track is more danceable, while a lower value suggests it may be less suitable for dancing.
- **Energy**: Represents an emotional measure of intensity and activity in a track, ranging from 0.0 to 1.0. Energetic tracks typically feel fast, loud, and noisy, while lower energy tracks may feel calmer or more somber.
- **Speechiness**: Detects the presence of spoken words in a track, with values ranging from 0.0 to 1.0. Higher values indicate a higher proportion of spoken words, suggesting that the track is more speech-like rather than purely musical.
- **Acousticness**: Indicates the likelihood that a track is acoustic, ranging from 0.0 to 1.0. A higher value suggests a higher chance the track contains acoustic elements rather than electronic or synthesized sounds.
- **Instrumentalness**: Predicts whether a track contains vocals, with values ranging from 0.0 to 1.0. Higher values indicate a greater likelihood that the track is instrumental, meaning it contains little to no vocal content.
- **Liveness**: Detects the presence of an audience in a recording, with higher values indicating a greater probability that the track was performed live rather than in a studio setting.
- **Valence**: Describes the musical positiveness carried by a track, ranging from 0.0 to 1.0. Tracks with higher valence values tend to sound more positive or uplifting, while lower values may convey a more negative or sad mood.
- **Loudness**: Represents the overall volume of a track in decibels (dB), with values typically ranging between -60 and 0 dB. It is useful for comparing the relative loudness of tracks and is an important factor in determining the perceived intensity of a piece of music.
- **Tempo**: Specifies the overall speed or pace of a track in beats per minute (BPM). It helps distinguish the rhythmic feel of a piece of music and is essential for performers and listeners to synchronize their movements or understand the mood of the music.

# Libraries Used
- Pandas
- Matplotlib
- Seaborn
- Scipy
- Statsmodels

  ## Key Features
- **Data Exploration**: Examined the Spotify dataset to understand the distribution and characteristics of musical attributes.
- **Regression Analysis**: Investigated the impact of major and minor modes and spoken words on the danceability and energy levels of tracks using Ordinary Least Squares (OLS) regression analysis.
- **Hypothesis Testing**: Performed t-tests to assess the effect of music mode on danceability and energy levels, and to evaluate the influence of loudness intensity on both acoustic and non-acoustic tracks for statistical significance.
- **Correlation Analysis**: Explored correlations between musical attributes using Pearson’s correlation coefficient to identify the strength and direction of relationships between two variables.
- **Visualizations**: Visualized findings using scatter plots, hexbin plots, joint plots, regression plots, box plots, and heatmaps to effectively convey and interpret the results.

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

## Results
- The type of mode (major or minor) a track is in significantly influences how energetic it feels and how suitable it is for dancing. This is because the differences in energy level and danceability between tracks of different modes are not random, but rather distinct characteristics of each mode. Interestingly, the mode of a track explains a small but significant portion of the variability in both energy and danceability levels. In other words, while other factors may also contribute to differences in energy and danceability, the mode has been found to have a recognizable impact on these attributes. This insight highlights the importance of considering the mode when analyzing and understanding the energetic and danceable qualities of music tracks.
- The analysis revealed a slight negative relationship between tempo and danceability, due to the negative correlation coefficient value, suggesting that faster-paced songs may be slightly less danceable. This finding was statistically significant, meaning it's unlikely to be random by chance. However, it's important to remember that correlation doesn't mean causation, so we can't determine the exact influence of tempo on danceability based solely on this analysis.
- There is an indication from the prominently substantial correlation coefficient that there is a robust positive linear relationship between the loudness and energy of tracks, suggesting a strong association between these variables. The p-value, which is smaller than the significance level, confirms a significant correlation between loudness and energy levels. It's important to remember that correlation does not imply causation, so caution should be exercised when interpreting the relationship between these variables solely based on this analysis.
- The slightly positive correlation coefficient value discloses a subtle positive association between energy and danceability, suggesting that songs with higher energy levels may be marginally more danceable. The low p-value, confirms a meaningful correlation between energy and danceability. 
- The linkage between valence and danceability shows a moderately positive correlation, suggesting that tracks with a more positive tone tend to be slightly more danceable. The considerably smaller p-value indicates a significant correlation between these variables.
- There is a weak positive relationship between tempo and valence, saying that songs with higher tempo may slightly give a more positive tone. The significantly smaller p-value suggests that there is a connection between tempo and valence.
- The levels of spoken words a track has significantly influences how energetic it feels and how acceptable it is for dancing. The differences in energy level and danceability between tracks of various speechiness are not random, but rather unique characteristics of each mode. Interestingly, the speechiness of a track gives a small but remarkable portion of the variability in both energy and danceability levels. According to the analysis, the average track has the most energy and danceability levels when there is little to no spoken words. This insight points out the importance of considering the spoken word levels when examining and comprehending the energetic and danceable qualities of music tracks.
- The low p-value of the acoustiness and danceability attributes shows that there is a significant impact on its danceability. Songs with various acoustic characteristics present distinct danceability levels that are unlikely to occur by random chance alone. The analysis states that tracks with the lowest acoustic levels (non-acoustic) tend to have the lowest levels of danceability.
- There is an indication that the acoustic nature of a track, whether acoustic or non-acoustic, gives a significant impact on its loudness thanks to its significantly low p-value. Tracks with different acoustic characteristics display distinct loudness levels that are not likely to occur by random chance alone. In the analysis, it indicates that some tracks with the lowest acoustic characteristics (non-acoustic) tend to be the loudest out of all of the tracks.

## Contact Information
Steven Nguyen

Email: sn924@drexel.edu

