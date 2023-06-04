# Premier League Analysis

This repository contains a Jupyter Notebook that performs an analysis of Premier League data from the 2023 season. The analysis includes data exploration, cleaning, integration, analysis, and visualization to gain insights into the performance and consistency of various teams.

## Data Sets

The analysis is based on the following data sets:

1. `2023_away_teams_stats.csv`: Contains statistics for away teams, including shots on goal, fouls, corner kicks, yellow cards, and more.
2. `2023_home_teams_stats.csv`: Contains statistics for home teams, similar to the away teams' data set.
3. `2023_matchday_results.csv`: Provides information about the match results, including the home team, away team, goals scored, and winners.
4. `2023_PL_standings.csv`: Includes the Premier League standings, including each team's rank, points, wins, losses, and goals scored.

## Analysis Steps

The Jupyter Notebook in this repository performs the following steps:

1. Data Exploration and Cleaning: The data sets are loaded, inspected for missing values, and cleaned. Missing values are either dropped or filled using appropriate techniques.
2. Data Integration: The away and home teams' statistics data sets are merged using the `pd.concat()` function to create a unified data set for analysis.
3. Data Analysis: The matchday results data set is filtered to select specific teams of interest. The winning percentages for each team are calculated based on the number of wins as both home and away teams.
4. Data Visualization: A line plot is created using Matplotlib to visualize the consistency of selected teams. The plot shows the winning percentages of each team over the course of the season.

## Usage

To reproduce the analysis or explore the code further, follow these steps:

1. Clone this repository to your local machine.
2. Ensure you have Jupyter Notebook installed along with the required libraries: Pandas, NumPy, and Matplotlib.
3. Open the Jupyter Notebook file (`premier_league_analysis.ipynb`) using Jupyter Notebook.
4. Run the notebook cells to execute the code step-by-step.
5. Explore the analysis, modify the code, or add additional analysis as desired.

Feel free to adapt the code or analysis to suit your specific needs and datasets. You can also utilize the provided data sets for your own Premier League analysis.

## Conclusion

This analysis provides insights into the performance and consistency of Premier League teams during the 2023 season. It demonstrates the usage of Jupyter Notebook and various data manipulation, analysis, and visualization techniques to gain valuable insights from the data.

Feel free to reach out with any questions or suggestions for further improvement. Enjoy exploring the Premier League analysis!

**Note**: The analysis is based on the data available at the time of the 2023 season and may not reflect the most current Premier League standings or statistics.
