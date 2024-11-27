# My-Netflix-Watch-History-Analysis
This is my course project for Sabanci University DSA210 - Introduction to Data Science course and my instructor is Özgür Asar. This work will be an analysis of my Netflix watch history which goes back to over 7 years.

 # My Dataset
For this project, I will be using my own Netflix Watch history that I will be downloading from my Account Settings as the starting point and the main data to process. This is a simple Excel file that contains only one attribute which is named "Title, Date". If it is a movie, the content goes as follows: "Movie's name" + "," + "Watched date (MM/DD/YY)". If it is a TV series/show, the content goes as follows: "Show's name" + ":" + "Season Number" + "Episode's name" + "," + "Watched date (MM/DD/YY)". I will be extracting them into following attributes and creating seperate columns: Movie name and watched date for movies; Series name, Season number, episode name and watched date. Also, I will be seperating movie name and show episode titles word by word to see if some patterns can be observed on that area as well. To acquire meaningful results from my exploratory data analysis and findings in general, this dataframe will not be sufficient by itself. From Python's " IMDbPy" library, I am going to add genres, runtimes, release years, IMDb ratings, number of votes, director name, production company and country of origin to my dataframe. 

# Project's Aim and Scope
What this project aims to demonstrate is my watching habits in general. From this dataframe which contains temporal information about both the longevity of the series and my watching date, as well as some fundamental characteristics of the content which are the most relevant information to use while categorizing them, a wide range of conclusions and interpretations can be made. 
## This includes but is not limited to:
My favorite genre
The year I spent watching the most content using runtime information
Whether there is a specific month or a season of the year that I watch more Netflix than usual by watch date attribute
From which countries I watch most TV shows or movies from?
What decade's content I like best with the help of release year information
Do I have a favorite director or a production company?
If I watch TV shows that air for a lot of seasons or if I like shorter series
Do I like shorter or longer episodes?
Do I like content with high rating or do I give a chance to the badly reviewed ones (from IMDb ratings data) ?
Whether I watch widely known movies or TV shows, or do I find unpopular ones? (from the number of votes data)
Are there keywords that make me click? (From the movie and episode title's word by word seperated data)

# Plan
The preprocessing of the initial column than Netflix provides will require a more complex seperation than a "TRIM" function from Excel, because there are sometimes columns and commas in show and movie titles and episodes as well. Therefore, I will be using Python's "pandas" library's functions like split, strip and join to create meaningful attributes. For title's word by word seperation, a seperate Worksheet could be used as well in order to not complexify the table, I will preeced according to some explorations and data manipulation practices. Then, the additional information will be added from the imdb library of Python by iterating through the original dataframe rows. After consolidating this whole dataset, trends that are exemplified above will be concluded using Exploratory Data Analysis and they will be visualized as well. Lastly, the data could be fit to a machine learning algorithm to recommend me shows from the IMDb library as well. 

