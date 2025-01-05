# European Soccer Data Analysis Project

<img src="https://github.com/Zaki978/European-Soccer-SQL-Data-Project/blob/main/assets/top-football-leagues-europe.png" alt="European Leagues Photo" width="600" height="300">

## Project Background
This project analyzes football (soccer) data from the **five most famous European leagues** across **seven seasons from 2014 until 2020**. These European soccer leagues include the Premier League (England), Serie A (Italy), Bundesliga (Germany), La Liga (Spain), and Ligue 1 (France). Within these leagues are professional football clubs that compete in various domestic leagues and international tournaments across Europe and play a crucial role in contributing to the global popularity of the sport. The main technologies used in the project involve SQL for complex queries and Tableau for data visualization.

The analysis focuses on the following key areas:
- **League Comparisons and Trends**: Assessed league competitiveness through point gaps, shot conversion rates, average goals per game, and team scoring averages across seasons.
- **Team Dominance and Performance**: Analyzed season stats, identifying top-scoring teams, champions, goal differences, and rankings by shots on target and loss ratios
- **Player Statistics**: Highlighted top scorers, analyzed player distribution by scoring averages, and generated detailed performance metrics
- **Gameplay Patterns and Relationships**: Investigated home vs. away performance, red cards vs. losses, and shot conversion rates vs. goals scored
- **Arsenal FC Specific Analysis**: Examined Arsenal’s offensive stats, scoring trends, top-scoring players, goal differences, points per game, and season results


The SQL queries used to inspect and clean the data for this analysis can be found here [SQL Script](https://github.com/Zaki978/European-Soccer-SQL-Data-Project/blob/main/EU%20Football%20SQL%20Project.ipynb).

Three interactive Tableau dashboards used to report and explore league comparisons and Arsenal's historical performance can be found below:
- [European Soccer Leagues Dashboard 1](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesDashboardPart1/LeaguesDashboardPart1)
- [European Soccer Leagues Dashboard 2](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesDashboardPart2/LeagueDashboardPart2)
- [Arsenal Historical Performance Dashboard](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/ArsenalHistoricPerformanceDashboard/ArsenalDashboard)

A Tableau story is used to walk through team, league and relationship level analysis can be found here [Tableau Story](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesStoryAnalysis/StoryAnalysis).

### Technologies Used
- **SQL (SQLite)**: Complex queries, data analysis and Database management
- **Python**: Built a file-based database to load CSV files into tables and export query results to CSV files
- **Jupyter Notebook**: Development environment
- **Tableau**: Creating charts, dashboards and stories

## Database Structure
The dataset is organized as a relational database and includes football data from Europe’s Top 5 leagues spanning 2014–2020. It comprises seven tables —appearances, games, leagues, players, shots, teams, and teamstats — with a total of 726,906 records. The tables are described as follows:
- **Appearances**: Player-specific match statistics
- **Games**: Match details and results
- **Leagues**: Information about the five major European leagues
- **Players**: Player biographical data
- **Shots**: Shot-specific statistics
- **Teams**: Team information
- **TeamStats**: Team performance metrics per match

You can download all tables in CSV format and access table schema information from the [Kaggle Football Dataset](https://www.kaggle.com/datasets/technika148/football-database/data?select=leagues.csv). 

## Overview of Findings
When evaluating league competitiveness, the Bundesliga stands out as one of the most competitive leagues, recording the highest average goals per game at 1.48 across all seasons, compared to Serie A's 1.41 in second place. However, the Bundesliga does not lead in average goals scored per team across seasons, with 50.19 goals compared to Serie A's 53.4. This disparity is likely due to Bundesliga teams playing fewer matches per season (34) compared to Serie A teams (38), providing Bundesliga teams with fewer opportunities to score goals. 

Additionally, shot accuracy saw a notable increase during the 2020 season across all leagues, likely influenced by factors related to COVID-19, such as fewer matches or reduced pressure from empty stadiums. Lastly, Barcelona achieved the highest average shot accuracy at 44.01% and recorded the largest goal difference of 470 goals across all seasons.

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/European%20Soccer%20League%20Dashboard%201.png" alt="European Leagues Photo" width="1000" height="550">

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
