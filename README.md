# European Football Data Analysis Project

## Overview
This project analyzes football (soccer) data from major European leagues using mainly SQL. The analysis focuses on team performance metrics, player statistics, and league competitiveness across multiple seasons from 2014 until 2020.

## Technologies Used
- **SQL (SQLite)**: Complex queries, data analysis and Database management
- **Python (including Pandas)**: Data manipulation and analysis
- **Jupyter Notebook**: Development environment

## Setup and Usage
1. **Get the Data**
   - Visit Kaggle dataset: [Football Database](https://www.kaggle.com/datasets/technika148/football-database/data?select=leagues.csv)
   - Download all CSV files from the dataset:
     - appearances.csv
     - games.csv
     - leagues.csv
     - players.csv
     - shots.csv
     - teams.csv
     - teamstats.csv
   - Place all CSV files in a directory named `Football Database`
2. **Install Jupyter Notebook**
   - Make sure to have Python (3.8 or higher) installed first
   - Open terminal/command prompt and run: *pip install notebook*
   - Launch Jupyter Notebook with: *jupyter notebook*

2. **Load Data into SQLite**
   - Run the Jupyter notebook called 'EU Football SQL Project.ipynb'
   - The notebook will automatically create and populate the SQLite database
   - Verify successful data import through the table row count check

3. **Run Analysis**
   - Execute the Jupyter notebook cells in sequence

## Data Sources
The dataset includes comprehensive statistics from:
- English Premier League
- Spanish La Liga
- German Bundesliga
- Italian Serie A
- French Ligue 1

## Database Structure
The project utilizes a SQLite database containing seven interconnected tables:
- **Appearances**: Player-specific match statistics
- **Games**: Match details and results
- **Leagues**: Information about the five major European leagues
- **Players**: Player biographical data
- **Shots**: Shot-specific statistics
- **Teams**: Team information
- **TeamStats**: Team performance metrics per match

## Key Findings
1. Premier League shows the highest average points gap (68.86) between top and bottom teams
2. Manchester City dominated the 2017 season with 100 points
3. Significant variation in league competitiveness across the five major European leagues
4. Clear patterns in home vs. away performance across all leagues show a significant home field advantage, with home teams winning 1.47 times on average more often than away teams

## Key Analyses

### 1. Team Performance Analysis
- Calculation of points, wins, draws, and losses across seasons
- Goal scoring and conceding patterns
- Home vs. away performance metrics
- Season-by-season team rankings
- Identification of league champions and defending champions

### 2. Player Statistics
- Top goal scorers and their conversion rates
- Player performance metrics (goals, assists, shots)
- Statistical distribution of player performance (quintile analysis)
- Detailed player statistics by team and season

### 3. League Competitiveness Analysis
- Points gap between top and bottom teams
- League-wide statistical comparisons
- Analysis of championship diversity
- Average points and performance metrics by league

### 4. Specific Team Analysis
Examples using Arsenal FC:
- Home and away goal-scoring patterns
- Season-by-season performance metrics
- Player contribution analysis

## Author
Zaki Bouaoudia
