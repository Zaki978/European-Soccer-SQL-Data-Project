# European Soccer Data Analysis Project

<img src="https://github.com/Zaki978/European-Soccer-SQL-Data-Project/blob/main/assets/top-football-leagues-europe.png" alt="European Leagues Photo" width="600" height="300">

## Overview
This project analyzes football (soccer) data from the 5 most famous European leagues across 7 seasons from 2014 until 2020. These European soccer leagues include the Premier League (England), Serie A (Italy), Bundesliga (Germany), La Liga (Spain), and Ligue 1 (France). Within these leagues are professional football clubs that compete in various domestic leagues and international tournaments across Europe and play a crucial role in contributing to the global popularity of the sport. The main technologies used in the project involve SQL for complex queries and Tableau for data visualization.

The analysis focuses on the following key areas:
- **League Comparisons and Trends**: Assessed league competitiveness through point gaps, shot conversion rates, average goals per game, and team scoring averages across seasons.
- **Team Dominance and Performance**: Analyzed season stats, identifying top-scoring teams, champions, goal differences, and rankings by shots on target and loss ratios
- **Player Statistics**: Highlighted top scorers, analyzed player distribution by scoring averages, and generated detailed performance metrics
- **Gameplay Patterns and Relationships**: Investigated home vs. away performance, red cards vs. losses, and shot conversion rates vs. goals scored
- **Arsenal FC Specific Analysis**: Examined Arsenal’s offensive stats, scoring trends, top-scoring players, goal differences, points per game, and season results

The SQL queries used to inspect and clean the data for this analysis can be found here [link](https://github.com/Zaki978/European-Soccer-SQL-Data-Project/blob/main/EU%20Football%20SQL%20Project.ipynb).

Three interactive Tableau dashboards used to report and explore league comparisons and Arsenal's historical performance can be found below:
- [European Soccer Leagues Dashboard 1](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesDashboardPart1/LeaguesDashboardPart1)
- [European Soccer Leagues Dashboard 2](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesDashboardPart2/LeagueDashboardPart2)
- [Arsenal Historical Performance Dashboard](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/ArsenalHistoricPerformanceDashboard/ArsenalDashboard)

A Tableau story is used to walk through team, league and relationship level analysis can be found here [link](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesStoryAnalysis/StoryAnalysis).



### Technologies Used
- **SQL (SQLite)**: Complex queries, data analysis and Database management
- **Python**: Built a file-based database to load CSV files into tables and export query results to CSV files
- **Jupyter Notebook**: Development environment
- **Tableau**: Creating charts, dashboards and stories

## Database Structure
The project utilizes a SQLite database containing seven interconnected tables:
- **Appearances**: Player-specific match statistics
- **Games**: Match details and results
- **Leagues**: Information about the five major European leagues
- **Players**: Player biographical data
- **Shots**: Shot-specific statistics
- **Teams**: Team information
- **TeamStats**: Team performance metrics per match

## Results


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
   - Execute the Jupyter Notebook cells in sequence

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
11. Conversation rates 

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
