# Web Scraper For Extracting English Premier League Football Players’ Data
In this project, I scraped data about all 20 English Premier League (EPL) teams' players. Each player’s inclusion in the final dataset means they have featured,
at least once, in their team’s matchday squad in the current EPL season. Data extracted for outfield players (i.e. non-goalkeepers) will be different from data 
extracted for goalkeepers since their performances are largely judged based on different statistics.
## Motivation
This project was carried out for a school assignment. The assignment required the author to scrape data from the web. I am a football fan and I picked this domain 
to make the project more interesting to me. Also, increasing my level of interest makes it more likely that I will expand the project in the future.
## Problem Definition
The project is undertaken with the following scenario in mind: a [Fantasy Premier League (FPL)](https://www.premierleague.com/news/2173986) competition participant 
wants datasets that they can manipulate to inform them on which players are most likely to produce the most FPL points in the next gameweek.
The result of this project will be two datasets (one for outfield players, the other for goalkeepers) containing each player’s data. The data for each player will be 
collected with the consideration of what statistics are best for evaluating a player’s performance; the data collected for goalkeepers will be different from data 
collected for outfield players.
Although applying this differentiation to every outfield position (i.e. defender, midfielder, striker) will help to better evaluate each outfield player’s performance,
this is out of the scope of this project. Other data can also be collected for (or left out of) the final dataset to improve the quality of decision-making. 
This is also out of the scope of this project.
## Methodology
I built the web scraper for this project in a Jupyter Notebook and set up a virtual environment (venv) for the project. To recreate the venv The required libraries 
are listed in the [_requirements.txt_](https://github.com/adedamola26/web-scraping-project/blob/main/requirements.txt) file. 
Python was used as my programming language.
## Solution
A description of the solution can be found in the [Solution section of the report](https://github.com/adedamola26/web-scraping-project/blob/main/report.pdf). 
By comprehensively commenting my code, I also made [the Notebook](fbref-scraping.ipynb)
easier to navigate. It also includes the code for generating the scatter plot below. 
![xG vs Goals scored](files%20generated%20by%20running%20notebook/scatterplot/xG%20vs%20Goals%20Chart%2028-01-2024.png)
## Outlook
I could extend this project in the future to extract more appropriate data for better evaluating each player’s performance. 
I could then use this data to train models that provide recommendations on what players to include in a squad for an upcoming FPL game week. 
The data provided by FBREF can also be used to train models for football betting predictions.
