# UFOs

## Overview of Project

### Purpose of Analysis

The purpose of this analysis was to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. The original webpage and dynamic table worked properly to allow users to filter by date and automatically view the new filtered table at the click of a button. The analysis was to add additional filters to the table using the id's for city, state, country and shape.

## Results

![txfilter](imageurl)

A simple search can be performed by entering any of the criteria in the search fields. A new table can be prompted when entering a specific state. I chose to display all the sightings for the state of Texas which can be shown in the image above. 

Let's say someone wanted to search for sightings on a specific day, all they would have to do is to follow the provided input example for the date 1/10/2010 and adjust to desired date. If they would like to take it a step further and find a sighting for a specific city on that date, they would just have to also enter a city name. Since the table for my chosen date of 1/5/2010 had a limited number of entries, I chose a city that was listed and singled it out in the filter search. By pressing enter, this allowed me to view that one specific sighting for that city on that day.

![datefilter](imgurl) ![datecityfilter](imgurl)

## Summary

I think one drawback of this page would have to be the use of the country filter. From the provided data.js form, the table shown on the original homepage shows that the majority of the countries listed are from the 'us' and only 2 of the options are from 'ca'. I feel that the country filter option can be omitted or that there be a note to advise that only 2 country options can be selected if choosing only that search criteria. 

Also I feel that a more interactive table may be of better use instead since there are countless options that a user may be able to input with no return. Maybe having a strict order in which a user can search or having another filter option pop up below after choosing the initial option. So let's say we can start by allowing the user to search for country, then another filter will pop up below to search for state, then city and then the table will display all dates for that city.  