# epl-player-analysis-2024-25
This is players analysis for EPL for the season 2024/2025
A complete machine learning project analysing Premier League player 
statistics from the 2024/25 season.

## What this project does
- Cleans and engineers features from raw EPL player stats
- Performs Exploratory Data Analysis (EDA) with visualisations
- Clusters players into roles using K-Means (CAM, CM, Box-to-Box, etc.)
- Predicts a player's position using a Random Forest classifier
- Identifies the most dangerous progressive ball-carrying midfielders

## Results
- Position prediction accuracy: XX% on unseen test data
- Cole Palmer predicted as MID with 85.9% confidence
- Erling Haaland predicted as FWD with 99.6% confidence
- K-Means naturally discovered 5 distinct player roles

## Tools Used
- Python, Pandas, NumPy
- Scikit-learn (KMeans, RandomForest, PCA)
- Matplotlib, Seaborn

## Dataset
EPL Player Stats 2024/25 — 561 players, 55 features

## Project Structure
├── epl_player_stats_24_25.csv   # Raw data
├── epl_analysis.ipynb           # Full notebook
├── images/                      # All chart outputs
└── README.md
