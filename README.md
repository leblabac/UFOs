# UFOs
UFO Sightings with JavaScript

## Overview 
The task was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

## Results:
### Welcome to the UFO Sightings Site!

### How the filters appear when first landing on the page:


### How the filters appear after being used: 


## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. More problematically, the filters require exact match against the data being entered (i.e. require correct lower-case spellings, does not address trailing white space.) The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only acceptable input is "el cajon".

### Recommendations: 
- The next addition to the filters should be to add a trim function to catch spaces at the end of words
- Allow entry using upper case and/or proper case as well exact match (lower case)
- Filter by date range