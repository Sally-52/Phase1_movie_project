Overview
The project's primary purpose is to generate insights that can assist Microsoft in entering and succeeding in the movie industry. We will utilize exploratory data analysis to get actionable insights to assist Microsoft determine what kind of films to develop. This project will leverage existing movie data to analyze box office trends, genre performance, and financial metrics to recommend strategic directions for Microsoft's new movie studio.

Objectives
Deliver Tactical Advice: Transform the insights gained into practical recommendations for genre selection and budget distribution for Microsoft's studio operations.
Grasp Market Dynamics: Gain insights into current trends in movie genres and audience preferences, highlighting the prevailing genre trends.

Discover Profitable Movie Categories: Determine the most successful film genres in terms of box office performance, both in the domestic and international markets.
Evaluate Expenditure versus Profits: Investigate the correlation between movie budgets and their financial profitability to pinpoint the ideal investment thresholds.

INQUIRIES:
Which genere is most viewed? We are going to explore the data and record our findings.

Datasets
The datasets are stored in the 'zippedData' folder and were sourced from:

1.https://www.boxofficemojo.com/ 2.https://www.imdb.com/ 3.https://www.rottentomatoes.com/ 4.https://www.themoviedb.org/ 5.https://www.the-numbers.com/.

Import the relevant libraries
#importing libraries
import pandas as pd
import sqlite3
import csv
import os
import numpy as np
from datetime import datetime
 #importing data visualization tools 
import matplotlib.pyplot as plt
import seaborn as sns
%matplotlib inline

Data Visualization.
![alt text](image-1.png)

The histogram shows that the majority of movies have vote averages clustered around the middle range, with a peak occurring between 6 and 7. This suggests that most movies in the dataset are rated above average but not exceptionally high. In summary, the histogram provides a visual representation of the distribution of vote averages for movies in the dataset. It shows that most movies have vote averages in the middle range, with fewer movies having very low or very high ratings.

![alt text](image-2.png)
This is a scatter plot showing the the popularity vs votecount .

![alt text](image-3.png)
this is a representation of the gross income of various genres.

Conclusions.
From the findings we found out that by investing in lower-budget movies, they might offer the best return on investments but investing in higher budget movies, they may not yield proportionally higher returns always.

Recommendations
Use data analytics and machine learning algorithms to predict the potential success of each film based on factors such as genre, budget, marketing strategy, and release schedule. This can help Microsoft's new movie studio make data-driven decisions and optimize its film slate.

Consider creating a mix of different genres and sub-genres to appeal to a wider audience and reduce the risk of relying on a single genre.

Look at the demographics of the audience for each genre. This can help Microsoft's new movie studio tailor its content to the target audience and create movies that will appeal to a specific age group or gender.