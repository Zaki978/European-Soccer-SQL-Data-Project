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
- **Highest Average Goals per Game**: The 2019 Bundesliga season recorded the highest average goals per game at 1.6
- **Highest Average Goals per Team**: Serie A averaged 53.4 goals per team per season, while Ligue 1 had the lowest at 47.54.
- **Total Games Held**: La Liga, Premier League, and Serie A each recorded the highest number of total matches played, with 2,660 games, whereas the Bundesliga has a total of 2,142 games since each team plays 34 games per season as opposed to 38 in the other three leagues
- **Points Gap**: The Premier League has the highest average point gap (68.86) between top and bottom teams, while the Bundesliga has the lowest (59.00). This ranking remained the same when calculating the gap between the top and bottom four teams, indicating that the disparity is consistent across a broader group, not just driven by a few standout teams. The larger average point gap in the Premier League suggests a more pronounced disparity between the strongest and weakest teams, where the strongest teams dominate, reducing competitiveness. The Bundesliga's smaller average point gap could signify a more balanced league; however, it is important to factor in that fewer games are played in the Bundesliga, and hence, teams earn fewer points per season, leading to smaller point gaps generally.

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/Point%20Gap%20by%20League.png" alt="Leagues Point Gaps" width="800" height="200">

### 2. Team Performance Analysis
- **Highest Points in a Season**: Manchester City dominated the 2017 Premier League season with a record 100 points
- **Premier League Reigning Champion**: Manchester City won back-to-back Premier League titles in 2017 and 2018
- **Highest Loss Rate**: Cagliari recorded the highest loss rate at 48.68%, losing 56 of 114 games across all seasons
- **Most Goals Scored**: Real Madrid scored the most goals in a season in 2014 in La Liga, 118 goals in total, equivalent to 3.11 goals per game
- **Goal Difference**: Barcelona achieved the highest goal difference (89) in the 2014 La Liga season, while Schalke 04 recorded the lowest (-61) in the 2020 Bundesliga season	

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/Goal%20Difference%20by%20Season%20by%20Team.png" alt="Goal Difference by Season and Team" width="800" height="300">

### 3. Player Statistics
- **Top Goal Scorers**: Lionel Messi scored the most goals (231), but Cristiano Ronaldo had a slightly higher goals-per-game rate (0.96 vs. Messi's 0.95) with 215 goals
- **Distribution of Average Goals**: The top quintile averaged 0.40 goals, while the bottom quintile averaged 0.08
- **Highest Goals per Game**: Robert Lewandowski had the highest goals per game in a season at an average of 1.41 in the 2020 Bundesliga season.

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/Top%20Scoring%20Players.png" alt="European Leagues Photo" width="400" height="300">

### 4. Gameplay Patterns and Relationships
- **Home Advantage**: Home teams win on average 1.47 times more often than away teams across all leagues signifying significant support impact
-  **Shots on Target Percentage (SOT%) and Shot Conversion Rate (SCR)**: A strong correlation indicates that a 1% increase in SOT% raises SCR by approximately 0.58%
-  **Total Red Cards and Total Losses**: Weak relationship suggesting other factors considerable in causing losses, such as team skill, opponent strength, or gameplay strategy

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/League%20Home%20-%20Away%20Goals.png" alt="European Leagues Photo" width="400" height="200">

### 5. Arsenal FC Specific Analysis
- **Goal-Scoring Patterns**: Overall, more goals were scored at home, notably in the 2017 season with 54 home goals vs. 20 away goals.
- **Top-scoring Players**: Pierre-Emerick Aubameyang	was Arsenal's lead scorer with 64	in 114 matches, followed by Alexis Sánchez with 60 goals and Alexandre Lacazette with 50 goals
- **Offensive Stats**: Arsenal scored the most goals and had the most wins during the 2016 season with 77 goals and 23 wins

<img src="https://github.com/Zaki978/Project-Portfolio/blob/main/assets/Arsenal%20Performance%20Dashboard%20Snapshot.png" alt="European Leagues Photo" width="1100" height="550">

## Recommendations and Further Analysis
Based on the insights and findings above, I would encourage others to consider exploring the following for further analysis:
- exploring the effects of covid-19 during the 2020-2021 season
- Determining how well the expected goals (xG) estimate the actual number of goals (G) a player or a team has scored
- Explore loss rates accounting for newly relegated teams to track how they perform in leagues below 


## Author
Zaki Bouaoudia
