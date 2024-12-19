# spotify-music-analysis
Spotify's audio features with streaming performance metrics to uncover patterns in successful music.

## The Spotify Analyzer is a Python-based tool designed to:

Fetch and analyze the top tracks of popular artists using the Spotify Web API. The analysis includes data on artist name, track name, track popularity, album, release year, and duration.

Provide visualizations and insights into top artist, tracks, streaming trends, and audio features such as danceability, energy, and valence.

## Requirements:

Python

Spotify Developer Account (https://developer.spotify.com/)

- Log in to Spotify Developer Dashboard
  
- Create new application to get Client ID and Client Secret

## Libraries:

- spotipy

- pandas

- numpy

- matplotlib

- seaborn

- datetime

- time

## Spotify Analyzer:

1. Initialize Spotify client by providing Client ID and Client Secret

2. Define genres and top artists to analyze
  
3. Run Analysis and Visualization. The code outputs:

-Combined data in a CSV file (spotify_top_tracks_analysis.csv).

-Summary statistics and top tracks for each artist.

-Variety of visuals including box plot and bar chart for popularity and average track duration.
