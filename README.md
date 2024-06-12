The Indian Premier League (IPL) is a men's Twenty20 (T20) cricket league held annually in India.
Founded by the BCCI in 2007, the league features ten city-based franchise teams.
The IPL usually takes place during the summer, between March and May each year. 
It has an exclusive window in the ICC Future Tours Programme, resulting in fewer international cricket tours occurring during the IPL seasons.
The IPL is the most popular cricket league in the world.

Feature in the dataset are

city
date
player_of_match
venue
neutral_venue
team1 (team1 is home team except in neutral_venue games)
team2 ( team 2 is away team except in neutral_venue games)
toss_winner team who won the toss and decides whether to bat or field
toss_decision 2 decision(bat & field)
result match won by run or wicket
result_margin (margin is given in both run and wicket so for example of 8 in result_margin first see result if run than it means won by 8 run similarly if wicket in result column and 8 in this column it means won by wicket)
eliminator (in this dataset no eliminator match 'Y'yes is shown in all match its showing 'N' no which i wrong because here all matches are included even knockout so i have remove this column)
method (more than 75 value are missing because less matches are decided by dls so i removed this column also)
umpire1
umpire2
Target in dataset is

result winning team name any method(even dls and superover in case of match tied)


This dataset of IPL Matches from 2008 to 2020 does not include individual player and bowl-by-bowl data.
