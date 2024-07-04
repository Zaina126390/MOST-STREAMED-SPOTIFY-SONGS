# MOST-STREAMED-SPOTIFY-SONGS
The code is designed to facilitate the analysis and prediction of the popularity of songs on Spotify based on their features
1. Dataset Loading and Preprocessing:

The dataset (Spotify.csv) is loaded using Pandas, assuming it contains various features related to songs.
Initial preprocessing steps involve checking for necessary columns ('streams'), dropping irrelevant columns ('id', 'name', 'artist'), and handling missing values by dropping rows with NaNs.
2. Feature Engineering:

Categorical columns are converted into dummy variables using one-hot encoding (pd.get_dummies()). This transforms categorical data into a format suitable for regression analysis.
3. Model Training:

A linear regression model is chosen (LinearRegression from Scikit-Learn) to predict the number of streams ('streams' column) based on other features (X).
