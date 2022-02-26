# UFOs

[deployed GUTHUB page](https://dennispsmith5676.github.io/UFOs/)

UFO Sightings with JavaScript

## Purpose
- Explain the strengths and weaknesses of JavaScript "standard" and JavaScript version ES6+.
- Describe JavaScript syntax and ideal use cases.
- Build and deploy JavaScript functions, including built-in functions.
- Convert JavaScript functions to arrow functions.
- Build and deploy forEach (JavaScript for loop).
- Create, populate, and dynamically filter a table using JavaScript and HTML
## Overview
The request was to display a table organizing UFO data stored as a JavaScript array. They wanted the ability to filter by multiple criteria creating a dynamic website. The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

Results:

### Welcome to UFO Sightings!

![1](static/images/top.png)


### How the filters appear when first landing on the page:

![2](static/images/working_filters.png)

### How the filters appear after being used:
By typing in the suggested placeholder elements as the filters, the result returns 2 matches. Make sure to type everything in lower case letters and do not have spaces at the end of the text. Click off the input box or press enter to initiate the filter. To reset the filter criteria, click the refresh button. The ufo sightings in the Nav bar will take you to the github repository.

![3](static/images/bottom.png)

## Summary:
### Drawbacks:
The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. The filters require correct lower-case spellings and cannot include spaces at the end. The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon". The only acceptable input would be "el cajon".

### Recommendations:
 - The next addition to the filters should be to add a trim function to catch spaces at the end of words as well as allow for upper and lower cases. 

![4](static/images/trim.png)

- A filter on a date range might be preferable than a singular date. Typing 1/2010 did not bring up all the dates from January as hoped. Perhaps, the UFO Sightings occur more frequently in a specific month instead of a specific day within the month. It is recommended to add in a filter function to include a date range as the filter to aid in the investigation of UFO Sightings.

![5](static/images/Date.png)