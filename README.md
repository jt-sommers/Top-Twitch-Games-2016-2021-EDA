# Top 200 Twitch Games (2016-2021) EDA: Project Overview 
* Performed EDA on Top 200 Twitch Games dataset
* Cleaned up dataset for better analysis
* Visulaized my EDA 

## Code and Resources Used 
**Python Version:** 3.8.5  
**Packages:** pandas, numpy, matplotlib, seaborn, plotly, cufflinks

**Kaggle Dataset:** https://www.kaggle.com/rankirsh/evolution-of-top-games-on-twitch


## Data Cleaning
After importing the data, I needed to clean it up so it was usable for EDA and visualization. I made the following changes:

* Updated 'Hours_Streamed' column to hold numerical data 
*	Created a datetime column called 'Date' 
*	Reordered columns so all date related columns would be next to each other 
*	Created a seperate dataframe for only 2020 data


## EDA
I did some EDA using pandas. Below are the results.

* Number of games that reached top 200: **1,639**
* Average monthly hours watched: **4,275,711**
* Standard deviation of hours watched monthly: **15,067,785**
* Peak Vewiership of "Escape From Tarkov": **441,410**
* Total number of hours "Fortnite" was streamed: **265,129,395**
* Total number of hours watched in 2020: **16,976,473,071**
* Peak viewership of "Counter-Strike: Global Offensive" in 2020: **828,949**
* Average number of streamers that streamed "Super Mario 64" in 2020: **3,722**


## Visualization
I looked at the distributions of data and plotted accordingly. Below are the visualizations I made.

