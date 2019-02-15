# PredictingSATScoresInChicago

This is still relatively messy. However, I will outline the methods of what I did.


From the Chicago Tribune I created a webscrapper to scrape the score of all Illinois SAT scores 
        - https://www.chicagotribune.com/suburbs/ct-school-report-card-sat-scores-2017-htmlstory.html
      
From the City of Chicago database, I used various information like number of existing coffee shops, streetlight outages, etc.
        - For missing zipcodes that did not exist within the tables from City of Chicago, I used the addresses from the existing tables to find the zipcode for each observation with a function that got it from the GoogleMaps API.

Used variables like race by zipcode as feature from Zipatlas:
        - http://zipatlas.com/us/il/chicago/zip-code-comparison/percentage-hispanic-population.htm
     
Used a City of Chicago high school contact information that included their zip code
        
INNER JOIN ALL BY ZIPCODE -- thereby having high schools with SAT score with events related to the neighborhood ALL CONNECTED (again) by ZIPCODE! :D


Let the process of Linear Regression commence!





        
