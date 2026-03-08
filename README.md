![Python](https://img.shields.io/badge/Python-3.10-blue)
![Pandas](https://img.shields.io/badge/Pandas-Data%20Analysis-yellow)
![NumPy](https://img.shields.io/badge/NumPy-Numerical%20Computing-013243)
![Seaborn](https://img.shields.io/badge/Seaborn-Visualization-00A67E)
![Matplotlib](https://img.shields.io/badge/Matplotlib-Plotting-orange)
![Jupyter](https://img.shields.io/badge/Jupyter-Notebook-F37626)

# 🎧 Spotify Popularity Analysis

Data Analytics Case Study - Understanding What Drives Song Popularity

A recruiter-ready analysis exploring how audio characteristics and genre patterns influence Spotify song popularity using Python, Pandas, and Seaborn.

## 📊 Project Overview

Music platforms generate massive amounts of audio data.
This project analyzes 232,000+ Spotify tracks to identify which audio features are most associated with higher popularity.

The goal is to move from raw data -> insights -> recommendations using a clear analytical workflow.

## ❓ Business Question

Which audio features and genre patterns are most associated with higher song popularity on Spotify?

## ✅ Key Insight

Popularity is not driven by a single metric.

The strongest signal is a combined audio profile:

Higher danceability + strong genre context increases the likelihood of popularity.

Songs that align with this profile are more likely to achieve higher popularity on Spotify.

## 🔍 Key Findings

1. **Danceability shows the clearest relationship with popularity**

Songs with higher danceability tend to appear more frequently among highly popular tracks.

2. **Genre strongly influences popularity**

Some genres consistently achieve higher average popularity scores.

Top genres in this analysis include:

- Pop
- Rap
- Rock
- Hip-Hop
- Dance

3. **Top 10% popular songs share a distinct audio profile**

Top-performing tracks tend to have:

- Higher danceability
- Moderate energy
- Lower instrumentalness
- Balanced valence

## 📈 Featured Visualizations

- Average Popularity by Genre
- Danceability vs Popularity
- Top vs Bottom Popular Songs
- Feature Correlation Matrix

## 🧠 Analytical Workflow

The project follows a structured data analytics pipeline:

1. **Data Quality Checks**

- Missing value detection
- Duplicate verification
- Dataset structure validation

2. **Feature Engineering**

- Duration converted to minutes
- Popularity categories
- Energy and danceability bands
- Tempo categories
- Mood score

3. **Exploratory Data Analysis (EDA)**

- Distribution analysis
- Genre comparisons
- Correlation analysis

4. **Comparative Analysis**

- Top 10% vs Bottom 10% songs
- Audio profile benchmarking

5. **Evidence-Based Conclusions**

## 🛠️ Tools and Technologies

| Tool | Purpose |
| --- | --- |
| Python | Data analysis |
| Pandas | Data cleaning and manipulation |
| NumPy | Numerical operations |
| Seaborn | Statistical visualization |
| Matplotlib | Data visualization |
| Jupyter Notebook | Analysis environment |

## 📂 Project Structure

```text
music-streaming-data-analytics
│
├── data
│   └── spotify_songs.csv
│
├── notebooks
│   └── spotify_analysis.ipynb
│
├── images
│   ├── spotify_avg_popularity_by_genre.png
│   ├── spotify_danceability_vs_popularity.png
│   ├── spotify_top_vs_bottom_audio_profile.png
│   └── spotify_correlation_matrix.png
│
├── requirements.txt
└── README.md
```

## ▶️ Run the Project Locally

```bash
git clone https://github.com/ethioCodingRoom/music-streaming-data-analytics.git
cd music-streaming-data-analytics
pip install -r requirements.txt
jupyter notebook notebooks/spotify_analysis.ipynb
```

## 💼 What This Project Demonstrates

- End-to-end data analytics workflow
- Strong exploratory data analysis
- Feature engineering for insight discovery
- Business-focused storytelling
- Clear data visualization
- Reproducible notebook analysis

## ⚠️ Limitations

This analysis identifies patterns, not causation.

Song popularity is also influenced by:

- Marketing
- Playlist placement
- Artist popularity
- Release timing

Future work could include machine learning models to predict popularity.

## 🚀 Future Improvements

- Build a popularity prediction model
- Add a Power BI or Tableau dashboard
- Perform time-based trend analysis
- Analyze artist-level popularity patterns

## 👤 Author

Asres Yelia

Data Analyst | Python Developer | BI Enthusiast

GitHub
https://github.com/ethioCodingRoom

Portfolio
https://github.com/ethioCodingRoom/ethiocodingroom.github.io
