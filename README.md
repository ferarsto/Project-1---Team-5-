# Project-1---Team-5-

Dataset Name: FIFA23 OFFICIAL DATASET,
Dataset:https://www.kaggle.com/datasets/bryanb/fifa-player-stats-database?select=FIFA18_official_data.csv
Time Frame: 2021 to 2022

Executive technical resume: 
The code performs data analysis on the player information from FIFA21 and FIFA22 games. Below is a summary of the main actions and visualizations carried out:
The data of players from FIFA21 and FIFA22 is loaded into two separate DataFrames, and a "Year" column is added to distinguish between both years.
The two DataFrames are combined into a single one, named "merged_df_clean," keeping only relevant columns for analysis.
Data transformations are performed for the "Value" and "Wage" columns, removing symbols and converting them into numeric values.
A bar chart is generated to display the top 5 countries with the most players in the dataset, using the "Nationality" column.
Players with an "Overall" rating greater than 75 are filtered, and a bar chart is created to show the countries with the best players in terms of "Overall Rating."
The Geoapify API is utilized to obtain the geographic coordinates (latitude and longitude) of the countries with the best players, and a map is displayed with these locations.
A bar chart is generated to display the distribution of players by their preferred foot ("Preferred Foot").
A scatter plot is created to explore the correlation between "Overall Rating" and "Potential" of the players.
Additional visualizations include histograms of the distribution of values, wages, and ratings of players, as well as a table showing the top 10 players with the highest "Overall" and "Potential" ratings in FIFA22.
Overall, the code performs exploratory data analysis and interesting visualizations on the players from FIFA21 and FIFA22. It provides insights into the distribution of players by country, their skills, wages, and values, as well as the correlation between their ratings. The presented visualizations and charts help gain a better understanding of player characteristics and identify patterns and trends in the data
