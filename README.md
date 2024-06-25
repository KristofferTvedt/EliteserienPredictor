# Project Overview
In this project, the goal is to predict the match winners of football matches in the top division, Eliteserien. 

### Steps to achieve the goals
1. Scrape match data using requests, BeautifulSoup and Pandas
2. Clean said data for machine learning purposes
3. Make predictions about who will be the match winner using sklearn
4. Measure error and improve our predictions

## Code
The code for this project is avaliabe here: [Here](https://github.com/KristofferTvedt/EliteserienPredictor)

File overview:
* scraping.ipynb - a jupyter notebook with the code for scraping the data needed
* predictor.ipynb - a jupyter notebook with the code for making the predictions

# Local Setup
## Installation
To use the code in this project, you will need to install the following locally:
* Jupyter
* Python 3.12+
* Python packages
  * Panadas
  * Requests
  * BeautifulSoup
  * Sklearn

## Data
The code (scraping.ipynb) scrapes [FBref](https://fbref.com/en/comps/28/2023/2023-Eliteserien-Stats) to get the data needed for our prediction algorithm. This code is quite slow, as the webpage will block the scrape requests if not slowed down.
If you only want to test the prediction model (predictor.ipynb) you can download the matches.csv, which is the output from scraping.ipynb
