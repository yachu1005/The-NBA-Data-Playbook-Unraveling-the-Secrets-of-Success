# The NBA Data Playbook Unraveling the Secrets of Success

<img width="267" alt="Screenshot 2023-12-12 at 22 45 17" src="https://github.com/yachu1005/The-NBA-Data-Playbook-Unraveling-the-Secrets-of-Success/assets/145074370/2585293b-031e-4bd1-b4c9-ea25f57309a4">



Team Members: Ya Chu Hsu, Ali Saadeddine, Bennett Blanco, Riris Grace, Saumya Anand, Sulaiman Alhomoud



## Table of Contents
1.   Problem Definition
2.   Executive Summary
3.   Entity Relationship Diagram
4.   Introduction, Motivation, and Importance of the project
5.   Data Source
6.   Data cleaning and preparation
7.   Exploratory Data Analysis
8.   Key Findings & Conclusion
9.   References
10.  Data Dictionaries *(Lots of tables, so it is appended)*



## Problem Definition
The NBA is the pinnacle of basketball, bringing together the best talent from around the world. It is also notorious for being very player-stats-driven, which often influences the decision-making of coaching and teams. Our goal is to analyze data for players, coaches, and organizations within the NBA to get a data-driven understanding of how all of these actors interact. For the scope of this project, we’ll look at what drives the financial performance of organizations, as well as how player and team performance has affected wins/losses throughout the history of the league.
<br/>
<br/>

Each actor within the NBA will be able to realize value from this analysis. A better understanding of how each actor interacts with each other can help opponents strategize for upcoming games, guide organizations to make data-driven financial decisions, or influence decision-making in sports betting.


## Executive Summary
The comprehensive analysis of NBA player performance, team dynamics, and financial trends reveals several key insights. Kevin Durant stands out as the scoring leader, emphasizing the dominance of top-tier players in the current era. LeBron James, despite lacking formal collegiate education, emerges as the highest-paid player. The correlation between top contributors and high scorers underscores the significance of offensive prowess over assists. Defensive prowess is exemplified by DeAndre Jordan, while successful coaching performances by legends like Steve Kerr and Phil Jackson are highlighted. Team-wise, the Los Angeles Lakers demonstrate consistent excellence, while fan engagement, reflected in attendance, is notably strong for teams like the Chicago Bulls. The timing of games at 8:00 pm correlates with higher scores, indicating more exciting matchups. Additionally, the analysis sheds light on the evolving landscape of player salaries over the years, reflecting the impact of inflation.



## Entity Relationship Diagram

<img width="1046" alt="Screenshot 2023-12-12 at 22 37 14" src="https://github.com/yachu1005/The-NBA-Data-Playbook-Unraveling-the-Secrets-of-Success/assets/145074370/c3023c03-1179-461d-a6d1-c431a2414c46">



The ERD for the NBA Data Playbook have the interconnections among 11 tables, encapsulating various facets of NBA data, including Players, Teams, Games, Scores, and Financials. Games are associated with teams and their respective coaches, while players are connected to their performance data and salary details. Revenue streams are traced to teams across multiple years. Each game record is linked to specific team and coaching information, and player profiles are correlated with individual game statistics and financial data.The relationships between tables vary, encompassing one-to-one, one-to-many, and many-to-many associations. This data amalgamation provides comprehensive insights necessary for analyzing NBA games and unveiling interesting insights as described in Exploratory Data Analysis (EDA).



## Introduction, Motivation, and Importance of the Project
Embarking on a data analysis project focused on the NBA is fueled by the vast and intricate web of information surrounding players, coaches, and organizations within the league. The motivation behind delving into this trove of data lies in the profound impact it can have across various domains. By unraveling the interplay between players, coaches, and organizations, a clearer understanding emerges, enabling opponents to craft strategic game plans that cater to specific strengths and weaknesses. Moreover, this wealth of information can serve as a compass for organizations, steering them toward data-driven financial decisions that optimize player acquisitions, contract negotiations, and overall team management. Beyond the court, the insights derived from data analysis can also play a pivotal role in the realm of sports betting, providing enthusiasts with a well-informed basis for decision-making. In essence, the motivation behind this NBA data analysis project lies in its potential to revolutionize how we perceive, strategize, and engage with the dynamic world of professional basketball.



## Data Sources
* Web-scraped results of NBA data from https://www.basketball-reference.com/ available on Kaggle
https://www.kaggle.com/datasets/patrickhallila1994/nba-data-from-basketball-reference?select=games.csv
*  Financial data web-scraped from
https://runrepeat.com/nba-revenue-statistics
* so far ununsed --> https://www.spotrac.com/nba/

<br/>
<br/>

<img width="1514" alt="Screenshot 2023-12-12 at 22 32 35" src="https://github.com/yachu1005/The-NBA-Data-Playbook-Unraveling-the-Secrets-of-Success/assets/145074370/ef410abe-99ee-46de-939d-8e4a9d59b364">


<br/>
<br/>


<img width="1524" alt="Screenshot 2023-12-12 at 22 33 03" src="https://github.com/yachu1005/The-NBA-Data-Playbook-Unraveling-the-Secrets-of-Success/assets/145074370/962838e2-aa60-4e4d-9f3a-6ccb1f95364f">


<br/>
<br/>


<img width="1585" alt="Screenshot 2023-12-12 at 22 33 23" src="https://github.com/yachu1005/The-NBA-Data-Playbook-Unraveling-the-Secrets-of-Success/assets/145074370/23eb16df-d13c-460e-85e5-8680ffd334d8">



