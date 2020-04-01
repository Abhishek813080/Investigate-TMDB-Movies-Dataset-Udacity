# Project-Investigate TMDB Movies Dataset

# Summary

This Tmdb movie dataset includes 10000 movies data. Which includes popularity,revenue,budget,genres and run times. These data matrics help us to understand how successful these movies are in different genres like adventure,action,documantery etc. Whole dataset duration covers 1960 to 2015.

# Goal of the Project

Our Goal is to understand steps involved in data analysis process i.e posing questions, data wraggling and data visualization. We have to analyze each and every phase of asked question.  

# Technologies Used
- Pandas
- Numpy
- Matplotlib
- csv

**Problem Researched Part**

# General Exploration

We always define a successful movie based on it’s revenue, reviews, popularity, etc. But what’s the factor associated with a successful movie? We know that movies hitting the box office are not always with high rating, or high rating movies are always not in trend. But how about popularity v.s. revenue? It seems like when a film raises a burst of upsurge, no matter what the reviews rating bad or not, people are still willing to pay for a popular movie.

# Exploratory Data Analysis

**1. How have movie production trends varied over the years?**

First I explored the movie popularity trend over years, from 1960 to 2015. I computed the mean of popularity in each year, and then plotted line chart to show the trend.On average, popularity over years is going up in recent years. The trend is reasonable due to the easily access of movie information nowadays. In the Internet age, people can easily search and gather movie information, visit various movie introduction pages, rate movies, even watching the content through different sources. Probably it is such the background that boost the popularity of movies.

**2. Which Genre has the highest voting of Movies?**
I tried to explore the Popular genres with it's vote count. I calculated the mean of genres and vote count. Based on this activity we could see that Adventure Genres has most vote count throughout the genres.

**3. What is the favourable runtime duration of movies with vote count?**
    In way to answer this question I have split the runtime in 5 category super-long,long,Average,super-short,short in following minutes 0, 45, 90, 120, 240, 900 and I used bin function to do runtime cut. Later on I grouped these run-time cut with vote count and found super long movies scored highest vote count.

**4. Which day is best of releasing moving based on voting?**
    I expored the release day and found the mean of voting average & release day. Based on this activity we have found wednesday has most voting count compare to other week days.

# Conclusion

**How have movie production trends varied over the years?**
   
- Movie production has increased in 2000-2010 decade and produced maximum movie in 2014 and minimum in 1960.
- In release year trend Drama,comedy and thriller are most popular genres throughout the years 2a.Based on investigation Drama genre popularity got decreased from 1970 to 1980 but later on people took interest in it and still taking interest.
- In year wise production, people like to watch average duration movies which are 90 minutes.
-In day wise Friday has seen most release throughout the year.
- In month wise December secured highest releases throughout the year.

- Which Genre has the highest voting of Movies?</b><br>
- In vote count Adventure has highest vote count.
- Documentary genre scored max vote average throughout all genres
- People like to vote super long movies either super short duration movies.
- Wednesday is most likable day to watch movies
- December is the only month which got most released and voting because of vacations.

# Limitation

During my analysis I have found budget and revenue columns are having zero values which can give false representation of data even after replace zero with null cannot give correct represenation.






```python

```
