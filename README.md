# Video_game_backlogged_exploration

## Where is the data from? ​
The dataset was comes from Kaggle. The user that provided the [data from the site backlogged](https://www.kaggle.com/datasets/arnabchaki/popular-video-games-1980-2023)

    
## How was it collected?​
The data was web scrapped from the game log/recording site Backlogged.
    
## How was it extracted?​
The user used simple data scrapping tool Beautiful Soup.    

## What program was used to clean the data?​
The data was cleaned using R and Jupyter Notebook.

## How was the data cleaned or transformed? Be specific.​
The data was first analyzed for missing values. There were only 13 values missing so it was not significant enough to replace them. So simply filled them with NA's. I also determined there were no duplicate rows. Next I looked through to find that ratings was numeric so I converted to integar. From there I made all the column titles into lowercase and changed all the "." to "_" to make it easier when exploring the data. In a few of the rows numbers were shown as this "3.9K" to make this easier for exploration I removed the "." and then replaced the "k" with "00". Finally I converted the date from "Feb 25, 2022" to date formate "2022-02-25".

## What are the units of the numeric data?​
The types of unit is in measurements of time.

## What were the formulas used in column creation?​
There was no specific formula it was formatted to be easy to read and simple to understand.

## How is the data validated to ensure consistency?​
The data is validated through multiple people on Kaggle using the data to complete their own analysis on the data. However, the data is expected to never be updated.  

## What are the definitions for the column names? Include all columns in your dataset.​
<br> X - The index of the variable 
<br> Title - The title of the game
<br> Release_date - When the game was released 
<br> Team - The developers of the game
<br> Rating - What players rated the game
<br> Times_listed - How long it took players to beat    
<br> Number_of_reviews - The amount of reviews left by players 
<br> Genres - what genre the game is in 
<br> Summary - A summary of the game 
<br> Reviews- What the players thought about the game 
<br> Plays - What are the number of people that have played the game 
<br> Playing - How many people are currently playing the game 
<br> Backlogs - How many people have the game in their backlog 
<br> Wishlist - How many people the game in their wishlist

 
## If there are set variable options in your dataset, what are thier definitions? ​
There are no set variable options

## What are the regulations to using the data? 
THe 

## If you are referencing sources, be sure to include citations/references as needed.
