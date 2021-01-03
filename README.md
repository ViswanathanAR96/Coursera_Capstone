# Coursera_Capstone
Applied Data Science Capstone - IBM

## Battle of Neighborhood
This note is part of the IBM Applied Data Science Capstone project. This course is Part-4 of 4-Course Specialization. The capstone project involves using Python and libraries such as numpy, pandas, matplotlib, seaborn, and folium. The Project is 'Battle of neighborhood'.<br>
Lets say, you want to relocate to another city, due to work reasons. You adore your current neighbourhood, and lounge for same/similar neighbourhood in your new city. This project, involves finding the right town using the location data offerred by Foursquare API.

## Problem Statement
I am a city person, and I want to explore new cities. However, due to work reasons, I allowed to relocate only among these 4 states (New York, New Jersey, Connecticut, and Pennsylvania). I want to find a city of my choice to relocate. What would it be? <br>
Let me list out, what I expect a city to-have and not-to-have:
<ol>
  <li> Coffee </li>
  <li> Convenience stores </li>
  <li> Restaraunts </li>
  <li> Food trucks / Fast food joints</li>
  <li> No/Limited Pubs and Bars </li>
</ol>
  
## Data
In order to get the list of cities in New York, New Jersey, Connecticut, Pennsylvania, we use the wiki page https://en.wikipedia.org/wiki/List_of_United_States_cities_by_population. The wiki page, lists all the cities in Unites States. We will take only the cities in New York, New Jersey, Connecticut, and Pennsylvania. <br>
We will use Foursquare API to get trending venues in each city. Then, we will compare my requirements with the output we get after performing data cleaning to get a top city. 
