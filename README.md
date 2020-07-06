# github-profile-scraper
This scraper checks whether github contributors are working at a company as indicated. 


## Purpose and choice of design
I developed this scraper to automate tedious manual look-up and thus to speed up the scientific inquiry of research based on github data. 

The purpose of this scraper is to check whether github contributors work at the company that owns the repo to which the contributor contributes. This check is necessary as many contributors use their private github profiles even if they work for a company. 
Assuming that these contributors are contributing to the repo as part of an external community would bias our understanding of contribution patterns. As research on github contribution data becomes more popular understanding the data quality on github becomes more and more important. 
This scraper is one step in this direction but is by no means exhaustive. 

For easy editing and to facilitate the reuse of code snippits to code is available as a ipynb and not as a self-contained python program (if you fancy, feel free to turn it into one).


## Structure of scraper
As the scraper (Scraping Github Profiles - Check companies of users) requires a list of github users comprising their user name, real name and the company at which they are supposed to work at you first need to get this list before running the scraper. 
To facilitate the process of looking up the real user names you can use program on (Scraping Github Profiles - Get real names). It automatically looks up real names of users on github. After completing this steps you can user the list as input for program 2. 

1. Scraping Github Profiles - Get real names
2. Scraping Github Profiles - Check companies of users

## Documentation and details
Please find a more detailed description of both programs in the respective Jupyter Notebook file. 


This scraper is published under a MIT license. 


