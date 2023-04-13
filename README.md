# cricket_players_analysis
This is an end to end project using WebScrapper (Bright Data), BI tools (python), and visualisation with Power BI, to determine top 11 cricket players  based on their performance

**The problem:**

Fantasy cricket is one of the most influential and rising platforms where people use their knowledge on players to create teams and earn money

Fantasy cricket is a part of the fantasy sports genre. It is an online game in which a virtual team of real cricket players is created and points are scored depending on how those players perform in real-life matches.

I am trying to use the data available at https://www.espncricinfo.com of T20 World Cup 2020, to analyze the player performance, so as to build a team which has the highest chances of winning against any other team. Although this project is fictional in terms of implementation, this team can possibly outrank any other team or combination of players. 

**Methods used:**
Step 1 (Extract): Scrap data from the above mentioned website using WebScrapper, Bright Data 
The data which I have extracted consists of 4 JSON files, Match Summary, Batting Summary, Bowling Summary, Player Profile

Step 2 (Transform): Load the data files in Python and convert them to csv. Create a Primary Key column for each table, so as to create a reference 
when used in Loading the data and doing operations

Step 3: (Load): The data is then further loaded into Power BI for analysis and outcome


