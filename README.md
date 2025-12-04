# MUSIC RECOMMENDATION SYSTEM (Spotify)

## Internship Task – Rhombix Technologies

### Objective
To predict the likelihood of a user repeatedly listening to a Spotify song
within a 30-day timeframe using machine learning.

### Dataset
Kaggle Spotify listening history dataset containing:
- spotify_track_uri
- ts (timestamp)
- platform
- ms_played
- track_name
- artist_name
- album_name
- reason_start
- reason_end
- shuffle
- skipped

### Methodology
- Data preprocessing and timestamp conversion
- Feature engineering (play count, recency, skip rate, shuffle rate)
- Binary target creation (repeat within 30 days)
- Machine learning model to predict replay probability
- Recommendation generation based on predicted probabilities

### Tools & Technologies
- Python
- Pandas, NumPy
- Scikit-learn
- XGBoost
- Jupyter Notebook

### Output
Top recommended tracks based on repeat listening probability.

### Author
Muhammad Nabeel
