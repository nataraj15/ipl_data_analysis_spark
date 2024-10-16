# IPL Data Analysis Project

This project involves reading IPL (Indian Premier League) datasets from Amazon S3, processing the data using Apache Spark transformations, and performing analysis using SQL to generate insights. The results are visualized using Matplotlib and Seaborn.

## Project Overview

The goal of this project is to analyze IPL cricket data to derive meaningful insights from the matches. The project uses Spark for data processing and SQL for querying the data to perform aggregations and create useful metrics. The visualizations help in better understanding the results.

## Data Sources

The IPL datasets used in this project are stored in Amazon S3 and include the following five files:
1. **ball_by_ball.csv**: Contains information about each ball bowled in the IPL.
2. **player_match.csv**: Contains details about the players participating in each match.
3. **team.csv**: Provides information about the teams.
4. **player.csv**: Contains details of players.
5. **match.csv**: Provides information about the matches.

## Tools and Technologies Used

- **Apache Spark**: For data processing and applying transformations.
- **SQL**: Used to query and derive insights from the processed data.
- **Matplotlib**: For data visualization.
- **Seaborn**: For enhanced visualizations.

## Project Structure

1. **Data Ingestion**:
   - The IPL datasets are read from Amazon S3 into Spark DataFrames.

2. **Data Processing with Spark**:
   - The raw data undergoes various transformations, such as filtering, joining, and aggregations using Spark.

3. **Data Analysis Using SQL**:
   - Spark SQL is used to query the processed data and derive insights such as top run-scorers, best bowling figures, and win-loss statistics for teams.

4. **Visualization**:
   - The results of the analysis are visualized using Python libraries, Matplotlib and Seaborn. Examples include plotting the distribution of runs, wickets, and visualizing win statistics for teams.

