
# Song Sentiment Analysis

This project was implemented during the course "Applied Machine Learning," offered by the Department of Management Science & Technology at the Athens University of Economics and Business.

## Purpose

Spotify uses a metric known as *Valence* to measure the happiness of a track. The exact calculation of Valence is not publicly disclosed, leaving room for exploration. This analysis aims to decode Valence and identify the features that best define and explain it. We will conduct a comprehensive analysis of tracks, utilizing data from the Spotify API, focusing on both high-level and low-level musical features.

## Data

`Spotify_API.ipynb`: This notebook demonstrates how to use the IDs of a song to make requests to the Spotify API. These requests provide access to both high-level and low-level features of songs. 

The list of track IDs used in this study was sourced from a dataset available on Kaggle. The dataset can be found [here](https://www.kaggle.com/datasets/ektanegi/spotifydata-19212020).

## Models and Methodology

`Spotify_Valence_Predictor.ipynb`: This notebook presents a thorough analysis aimed at understanding and predicting the valence of a song. It specifically addresses two main questions:

- What features significantly influence the *valence (sentiment)* of a song? This aspect is explored using inferential statistics.

- How can we predict *valence* using various machine learning methods? The machine learning methods employed in this study include:
    - Linear Regression
    - Ridge and Lasso Regression
    - LightGBM
    - Random Forests
    - MLP (Multilayer Perceptron) Neural Networks
