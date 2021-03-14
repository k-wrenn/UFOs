# UFOs
## Overview of Project
Dana asked for help to create a webpage that examines data in regards to UFOs. Initially, a webpage was made that sorted listings by date; however, Dana wished to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. These additional criteria included filters for city, state, country, and shape of the UFO.
## Resources
Data: data.js

Software: JavaScript, HTML, CSS, Chrome, VSCode

## Results
### How to perform a search:
    1. First, open the index.html file in chrome. It should bring the user to the page seen below:
    ![Full](static/images/Full.png)

    2. Scroll down, and the user will find the Filter Search area. Here, the user will be able to enter a date, city, state, country, or shape. The user can enter as many filters as desired. (The prefilled text in the filter boxes are simply place holders to provide the user wtih the proper syntax for each filter)
    ![Filter](static/images/Filter.png)

    3. Once the user hits "Enter", the table will be filtered by the serach criteria. For example purposes, San Diego, ca was entered and the results are shown below.
    ![Applied](static/images/Applied.png)

    4. To conduct a new search the user can either refresh the page or click on "UFO Sightings" in the upper right hand corner of the page (underlined below)
    ![Refresh](static/images/Refresh.png)
## Summary
One drawback of the webpage is that filters are case sensitive. For example if the user were to enter "CA" instead of "ca" the search would yield no results. Making the filters not case sensitive could improve user experience.

In addition to making the filters not case sensitive, another recommendation would be allowing the user to filter by a range of dates. This would allow the user to see all sightings within a specific range, such as a week or month. As it stands now, the user would manually have to enter each date of the week/month in order to see the results.

Second, it may be beneficial to add a drop down list for each of the different criteria. Instead of the user having to guess a possible shape of a UFO, a drop down list would allow the to see a pre-made list to filter the data by. This would also be useful in the city, state, and country filters.

Lastly, in order to keep data as up to date as possible, a user submission form may be useful. This form would allow those who saw a UFO to submit their sighting and added it to the searchable data.