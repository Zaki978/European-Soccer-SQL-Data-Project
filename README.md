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

Below are three interactive Tableau dashboards for league comparisons and Arsenal's performance.
- [European Soccer Leagues Dashboard 1](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesDashboardPart1/LeaguesDashboardPart1)
- [European Soccer Leagues Dashboard 2](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesDashboardPart2/LeagueDashboardPart2)
- [Arsenal Historical Performance Dashboard](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/ArsenalHistoricPerformanceDashboard/ArsenalDashboard)

A Tableau story is used to walk through team, league and relationship level analysis and can be found here [Tableau Story](https://public.tableau.com/app/profile/zaki.bouaoudia4587/viz/EuropeanSoccerLeaguesStoryAnalysis/StoryAnalysis).

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

Additionally, shot conversion rates saw a notable increase during the 2020 season across all leagues, possibly influenced by factors related to COVID-19, such as fewer matches or reduced pressure from empty stadiums. Lastly, Barcelona achieved the highest average shot accuracy at 44.01% and recorded the largest goal difference of 470 goals across all seasons.

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/European%20Soccer%20League%20Dashboard%201.png" alt="European Leagues Photo" width="1100" height="550">

## Insights Deep Dive

### 1. League Competitiveness Analysis
- **Highest Average Goals**: The 2019 Bundesliga season recorded the highest average goals per game at 1.6.
- **Points Gap**: The Premier League has the highest average gap (68.86) between top and bottom teams, while Bundesliga has the lowest (59.00)
- **Total Games Held**: La Liga, Premier League, and Serie A each recorded the highest total matches played, with 2,660 games whereas Bundesliga has a total of 2,142 games
- League-wide statistical comparisons
- Analysis of championship diversity
- Average points and performance metrics by league

### 2. Team Performance Analysis
- Calculation of points, wins, draws, and losses across seasons
- **Highest Points in a Season**: Manchester City dominated the 2017 Premier League season with a record 100 points
- **Reigning Champion**: Manchester City won back-to-back Premier League titles in 2017 and 2018
- **Highest loss rate**: Cagliari recorded the highest loss rate at 48.68%, losing 56 of 114 games across all seasons
- 
- Goal scoring and conceding patterns

- Season-by-season team rankings
- Identification of league champions and defending champions

### 3. Player Statistics
- Top goal scorers and their conversion rates
- Player performance metrics (goals, assists, shots)
- Statistical distribution of player performance (quintile analysis)
- Detailed player statistics by team and season

### 4. Gameplay Patterns and Relationships
- **Home Advantage**: Home teams win on average 1.47 times more often than away teams across all leagues
-  **Shots on Target Percentage (SOT%) and Shot Conversion Rate (SCR)**: strong relationship between the two suggesting each 1% increase in SOT% boosts SCR by approximately 0.58%
-  **Total Red Cards and Total Losses**: Weak relationship suggesting other factors at play such as team skill, opponent strength, or gameplay strategy

### 5. Arsenal FC Specific Analysis
- **Goal-Scoring Patterns**: Overall more goals were scored at home, notably in the 2017 season with 54 home goals vs. 20 away goals.- Season-by-season performance metrics
- **Top-scoring players**: Pierre-Emerick Aubameyang	was Arsenal's lead scorer with 64	in 114 matches, followed by Alexis Sánchez with 60 goals and Alexandre Lacazette	with 50 goals. 
- **Offensive Stats**: Arsenal scored the most goals and had the most wins during the 2016 season with 77 goals and 23 wins. 

## Key Findings
1. 
3. 
4. 
6. 
7. **Barcelona had the largest goal difference** of 470 whereas Granada has the smallest goal difference of -121 across all seasons 


## Data Visualization in Tableau available on my [Tableau Public Profile](https://public.tableau.com/app/profile/zaki.bouaoudia4587/vizzes).

## Recommendations and Further Analysis
Based on the insights and findings above, I would encourage others to consider exploring the following for further analysis:
- exploring the effects of covid-19 during the 2020-2021 season
- Determining how well the expected goals (xG) estimate the actual number of goals (G) a player or a team has scored
- Explore loss rates accounting for newly relegated teams to track how they perform in leagues below 


## Author
Zaki Bouaoudia
