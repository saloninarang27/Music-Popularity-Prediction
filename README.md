# Music-Popularity-Prediction
Music Popularity Prediction aims to leverage machine learning techniques to estimate the future popularity of songs based on their musical attributes and metadata. The project employs various regression algorithms, with Random Forest Regression providing the best predictive accuracy.

The dataset contains 227 music tracks, each characterized by features such as danceability, energy, loudness, tempo, valence, and speechiness, along with essential metadata like track name, artist, album, release date, and explicitness. By analyzing these attributes, the model predicts the popularity score of a track, helping artists, producers, and marketers make data-driven decisions on song releases and promotions.

This project includes data preprocessing, feature engineering, model training, and performance evaluation to ensure accurate predictions. Advanced visualization techniques are also used to provide insights into the factors influencing music popularity.

---
## Overview
Music Popularity Prediction means using regression techniques to forecast the popularity of songs based on various music features and metadata. Expected results include accurate predictions of a song’s future performance in terms of streams, downloads, and chart positions, which enable music producers, artists, and marketers to make informed decisions.

To get started with music popularity prediction, we need a dataset of various songs with their musical features and historical data on how much popularity the songs got. I found an ideal dataset for this task which includes 227 music tracks, each described by their music features along with additional metadata like track name, artists, album name, and release date.

## Methodology
I have used various regression algorithms to predict music popularity, among which **Random Forest Regression** provided the best results. The dataset consists of 227 music tracks, each with detailed attributes such as:
- **Track Name**
- **Artists**
- **Album Name**
- **Album ID**
- **Track ID**
- **Popularity (target variable)**
- **Release Date**
- **Duration (ms)**
- **Explicit (Boolean)**
- **External URLs**
- **Danceability**
- **Energy**
- **Key**
- **Loudness**
- **Mode**
- **Speechiness**
- **Acousticness**
- **Instrumentalness**
- **Liveness**
- **Valence**
- **Tempo**

## Features
- **Data Preprocessing**: Cleaning and preparing music datasets
- **Feature Engineering**: Extracting key audio features
- **Machine Learning Models**: Implementing regression and classification algorithms
- **Evaluation Metrics**: Measuring accuracy and model performance
- **Interactive Visualization**: Graphs and insights on music trends

## Tech Stack
- **Programming Language:** Python
- **Libraries:** Pandas, NumPy, Scikit-Learn, TensorFlow, Matplotlib, Seaborn
- **Data Source:** Spotify API, Kaggle Datasets

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/saloninarang27/MusicPopularityPrediction.git
   ```
2. Navigate to the project directory:
   ```sh
   cd MusicPopularityPrediction
   ```
3. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```
4. Run the project:
   ```sh
   python main.py
   ```

## Contributing
Contributions are welcome! Feel free to fork the repo and submit a pull request.

## License
This project is licensed under the MIT License.

---
🎵 "Predicting the next chart-topping hit, one beat at a time!" 🚀

