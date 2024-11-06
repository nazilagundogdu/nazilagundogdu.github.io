---
layout: page
title: Blog
permalink: /blog/
published: true
---

Movie Trends of the Past ½ Century
 
Being movie fans, my husband and I noticed a subtle decline in the script quality of more contemporary movies. The Data Scientist in me was triggered to see whether our perceptions can be substantiated. I got to work and would like to share some of my findings with you.
 

🎦 Linear Regression on Oscar-nominated and winner movie ratings
After choosing IMDB as my main source because of its popularity and completeness, step one was to actually find the list of Oscar-nominees. Using the BeautifulSoup library in Python I pulled the names and the years for Oscar-nominees for “best picture” in the past 50 years (note this analysis does not look at best actor/actress or other categories).
 

This was followed by extracting the  links for each movie as I wanted to pull more detailed data. The data I was interested in included the overall IMDB rating, the name of the Director and the Cast, as well as whether the movie finally won the award or not.
 
 
This left me with 311 nominees and, well, 50 winners. The following diagram shows the trend of ratings for winners in the past 50 years.
 
