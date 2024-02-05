# EDA-Champions-League 21-22
<p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/2340bc0d-5a5a-4806-ba38-e4a9ed164599"
 width="750">
    
## INTRODUCTION
The UEFA Champions League (UCL) is an annual club football⚽️ competition organised by the Union of European Football Associations (UEFA) and contested by top-division European clubs, deciding the competition winners through a round robin group stage to qualify for a double-legged knockout format, and a single leg final. It is one of the most prestigious football tournaments in the world and the most prestigious club competition in European football, played by the national league champions (and, for some nations, one or more runners-up) of their national associations.

In this project, I did an exploratory data analysis for the Champions League season 2021-2022 ⚽️. The main goal of this work is to visualize interesting statistical data, and found out how players and teams performed throughout the tournament.

## Libraries Used
Pandas as it is designed for versatile data manipulation and analysis.
NumPy serves as the foundation for scientific computing in Python, providing support for large arrays and matrices, along with mathematical functions. 
Matplotlib is used for the creation of diverse visualizations, while Seaborn, built on Matplotlib, simplifies statistical data visualization with a high-level interface, making it easy to generate ideas.
## Data Importing and Cleaning
Uploaded the csv datsets and checked for missing values, outliers, or inconsistencies in the data and addressed them as needed and ensured that data types are appropriate for analysis.
## Key Findings and Insights
* At first using the "[goals.csv](https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/blob/main/goals.csv)" dataset I found out some of the  basic insights like
    - total goals scored in the tournament - 370
    - total penalties scored in the tournament - 36
    - the clubs that participated(qualified) in the tournament - Real Madrid, Bayern, Ajax, Liverpool, Leipzig,
       Man. City, Paris, Benfica, Man. United, Villarreal,
       Chelsea, Sporting CP, Atlético, Dortmund, Salzburg,
       Club Brugge, Atalanta, LOSC, Inter, Juventus, Sevilla,
       Shakhtar Donetsk, Zenit, Young Boys, Wolfsburg, Sheriff,
       Porto, Dynamo Kyiv, Barcelona, Milan, Malmö, Beşiktaş
    -  most players from which club - Chelsea
    -  total goals scored  by headers - 60
    -  top players who scored max goals in the tournament where I found Benzema, Lewandowski and Haller are the top players with maximum number of goals. Where __Karim Benzema__ scored          15 goals and 3 goals by header by just playing 12 matches in all total thus making him the top goalscorer of the tournament. <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/bfd8808a-1e2d-4013-bd5b-b432a040e86f"
 width="300">
    - next i found the Portuguese RB __João Cancelo__ had scored 2 goals in the tournament as a defender which is quite impressive. <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/1e78c80d-87d9-488f-ac5e-f91036d3c45b.FPGg_ifXIAs4xRp.jpg"
 width="300">
    - goals scored from inside area of the box is around 10% and from outside area of the box is around 90%.
    - next created another bar graph showing the Top 10 Clubs with most goals where the club _Bayern Munich_ scored maximum number of goals in the tournament (31 goals) <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/ca535434-b53e-457e-8ce5-2481526200d1"
 width="300">
* Next using the "[goalkeeping.csv](https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/blob/main/goalkeeping.csv)" dataset I found out some of the basic insights like
    - total number of cleansheets in the tournament - 70
    - most number of goals conceded in the tournament was by the keeper of Club Brugge - Simon Mignolet (20 goals conceded)
    - players with most cleansheets - Thibaut Courtois (5 cleansheets)
    - penalties saved about _11.32%_ and penalties missed about _88.67%_ in the whole tournament.
    - goals saved about _65.36%_ and goals conceded about _34.63%_ in the whole tournament.
    - next I have found the top 10 keepers with most saves and also here I found that Thibaut Courtois made the maximum number of saves the entire tournament (61 saves), thus making him the best goalkeeper of the season with most number of cleansheets and most number of saves.  <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/d0b044cb-2fc8-406b-98a9-54b64bb6be08"
 width="300">
 * After this using the "[attacking.csv](https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/blob/main/attacking.csv)" dataset I found out some of the basic insights like
    - top players with most assists - Bruno Fernandes, Vinícius Júnior, Sané etc. while _Bruno Fernandes_ made the most number of assists (7 assists) in the entire tournament just by playing 7 matches. <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/2a5c9af2-9642-41fe-b369-a91c39ef5130"
 width="300">
    - top clubs with most assists - _Bayern Munich_, _Liverpool_, _Man City_ etc.
    - total assists in the tournament - __281__
    - next found out Vinícius Júnior of Real Madrid	who play as a Forward (RW) made	6 assists in the tournament.
    - top defender with most assists - _Alexander-Arnold_ of Liverpool	(4 assists) which is quite impressive. <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/1c13928c-0e18-4ac6-8f0a-c06920344abc"
 width="300">
 * Next using the "[distribution.csv](https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/blob/main/distribution.csv)" dataset I found out some of the basic insights like
     - One of the Zenit	Midfielder _Erokhin_ has the maximum pass accuracy of	98.0.
     - also when comparing the stats of the players with top assists we can see _Vinícius Júnior_ of Real Madrid with 6 assists has better cross accuracy(31) and pass accuracy(83.1) than         _Bruno Fernandes_ of Man. United.
     - players with the best cross and pass accuracy among which _Thiago Silva_ has a pass accuracy of 93.1 and cross accuracy of 100. <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/6a663c14-53b4-4ba0-ace9-9ced8630135f"
 width="300">
 * Using the "[defensive.csv](https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/blob/main/defensive.csv)" dataset I found out
     - _Casemiro_	the Real Madrid	Midfielder(CDM) has the maximum balls recovered (76) and out of 31 tackles he won 13 tackles and lost	18 tackles and had attempted 19 clearance.
     - Total Tackles won in the tounament is around 43% and Tackles lost is around 56%
     - Among the defenders _Éder Militão_	of Real Madrid and _Reinildo_ of Atlético are on the top of the table with 76 balls recovered and 6 tackles won while Eder Militao lost 13 tackles out of 19 and Renildo lost 7 tackles out of 13. <p align="center">
  <img src="https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/assets/125906962/da6d7c8b-65dc-4f02-930a-56b2874cd050"
 width="300">
 * Next Using the "[disciplinary.csv](https://github.com/BRUTALXBONG/EDA-Champions-League-21-22/blob/main/disciplinary.csv)" dataset I found out
     - percentage of red and yellow cards in a tournament, RED CARD-(4.83%) & YELLOW CARD_(95.16%)
     - player with most yellow card and fouls committed - _Balanta_ of Club Brugge had 4 yellow cards in the tournament.
     - player with most red card - _Felipe_ of Atlético had 2 red cards and 3 yellow cards in the tournament. <p align="center">
  <img src=""
 width="300">
   




  
 

