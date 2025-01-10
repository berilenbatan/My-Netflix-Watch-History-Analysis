# My-Netflix-Watch-History-Analysis
This is my course project for Sabanci University DSA210 - Introduction to Data Science course and my instructor is Özgür Asar. This work will be an analysis of my Netflix watch history which goes back to over 7 years.

 # My Dataset
For this project, I used my own Netflix Watch history that I downloaded from my Account Settings as the starting point and the main data to process. This is a simple Excel file that contains only one attribute which is named "Title, Date". If it is a movie, the content goes as follows: "Movie's name" + "," + "Watched date (MM/DD/YY)". If it is a TV series/show, the content goes as follows: "Show's name" + ":" + "Season Number" + "Episode's name" + "," + "Watched date (MM/DD/YY)". I extracted them into following attributes and creating seperate columns: Movie name and watched date for movies; Series name, Season number, episode name and watched date, as well as date's month and years for TV shows. To acquire meaningful results from my exploratory data analysis and findings in general, this dataframe was not sufficient by itself. From The Movie Database, I added release years, IMDb ratings, number of votes, director name, production company and country of origin to my dataframe of movies. 

# Project's Aim and Scope
What this project aims to demonstrate is my watching habits in general. From this dataframe which contains temporal information about both the longevity of the series and my watching date, as well as some fundamental characteristics of the content which are the most relevant information to use while categorizing them, a wide range of conclusions and interpretations were made. 
- My favorite genre
- The year(s) I spent watching the most content using runtime information
- Whether there is a specific month or a season of the year that I watch more Netflix than usual by watch date attribute
- From which countries I watch most TV shows or movies from
- What decade's content I like best with the help of release year information
- Do I have a favorite director or a production company?
- If I watch TV shows that air for a lot of seasons or if I like shorter series
- Do I like shorter or longer episodes?
- Do I like content with high rating or do I give a chance to the badly reviewed ones (from IMDb ratings data) ?
- Whether I watch widely known movies or TV shows, or do I find unpopular ones? (from the number of votes data)
- Are there keywords that make me click? (From the movie and episode title's word by word seperated data)

  # The Files
- The raw data : MyNetflixWatchHistory.xlsx
- Preprocessing process code: Preprocessing.ipynb
- Movies Analysis and code: Movies Analysis.ipynb
- TV Shows Analysis and code: TV Shows Analysis.ipynb

