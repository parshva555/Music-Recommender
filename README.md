# Music Recommendation System

This repository contains a music recommendation system that uses clustering algorithms to recommend tracks based on user-selected songs. The system analyzes song features and provides personalized music recommendations.

## Features

1. **Music Recommendation System Development**: Implemented a recommendation system using K-Means clustering and StandardScaler for personalized music suggestions.
2. **Data Preprocessing and Feature Engineering**: Used pandas for data cleaning, transformation, and feature extraction to prepare the Spotify dataset.
3. **Cluster Analysis and Recommendation Strategy**: Applied the elbow method and developed a frequency-based strategy for diverse song recommendations.

## Tech Stack

- **Programming Language**: Python
- **Libraries and Frameworks**:
  - Data Manipulation and Analysis: `pandas`, `numpy`
  - Machine Learning and Clustering: `scikit-learn` (StandardScaler, KMeans, silhouette_score)
  - Distance Calculation: `scipy` (cdist)
  - Data Visualization: `matplotlib`
- **Data Source**: CSV files for tracks and artists datasets

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/music-recommendation-system.git
   cd music-recommendation-system
2. Insall Required Packages
   ```bash
   pip install -r requirements.txt
3. Usage
   ```bash
   python recommend.py

## Project Structure
- recommend.py: Main script to run the music recommendation system.
- data/: Directory containing the tracks.csv and artists.csv files.
- requirements.txt: List of required Python packages.
   
