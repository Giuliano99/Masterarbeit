# Masterthesis Giuliano Gaub
Prediction of English Premier League soccer matches, based on player data using supervised learning.

The code of the work is written entirely in Python (Jupyter Notebooks) and is subdivided into several notebooks. 
All cells in which dataframes are exported to csv files are commented out to avoid accidental overwriting of the files.
All created files are stored in the Data folder.
The following is a brief description of what is done in each notebook:

01_Import_Data:
Import and Merge dataframes from different sources

02_Feature_Engineering
Engineer Features for the classic model based on match statistics

03_Webscraping_Fbref
Extract Player Data for every matchday from fbref and transform data for further usage. 
As the HTML of the website can change, it is not guaranteed that the code for scrapping will work at all times.

04_Calculate_Player_Ratings
Weight statistics for the player rating and scale it

05_Generate_Player_Features
Generate Features from player data, using calculated ratings and Fantasy League Values

06_Exponential_Smoothing
Calculate player ratings using exponential smoothing. Find optimal smoothing factor alpha

07_Webscraping_Transfermarkt
Scrape community votes
As the HTML of the website can change, it is not guaranteed that the code for scrapping will work at all times.

08_Supervised_Learning
Apply Random Forest Classifier, perform Hyperparameter Tuning, export results from Random Forest model
Optimal values of the Hyperparaemter Tuning may vary slightly when executed several times.

09_Evaluation
Evaluate models, comparison to benchmarks