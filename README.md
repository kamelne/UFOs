# UFO Sightings

## Overview
Dana needs help presenting her UFO sighting data that is stores in a JavaScript array. Using JavaScript, HTML, and CSS, we will build a webpage for Dana that will convert that array to a dynamic table with multiple criteria filters and present it on a html webpage formatted using CSS. 

## Results
When a user opens the webpage, they will be greeted with all the data neatly formatted into a table, and all filters blank. 

![homepage](https://user-images.githubusercontent.com/57120024/167474108-a669329d-d20d-4951-8134-ae92dec0bf73.PNG)

The Filter Search is filled with example text that is grayed out, so the user knows how to input each criteria. 

![filter serach start](https://user-images.githubusercontent.com/57120024/167476253-47cfdfa8-c40d-45ed-a8d8-ae0380d01148.PNG)

Once the user inputs criteria and clicks away from the input box the table will auto filter to the criteria. 

![filter VA](https://user-images.githubusercontent.com/57120024/167474583-1d5ae313-5d74-40f5-9fda-a4faa0773288.PNG)

To clear the filters the user just needs to delete their input text. 

If there are no results for the user's filter criteria or the input text does not match the required format a blank table will be the result. 

![no results incorrect input](https://user-images.githubusercontent.com/57120024/167475130-573f35ad-79ee-45f9-97c1-806bd121fb35.PNG)

## Summary
One drawback from the current design is the user being able to input any text they want in the search boxes. One recommendation to fix this would be to add a feature for the input boxes to auto populate text as the user inputs to only data that is in that specific search criteria. A simpler solution could be to turn the input boxes into drop down menus that are filled with data as the table is originally created. Another recommendation would be to add further filters to the table headers to allow the user to then sort columns by ascending/descending.

