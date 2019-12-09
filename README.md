# ids-nba-project
Authors: Raj Shah, Matthew Ionescu, Jed Rojas, Abhiraj Kante

Intro to Data Science project: Predict the winner of an NBA game

nba_stats_scraper_preprocessing.ipynb contains the code used to scrape the initial data. The cell block marked with a warning takes very long to run as is. This code in this cell was split and run on separate notebooks in parallel, then the data was merged to create our initial dataset. In this notebook, some preprocessing was done (record split into separate categories and win percentages were calculated, and points per game were calulated).

In finaldatascienceproject.ipynv more preprocessing was done, and our machine learning models were trained. The models used are logistic regression, decision tree, naive bayes, and k nearest neighbors. 

Add_final_stats.ipynv was used to get more data from stats.nba.com, and updates our initial data set with the new data. 
