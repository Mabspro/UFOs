# UFOs
## Overview
The project was done to show a dynamic webpage that takes in user inputs and adjusts accordingly to display information about UFO sightings across a region.
For the website to work properly users will be able to filter the UFO sightings table based on multiple criteria such as the event date, city, state, country and shape.

## Resources Used
Data Source: UFO data
Software: HTML/CSS, JavaScript, Visual Studio Code 1.49.1, BootStrap 4.0.0

# Results 
## Index page
This is the initial page. The user can re-initialize the page by clicking on the navbar at the top.

## Filters
Filtering by event date:
The user enters the desired date, the change is detected and the table is updated accordingly.

Filtering by city:
The user enters the desired city, the change is detected and the table is updated accordingly.

Filtering by country:
The user enters the desired country, the change is detected and the table is updated accordingly.

Filtering by state and shape:
The user enters the desired state and shape observed, the changes are detected and the table is updated accordingly.

# Summary
Because the website relies on data that is readily displayed on the site, it makes it slightly annoying for the user to know what parameter to use for the filtering. For example to pick a city, the user would have to go through the table a find the city desired for the analysis, etc.

Fix: 
One way to address this would be to present drop-down lists including all filter values in place of the input fields. Each list would need to update after a parameter is selected in any filter. 

Also useful would be a button to clear the filters since right now they have default greyed out suggested filters. The button would be located below the last filter.
