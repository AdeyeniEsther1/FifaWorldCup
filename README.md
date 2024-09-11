# FIFA WORLD CUP ANALYSIS


![FIFA WORLD CUP IMAGE](https://github.com/user-attachments/assets/5a58a9d7-92ed-4201-8571-0b46f9538c79)

## TABLE OF CONTENTS

- [INTRODUCTION](#introduction)
- [PROBLEM STATEMENT](#problem-statement)
- [DATA SOURCES](#data-sources)
- [TOOL](#tool)
- [SKILLS DEMONSTRATED](#skills-demonstrated)
- [DATA CLEANING AND DATA PREPARATION](#data-cleaning-and-data-preparation)
- [VISUALIZATIONS AND INSIGHTS](#visualizations-and-insights)
- [RESULTS](#results)
- [CONCLUSION](#conclusion)
  
### INTRODUCTION

This project explores historical trends in FIFA World Cup tournaments from 1930 to 2014, focusing on team performances, match outcomes, and tournament statistics.

![TotalGoalsScored](https://github.com/user-attachments/assets/e628b89f-2233-4e96-bcaf-588103b904f5)

### PROBLEM STATEMENT

This project explores historical trends in FIFA World Cup tournaments from 1930 to 2014, focusing on team performances, match outcomes, and tournament statistics. 

Key questions include:
- Total goals scored in each World Cup year.
- Average Goals Per Match Over the Years
- Countries with the highest total goals.
- Matches with the highest number of goals.
- Analyzing African teams' performances, including total goals scored and average match attendance.
- The analysis aims to uncover patterns and provide insights into future tournament predictions based on historical data.

### DATA SOURCES

The dataset used in this project was sourced from Kaggle, specifically the [FIFA World Cup Dataset (1930-2014)](https://www.kaggle.com/abecklas/fifa-world-cup). It contains detailed information about the tournament’s outcomes, including teams, goals scored, stages reached, and match dates.

### TOOL
Jupyter Notebook

### SKILLS DEMONSTRATED

Multiple functions from the Python and Pandas libraries were used during the data wrangling and cleaning phase of this project. The following libraries were imported for the analysis:
- Python standard libraries.
- Pandas for data manipulation and cleaning.
- Matplotlib and Seaborn for data visualization.

![Screenshot (500)](https://github.com/user-attachments/assets/9a6dd214-d73e-42d4-a423-6ddb2401ed18)

### DATA CLEANING AND DATA PREPARATION

After loading the dataset, the following steps were taken during the cleaning process:
- The data was assessed both visually and programmatically to identify potential issues.
- A copy of the original dataset was created to preserve the raw data.
- Data quality issues were addressed, such as correcting wrong data types.
- A new column, [Is_African_Team], was added to identify the number of African countries that participated in the World Cup.
- A column was created to calculate the Total Goals by summing the 'Home Team Goals' and 'Away Team Goals,' making the analysis easier.

  

  ### VISUALIZATIONS AND INSIGHTS

  Various visualizations were created to better understand the historical trends of the FIFA World Cup:
- Line plots were used to showcase the progression of goals scored over time.
  ![AverageGoalsByMatch](https://github.com/user-attachments/assets/467bbf2d-b7ff-4831-9fdc-6ac5a62db26a)

- Bar charts highlighted the top-performing teams in various tournaments.
  ![HighestScoringMatches](https://github.com/user-attachments/assets/530648e9-0d7a-4804-bd37-3eb6c3251f19)

- Bar charts showing the total goals involving African Team
  ![TotalGoalsInvolvingAfrican](https://github.com/user-attachments/assets/e2942971-cc94-4d09-a0a6-5077a307361a)


  ### RESULTS

- World Cup goals have increased over the years, with notable peaks in 1954, 1982, 2002, and 2014. Fluctuations occurred in the 1960s-70s, while the 1990s-2014 showed stability, reflecting changes in team strategies and tournament formats.
- From 1930 to the 1950s, World Cup matches saw increasing goals, peaking in the 1950s. A sharp decline followed, with goals stabilizing around 2.5-3.5 per match from the 1970s onward, reflecting evolving tactics and balanced play styles
- Brazil had the highest number of total goals.
  
  ![Screenshot (504)](https://github.com/user-attachments/assets/05797174-2bc5-4906-ba1a-09751887f2a0)

  
 ### CONCLUSION

- The chart provides a clear visualization of how the total goals per World Cup year have evolved over time, reflecting the changing dynamics of the tournament. The peaks suggest years with particularly high-scoring matches, while the overall trend indicates growth in the number of goals scored as the World Cup expanded and evolved.
- The data suggests that the FIFA World Cup saw a high-scoring period in the early tournaments, with a peak in the 1950s. However, the average goals per match decreased and stabilized in later years, indicating possible changes in tactics, defensive strategies, or the increasing competitiveness of teams.

### **Thank you for your effort in assessing this project.**
  
