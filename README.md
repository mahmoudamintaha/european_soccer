# European Soccer
SQL database manipulation and analysis using python libraries in Jupyter notebook

DATABASE LINK ON KAGGLE : https://www.kaggle.com/datasets/hugomathien/soccer

## Introduction:

In this report we will invistigate **European Football Database** that includes tables about leagues, matches and players. 

### Questions to be answered in this report:

1. What teams have the highest number of wins each year?
2. What teams have the highest number of wins between 2007-2015?
3. Is Correlation between winning and:
    * defence line class.
    * chance creation from crossing class.
    * defence aggression class.
    * buildup play positioning class.
4. Which players **gained**, **lost** the highest number of rating points between 2007-2016?
5. Does *heading accuracy* rating depend on:
    * height rating.
    * jumping rating.
    * volleys rating.
    * balance rating.
6. Does *longshots* rating depend on:
    * aggression rating.
    * weight rating.
    * shot power rating.
    * strength rating.
7. Does *dribbling* rating depend on:
    * agility rating.
    * acceleration rating.
    * reactions rating.
    * balance rating.
8. Does *sprint speed* rating depend on:
    * acceleration rating.
    * stamina rating.
    * height rating.
    * weight rating.
9. Comparison between Lionel Messi and Cristiano ronaldo overall rating trend between 2007-2015.



## Conclusion:

1. Real madrid had the highest number of wins in Europe for 3 seasons between 2007-2016.
2. Winning teams has higher percentage in using offside trap.
3. Winning teams has higher percentage in using contain and double defence rather than high press.
4. Winning teams has higher percentage in using free form during buildup phase.
5. Marco Reus gained the highest numer of overall rank points between 2007-2016.
6. Derek Riordan lost the highest numer of overll rank points between 2007-2016.
7. Variables with positive correlation:
    * (long shots / shot power) strong 
    * (sprint speed / acceleration) strong
    * (dribbling / aglity, acceleration) moderate
8. Variables with negative correlation:
    * (height / balance) strong
    * (sprint speed / weight) moderate
9. Messi had higher overall ratings in all years exept 2007, 2008.

##### Remember that:
1. number of wins are local to the teams' national competetion.
2. mathes with draw results has been omitted.
3. players and teams attributes are scraped from **FIFA Game** and may not apply to real world.
