# spotify-music-analysis
Spotify's audio features with streaming performance metrics to uncover patterns in successful music.

## The Spotify Analyzer is a Python-based tool designed to:

Fetch and analyze the top tracks of popular artists using the Spotify Web API. The analysis includes data on artist name, track name, track popularity, album, release year, and duration.

Provide visualizations and insights into track performance, streaming trends, and audio features such as danceability, energy, and valence.

## Requirements:

Python

Spotify Developer Account (https://developer.spotify.com/)

## Libraries:

- spotipy

- pandas

- numpy

- matplotlib

- seaborn

## Spotify Analyzer (Real Data)

1. Initialize the SpotifyAnalyzer Class: Provide your Client ID and Client Secret

2. Provide a list of artists. You can use the get_artist_top_tracks to analyze their top tracks.

3. Run Analysis and Visualizations

The code outputs:

- Combined data in a CSV file (top_10_artists_tracks.csv).

- Summary statistics and top tracks for each artist.

- Box plot and bar chart for popularity and average track duration.
