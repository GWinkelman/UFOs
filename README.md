# UFOs

## Overview of Project
The purpose of this analysis project was to learn how to use JavaScript (along with HTML and Bootstrap skills) to create an interactive webpage that displays various data about UFO sightings around the world.  The data that was used consisted of date/time, city, state, country, shape, duration (min), and comments about the sighting.  For this project specifically, the client wanted to be able to filter the data by date/time, city, state, country, and shape from the main webpage, so JavaScript, HTML, and CSS styling were used to create the webpage and also insert interactive text boxes so that these specific filters can be used.  

## Results

###All in all, the webpage looks great and is very simple to use. Listed below are the steps for using the webpage with images to help guide the process. 

- The first step is opening the HTML file in a default browser (I use Chrome and the webpage works perfectly). 
 
![step1](/images/step1.png)



- The next step is filling in the filters on the left side and then hitting enter.  For example, in the image below I used "boulder" as a filter in the city input box.  After hitting enter, you can see that all of the data in the data is from Boulder, CO (which is only 1 UFO sighting).  

![step2](/images/step2.png)



- In order to filter more data, all you need to do is keep typing the filters into the text boxes on the left-hand side.  You will have to manually clear the last search. Since Boulder, CO only had one sighting, we will use "el cajon" as our next example with multiple filters applied.  Searching with "el cajon" as the city, "triangle" as the shape, and "1/1/2010" as the date will give you the image shown below. 

![step3](/images/step3.png)



- Now you should be ready to search for the UFO data by any of the filters that are on the left-hand side.  It is important to note that case-sensitivity does matter, so keep things lowercase and enter them how they appear in the table in order to complete a successful filtered search.  (i.e. Use "ca" instead of "Ca" for California). 

## Summary
One drawback of this webpage is that it is case-sensitive. Especially since nouns like cities, countries, and states are capitalized; this filter requires the user to forget about those rules/habits in order to properly use the filter search. This is something that could be added in the coding process, but for this assignment it was not required. 

### Two recommendations that I have for furthering this interactive webpage are:
1. Create an interactive button to clear the previous search. In its current state, the webpage requires you to manually remove filters with backspace. With a "clear data" button, you could clear the search in one click which would save time for the user.  

2. To go along with the case-sensitivity drawback, a dropdown menu could be included for the different filters.  That way, instead of guessing and hoping that a certain city or state will have UFO sightings, the user can see what their overall options are first and select one from the menu. This seems nice and efficient, but it could lead to some very long dropdown menus so it would need to be neat and easy to read for the user. Since the table is dynamic, it should react to the user's typing, thus showing them right away if a filter that they have searched for is not in the data.  
