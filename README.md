## Overview of the Analysis

# Dana’s webpage and dynamic table are working as intended, but she’d like to provide a more in-depth analysis of UFO sightings by allowing users to filter for multiple criteria at the same time. In addition to the date, you’ll add table filters for the city, state, country, and shape.

## Results

1. Download the ufo_starterCode.js, rename it app.js, and place it in the js folder of your UFOs GitHub repository. The starter code includes the code used to populate the table from this module.
2. Create four more list elements: city, state, country, and shape. These will be similar to the "Enter Date" list element. Each element should have the same "id" as the object properties in the data.js file.
3. In Step 1 of the app.js file, create an empty filters variable to keep track of all the elements that change when a search is entered. This variable will be used in Step 5 to store the property “id” and the value that was entered from user input.
4. Next, you will need to write code for two functions whose names we’ve provided in the starter code, updateFilters() and filterTable().
5. The updateFilters() function will replace your handleClick() function and update the filters variable you created in Step 1.
6. The filterTable() function will filter the table data by the value that is entered for the "id" that has changed.
7. For Step 2, located before the buildTable(tableData) function at the end of the starter code, modify the event listener from this module so that it detects a "change" on each input element and calls the updateFilters() function.
8. In Step 3, we’ve provided the function, updateFilters(). Inside this function, you’ll write code in Steps 4-5 to update the filters based on user input.
9. In Step 4a, create a variable that saves the element that was changed using d3.select(this).
10. In Step 4b, create a variable that saves the value of the changed element’s property.
11. In Step 4c, create a variable that saves the attribute of the changed element’s id.
12. In Step 5, write an if-else statement that checks if a value was changed by the user (variable from Step 4b). If a value was changed, add the element’s id (variable from Step 4c) as the property and the value that was changed to the filters variable you created in Step 1. If a value was not entered, then clear the element id from the filters variable.

## Summary
# Drawback
* The webpage was designed in a simpler format and very less bootstrap function were utilized

# Recomendation
* More bootstrap design element
* Button could have been fancier 
