# spotify-music-analysis
Spotify's audio features with streaming performance metrics to uncover patterns in successful music.

## The Spotify Analyzer is a Python-based tool designed to:

Fetch and analyze the top tracks of popular artists using the Spotify Web API. The analysis includes data on artist name, track name, track popularity, album, release year, and duration.

Provide visualizations and insights into top artist, tracks, streaming trends, and audio features such as danceability, energy, and valence.

![image](https://github.com/user-attachments/assets/768e6375-3ba6-4736-bb63-9e840eeddba3)

## Requirements:

Python

Spotify Developer Account (https://developer.spotify.com/)

- Log in to Spotify Developer Dashboard
  
![image](https://github.com/user-attachments/assets/25f7a94e-d3ac-4ad1-a79e-e5c5f04617d1)

- Create new application to get Client ID and Client Secret

![image](https://github.com/user-attachments/assets/a2e3e5ff-d9d5-4493-a218-cf756dc360aa)

## Libraries:

- spotipy

- pandas

- numpy

- matplotlib

- seaborn

- datetime

- time

- plotly

![image](https://github.com/user-attachments/assets/2772cef8-9412-4181-beb6-d564fbae34b8)

![image](https://github.com/user-attachments/assets/2032d8b2-9f7f-4f59-9b5c-81625143e4b5)

## Spotify Top Tracks & Artist Analysis:

1. Initialize Spotify client by providing Client ID and Client Secret
2. Define genres and top artists to analyze
3. 3. Run Analysis and Visualization. The code outputs:

-Combined data in a CSV file (spotify_top_tracks_analysis.csv).

-Summary statistics and top tracks for each artist.

-Variety of visuals including box plot and bar chart for popularity and average track duration.

![image](https://github.com/user-attachments/assets/6142c2dd-5f52-4206-806f-a2136a1a3d49)

## Monthly Stream Trends for Top Artists Across Genres:

1. Convert release date to datetime
2. Filter data to last two years
3. Create monthly averages for streams
4. Get top 10 artists per genre based on total streams
5. Plot data

![image](https://github.com/user-attachments/assets/fd4e2d97-da9a-4e76-945c-1cbb7c4dac81)

![image](https://github.com/user-attachments/assets/41e51d3b-bba3-4b80-bf67-0656995b2e33)


## Top Artist’s Average Daily Streams

1. Filter data to last two years
2. Create monthly averages for streams 
3. Get the top 10 artists per genre based on total streams
4. Create a figure with subplots
5. Add traces for all genre
6. Add stats table
7. Create buttons for dropdown (switch genres)
8. Display figure (interactive)

![image](https://github.com/user-attachments/assets/ae1dd44a-e8cd-45a4-9cdf-31ee9fea2ad2)

Dashboards:

![image](https://github.com/user-attachments/assets/5fad2585-cf5c-4f21-8686-0b334901479a)

![image](https://github.com/user-attachments/assets/f78a5029-ad52-4734-aa2b-cab54f0fb26e)

