# vidgame_sales

****First data project(EDA) using excel, power pivot, and simple relational database****
======
Raw data is in vgsales.csv from https://www.kaggle.com/datasets/gregorut/videogamesales  
additional data created by me in companies.txt and in excel sheet 'plaforms'

Main focus of this project is to present in simple charts and tables, diffrent statistics about video game sales, varrying from year, publisher, genere etc.
Only for showcasing proficiency in excel and simple data manipulation, analysis and visualization

STEPS TAKEN)
1)  taking unique values of Platform tab from DATA, googling full names and assinging them to company, creating table: platforms - relation with DATA(one-to-many)
2)  taking unique publishers, asked ChatGpt to give me csv file as: "Company","Country". "Country" informs where publisher is registered, creating table publisher - relation with DATA(one-to-many)
3)  Using Power Querry to add those 3 data tables to model and combaining them into database where in table DATA: Primary Key is Rank, Foreing Key(Primary for platforms) is Platform, Foreing Key(Primary for publisher) is Publisher

Here are the charts //I WILL CREATE DASHBOARD IN FUTURE OR MOVE TO NEXT PROJECT

**CHART 1 GLOBAL SALES** https://github.com/kinsin5/vidgame_sales/issues/1#issue-2255932303

**CHART 2 GLOBAL SALES BY COUNTRY TREE** https://github.com/kinsin5/vidgame_sales/issues/2#issue-2256101746

**TABLE 1 GAME RANK BY GENERES** https://github.com/kinsin5/vidgame_sales/issues/3#issue-2256112914

**CHART 3, TABLE 2**  https://github.com/kinsin5/vidgame_sales/issues/4#issue-2256322296

**CHART 4**  https://github.com/kinsin5/vidgame_sales/issues/5#issue-2256350096

**CHART 5**  https://github.com/kinsin5/vidgame_sales/issues/7#issue-2258105698


SOME ISSUES/BUG FIXING 
1)  Power Querry transforming decimal numbers from 0.0 format to 0,0, because of polish excel
2)  IDENTIFYING **2 PROBLEMS** **1:** YEARS 2017 and 2020 ARE MISSING A LOT OF VALUES AND 2016 HAVE ONLY A THIRD OF IT'S DATA// **2:** THERE IS N/A ERROR IN YEARS
3)  "Uknown" or N\A publishers also filtered to clean data

IDEAS.
1)  In chart 1. global sales by category and game I learnt that I can add labels automaticly from my specified array to change way my chart looks. (POMYSL NA GIF JAK TO ROBISZ W PRZYSZŁOSCI) 


