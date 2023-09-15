
![d711b3229f91221110ea1bc7ca20847f](https://github.com/johN-Kioko/dsc-phase-1-project-v2-4/assets/141914238/c269ef34-1154-43c9-ae29-99c911d3d52f)

Introduction

Microsoft sees all the big companies creating original video content and
they want to get in on the fun. They have decided to create a new movie
studio, but they don't know anything about creating movies. You are
charged with exploring what types of films are currently doing the best
at the box office.

Problem Statement
You must then translate those findings into actionable insights that the
head of Microsoft's new movie studio can use to help decide what type
of films to create.
Main Objective
Find the type of films that are currently doing better at the box office and
use the data to help create a new movie studio

Other Objective
-	Find movies with the lowest number of votes and highest number of votes
-	Find movies with the highest number of votes
-	Find the maximum number of movies that are bought locally and internationally
  
Data Understanding
The dataset used for this analysis was downloaded from different box
offices. The data was acquired from Box Office Mojo Links, IMDB,
Rotten Tomatoes, The MovieDB, The Numbers. The data contains information
about movies that have been posted in box offices. The data has two files:
IMDB movie ratings and basics and boom movies gross. The whole combined
data has 2447 rows and 12 columns. The data has the following set of

information about the movie:
-	Movie_id: This is the primary key used to identify all movies
-	Primary_title: This is the original movie title the movie was given
-	Start_year: This is the year the movie started production
-	Runtime_minutes: This is the count of minutes in each movie
-	genres: This is the classification of the movie
-	Average rating: This is the rating collected over the continent from
viewers
-	numvotes: This is the number of people who voted for the movies and
their count was used to generate ratings
-	title: This is the title the movie was produced with
-	studio: This is the studio in which each movie was produced
-	domestic gross: This is the amount of money collected from each sell
of movies in the country of origin
-	foreign gross: This is the amount of money collected from each sell
of movies in the country of origin *year: This is the year the
movie was produced

Data Preparation
Before conducting the analysis, the data had to be processed and cleaned.
The data was checked for null values and also duplicates. This data had
a few columns that had missing or null values and we had to delete the
rows to preserve the important information. Some Exploratory Data
Analysis(EDA) was done on the data to determine if there were any
patterns in the data. This data had one categorical column, meaning that
these columns had to be converted to numeric features in order to be
used in the evaluation. The categorical columns were then changed from
object to float. This data was then ready for evaluation.
The following are examples of the Visualizations obtained from the EDA:
This is to compare the number of people watching movies according to their
titles {width="6.5in" height="3.236111111111111in"}
The diagram below compares the number of people watching specific types
of Genres
 {width="6.5in" height="3.2256944444444446in"}

Conclusion
-	Interception is the most and highest-watched movie and was released
in the year 2010
-	Biography, Drama, Music is the most selling genre internationally
-	Action and thriller genres are the most-watched movies
-	The most watched and liked genres in general an action, adventure
and Sci-Fi
-	Avengers sold the highest locally while Bohemian Rhapsody sold
highest internationally

Recommendation
I would recommend that the managers of Microsoft to majorly focus on
movies with the following.
-	Adventure, Drama, Sci-Fi movies Action Thrillers, and Western Drama
are the highest-watched genres with a big gross amount.
-	Action, Adventure, and Sci-Fi movies have the majority of people watching it
both locally and in foreign countries
-	For international purposes, the Studio should focus on Adventure,
Animation and Comedy movies. Action, Thriller movies and Biography,
Drama and Music Genres because of their high selling rates in
foreign countries.
