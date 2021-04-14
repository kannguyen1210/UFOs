# UFOs

### Overview of Project
Dana’s webpage and dynamic table was working as intended with the date filter but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, we’ll add table filters for the city, state, country, and shape to the website and update the code to allow users to filter the table based on these new criteria

### Results
Once the code was updated, we can narrow down the criteria of our search gradually to have fewer data to analyze, this will help us to look through our data set much faster since we are working with fewer data with a focused search filter.

First, we would want to determine which country are we doing an analysis on. For our example, we will go with "us". Start filtering the data by enter "us" to the country field and see the result changes according to the screenshot below:
![alt text](static/country_filter.png)

However, since our data set is still too long, we will want to narrow our search even more before diving into the details of each record. Since California is famous with UFO sighting and rumors (Area 52). Let's narrow our search even more with "ca" in the State field according to the screenshot below:
![alt text](static/state_filter.png)

With two filters in place, our data is now much shorter to look through, at this point, the user can narrow the search even more by entering a city, for example, "el cajon". Once the filter is set, we now have only 5 rows of data to look at, this is a much more comfortable number of record to work with, especially if the user is planning to read the details of the "comment" column of the table. 
![alt text](static/city_filter.png)

### Summary
There are still many drawbacks to our website, for example, it does not have a functionality to allow user to save/retrieve their search history so that they can look at the data again if they chose to re-visit their search criteria.

With more time and resources, I would recommend building two more functionalities:
1. Allow users to save a search criteria for a later use and also allow the user to see a list of search criteria
2. Allow users to export their search result into a csv format so they can export the search and do more complex analysis with a tool they are comfortable with, such as Excel or Python. 