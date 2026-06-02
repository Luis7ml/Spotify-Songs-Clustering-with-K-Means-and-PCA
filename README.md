# Spotify Songs Clustering with K-Means and PCA

## Overview

This project applies unsupervised machine learning techniques to group Spotify songs with similar audio characteristics.

The analysis includes data preprocessing, feature scaling, cluster discovery using K-Means, dimensionality reduction with PCA, and interactive visualization of the resulting song clusters.

## Dataset

The dataset contains Spotify songs described by multiple audio features such as:

- Danceability
- Energy
- Loudness
- Speechiness
- Acousticness
- Instrumentalness
- Liveness
- Valence
- Tempo

## Technologies

- Python
- Pandas
- NumPy
- Scikit-Learn
- Plotly
- PCA

## Methodology

1. Load and clean the dataset
2. Standardize features using StandardScaler
3. Determine the optimal number of clusters using the Elbow Method
4. Train a K-Means clustering model
5. Reduce dimensionality with PCA
6. Visualize clusters in a two-dimensional space

## Results

The songs were successfully grouped into distinct clusters based on their audio features, revealing patterns and similarities between tracks.

## Visualizations

### Elbow Method

<img width="1475" height="448" alt="Captura de tela 2026-06-02 195326" src="https://github.com/user-attachments/assets/2f947c82-ba65-4544-af1a-0998258aa500" />


### PCA Cluster Visualization

<img width="1476" height="443" alt="Captura de tela 2026-06-02 195434" src="https://github.com/user-attachments/assets/d410bc63-29d5-4193-9335-1e85c5254e1e" />



## Project Structure

```text
├── README.md
├── spotify_recommendation_kmeans.ipynb
└── spotify_songs.csv
```

## Clusters Descriptions

| Cluster | Description |
|----------|------------|
| 0 | Acoustic & Melancholic |
| 1 | Energetic Pop |
| 2 | Dance & Party Tracks |
| 3 | Intense Instrumental |


## Author

Luis Santos
