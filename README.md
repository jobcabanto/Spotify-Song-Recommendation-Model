# Spotify Song Recommendation Model

The goal of the project was to quantify my musical taste and understand my listening patterns from a numerical point of view. The recommendation model analyzes songs based on Spotify's "Danceability", "Energy", and "Acousticness" features.

Tools/Technologies Used:
- Python
- Spotify API
- Scikit-Learn
- Pandas
- Matplotlib

Project Summary:
- The dataset was comprised of 100 songs from my current music rotation (good_songs) and 100 songs I do not listen to daily (bad_songs)
- Model features were reduced from Spotify's 13 quantitative audio features to 3 (Danceability, Energy, and Acousticness) using dimensionality reduction techniques
- The specific algorithm used for the project was the K-Nearest Neighbours algorithm with KD-trees
- Using the cross-validation with the elbow method, it was found that 9 was the optimal k-neighbours for the model
- After applying the model to a test set, the model performed with 89% accuracy

Spotify Profile: https://open.spotify.com/user/03oenn4r6hh05yesfms7sp2f2?si=201662862d36428c 

![alt text](https://github.com/jobcabanto/Spotify-Recommendation-Bot/blob/main/res/knn_chart.png)
![alt text](https://github.com/jobcabanto/Spotify-Recommendation-Bot/blob/main/res/elbow_method.png)
