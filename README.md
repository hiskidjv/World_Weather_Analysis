# World_Weather_Analysis

## Purpose

Taking the PlanMyTrip app to the next level with a travel itenerary that connect 4 hotels in locations fitting the users inputted weather parameters (in this case max temperatures between 75 and 90).  

## Deliverables

1. The Weather_Database folder holds the notebook wherein we gathered the random coordinates for 2000 locations, which resulted in about 700 cities nearby from our API call helping us get a good pool of options to output as a .csv file for later use.

2. The Vacation_search folder holds the notebook wherein we gathered the weather data by performing an API call and parsing the desired elements into a dataframe that could be sliced depending on a user's input of desired temp.  We then found nearby hotels and mapped each location with a marker layer and a pop-up for each hotel.

3. The Vacation_Itinerary folder holds the notebook wherein we created a trip itinerary using four of the desired hotels that are within driving distance and access to one another.  We mapped the itinerary and also created a focused map with markers and pop-up weather info for each of the four cities.

## Additional Notes

It appears that no hotels in the European region fit the description we sought.  It also appears that some hotel names remained blank even after searching and removing nulls and NaN rows.  This is certainly a bug to be fixed before rolling out the final version of this app to the users!
