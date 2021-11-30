# UFOs
UFO Sightings with JavaScript

## Overview 
The task was to display a table organizing UFO data stored as a JavaScript array. The client wanted the ability to filter by multiple criteria creating a dynamic website.  The table was created using JavaScript, while HTML/CSS and Bootstrap were used to modify the aesthetics of the website.

## Results:
### Welcome to the UFO Sightings Site!
![img1](https://user-images.githubusercontent.com/87709841/143980824-b588370c-fc0d-4594-9269-1aaea71210f8.PNG)

### How the filters appear when first landing on the page:
![img2](https://user-images.githubusercontent.com/87709841/143980841-1963f631-c60c-4d6c-85ec-9f57970bab6d.PNG)

### How the filters appear after being used: 
![img3](https://user-images.githubusercontent.com/87709841/143980852-f680224e-d414-49d0-9de7-e8d1a460008e.PNG)


## Summary: 

### Drawback:
The user must know specific dates, cities, or shapes to search. Some shapes like "light" might not be as intuitive. More problematically, the filters require exact match against the data being entered (i.e. require correct lower-case spellings, does not address trailing white space.) The city that was used, for example, could not be typed as "elcajon", “el cajon_”, or "El Cajon".  The only acceptable input is "el cajon".

### Recommendations: 
- The next addition to the filters should be to add a trim function to catch spaces at the end of words
- Allow entry using upper case and/or proper case as well exact match (lower case)
- Filter by date range
