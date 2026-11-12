# Predicting a Hit: Using Spotify Audio Features to Spot Viral Songs

Exploring whether a song's audio features (danceability, energy, valence, acousticness, liveness, tempo, etc.) can predict whether it goes viral and how long it sticks around on the charts.

## What's in here

- `SpotifyAnalysis.ipynb` — EDA and modeling on the dataset: feature distributions, correlation with chart longevity, and a classifier for `is_viral_hit`.
- `data/` — the dataset (track metadata, audio features, chart longevity panel), with `datasheet.md` / `README.md` describing each file's columns.

## Data source

[Global Spotify Hits & Audio Dynamics (2018–2026)](https://www.kaggle.com/datasets/vedauv/global-spotify-hits-and-audio-dynamics-20182026) from Kaggle.

## Setup

```bash
pip install -r requirements.txt
jupyter lab SpotifyAnalysis.ipynb
```
