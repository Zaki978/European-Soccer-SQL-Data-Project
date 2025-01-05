# European Soccer Data Analysis Project

![European Leagues Photo](https://github.com/Zaki978/European-Soccer-SQL-Data-Project/assets/top-football-leagues-europe.png)
![European Leagues Photo v2](https://www.google.com/url?sa=i&url=https%3A%2F%2Fscore24.com%2Fhome%2Fthe-new-season-of-europes-top-football-leagues-what-to-expect%2F&psig=AOvVaw1JkPkdSusozB2kHHL7lTI0&ust=1735282761952000&source=images&cd=vfe&opi=89978449&ved=0CBQQjRxqFwoTCIig65juxIoDFQAAAAAdAAAAABAT)

## Overview
This project analyzes football (soccer) data from major European leagues using mainly SQL and Tableau for data visualization. The analysis focuses on team performance metrics, player statistics, and league competitiveness across multiple seasons from 2014 until 2020.

### Technologies Used
- **SQL (SQLite)**: Complex queries, data analysis and Database management
- **Python**: Built a file-based database to load CSV files into tables and export query results to CSV files
- **Jupyter Notebook**: Development environment
- **Tableau**: Creating charts and dashboards

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
   - Launch Jupyter Notebook with: *Jupyter Notebook*

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
1. **Premier League** shows the highest average points gap (68.86) between top and bottom teams
2. **Manchester City** dominated the 2017 Premier League season with 100 points
3. Clear patterns in home vs. away performance across all leagues show a significant home field advantage, with **home teams winning 1.47 times on average more often than away teams**
4. **La Liga, Premier League, and Serie A** each recorded the highest total matches played, with 2,660 games whereas Bundesliga has a total of 2,142 games
5. **Strong relationship between shots on target and shot conversion rate** but weak relationship between red cards and total losses suffered by a team
6. **Cagliari was the team with the highest loss rate of 48.68%**, losing 56 matches out of 114 games across all seasons
7. **Barcelona had the largest goal difference** of 470 whereas Granada has the smallest goal difference of -121 across all seasons 
8. **Barcelona had the most shots on target** across all seasons, reaching 44.01% overall
9. **Serie A had the highest average goals scored per team** across seasons at an average of 53.4 goals
10. The highest average goals per game recorded across a season was in the **2019 Bundesliga season with 1.6 goals per game**

## Data Visualization in Tableau available on my [Tableau Public Profile](https://public.tableau.com/app/profile/zaki.bouaoudia4587/vizzes).


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
