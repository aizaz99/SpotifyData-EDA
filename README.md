 Spotify Data Analysis with Python (Pandas)
 Project Overview

This project explores the Spotify Tracks Dataset (232k+ songs) using Python and Pandas. The goal is to clean, analyze, and visualize data to uncover insights about genres, artists, song characteristics, and popularity trends.

I focused on answering four guiding questions:

Which genres are most popular on average?

Which artists dominate in terms of popularity?

Are songs getting shorter or longer?

Do “happy” songs (high valence) also tend to be danceable or energetic?

Tech Stack

Python 3

Pandas (data wrangling & aggregation)

Matplotlib & Seaborn (visualizations)

Jupyter Notebook (analysis & storytelling)

Dataset

Source: Kaggle – Spotify Tracks Dataset

232,725 tracks

Features include: genre, artist_name, track_name, popularity, danceability, energy, valence, acousticness, duration_ms, and more.

Key Analysis & Insights
1. Genre Popularity

Pop is the clear leader (avg popularity ~66.6).

Rap, Rock, and Hip-Hop also score high.

Folk and Alternative trail behind.

Insight: Spotify popularity heavily favors mainstream genres.

2. Top Artists by Popularity

Pedro Capó tops the list (avg popularity ~87).

Latin pop/reggaeton stars like Mario Bautista, Mau y Ricky, Paloma Mami, Sofia Reyes also dominate.

Martin Garrix represents EDM at the top.

Insight: Latin pop and global crossover artists thrive on Spotify.

3. Song Duration Trends

Average song length is ~3.9 minutes, median ~3.7.

Most tracks cluster between 3–4.5 minutes.

Outliers include very long tracks (~90 minutes, likely live/classical).

Insight: Streaming-era tracks mostly stay under 4 minutes, aligning with industry norms.

4. Happiness, Danceability & Energy

Positive correlation between valence (happiness) & danceability (0.55).

Positive correlation between valence & energy (0.44).

Negative correlation between valence & acousticness (-0.32).

Insight: Happy songs tend to be more upbeat, danceable, and energetic. Acoustic tracks are generally less happy and energetic.

Visualizations

Bar chart of Top 10 Genres by Popularity

Correlation Heatmap of audio features

Scatter plot of Valence vs Energy


Future Improvements

Add trend analysis by year (are songs getting shorter over time?).

Build a Spotify recommendation engine (linking audio features with popularity).

Combine with Netflix dataset for cross-platform entertainment insights.

 Key Takeaway

This analysis shows how Pandas + basic visualizations can uncover meaningful insights from music data. The results highlight real-world patterns in streaming: mainstream genres dominate, Latin artists are rising globally, and upbeat tracks drive popularity.
