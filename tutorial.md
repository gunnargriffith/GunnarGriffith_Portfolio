---
title: "Tutorial Blog"
---

## Data Analysis Tutorial - Spotify Top 200

![](images/spotify-logo-icon.webp)

    Spotify provides a public API that includes playlist data and detailed audio features
for individual tracks, such as Danceability, Energy, Speechiness, and Valence.

For this project, I analyze a dataset containing Spotify’s official Top 200 songs
from 2016 to 2023. The goal is to explore which musical characteristics are most
associated with higher-ranking songs and whether collaborations outperform solo artists.

### Research Questions

1. Which audio features significantly predict higher chart ranking?
2. Do songs performed by multiple artists achieve higher rankings than solo-artist songs?

### Dataset Overview

The dataset includes the following variables:

- Rank
- Title
- Artists
- Danceability
- Energy
- Speechiness
- Acousticness
- Instrumentalness
- Valence
- Points (Total)

Each row represents a song’s daily appearance in the Spotify Top 200.

### Data Cleaning and Feature Engineering

To prepare the dataset for analysis, I:

- Created a `multi_artist` variable indicating whether a song has multiple performers.
- Converted ranking into a `rank_score` where higher values indicate better performance.
- Collapsed the dataset so each song appears only once.
- Computed average rank and total days in the Top 200 for each song.