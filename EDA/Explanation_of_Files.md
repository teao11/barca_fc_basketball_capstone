### NBA API
*nba_api_test.ipynb*  

This nba_api_test file connects to the nba api to pull data according to the endpoints you choose. 
This file is here to pull data only if we need to fill in missing data
*note* This will not work with Google Colab! When using the API be aware to not spam the api or else you will be penalize a time  

*nba_api_teams_players.ipynb*  

This file will pull player stats by season of all the players in the NBA and will push it into a database on postgres  


### Webscrapping
*webscraping_salaries.ipynb*  

This file is to scrape salaries off of espn.com. 
The next button now working
Next implementation can be clicking the years
Full Automation was implemented. Will scale with more information for future use


### Salaries_cleaning
*Salaries_cleaning.ipynb*  

This file will import the three csv files then clean and merge them and upload to the postgres DB
*SalaryRatings.ipynb*  

This file will take the salaries data and the stats data and combine them into a dataframe. It will then join the raptor data
