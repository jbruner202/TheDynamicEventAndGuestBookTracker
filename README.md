# The Dynamic Event Guest Book & Tracker

## Overview
This project is an interactive VIP Event Guest Book that utilizes JavaScript array manipulation and loop processing structures. It dynamically maintains a list of attendees, updates a counter, and seamlessly renders the HTML to display the guest list using loops. 

## Features
- Interactive text input to add guests
- Real-time attendee counter
- Input sanitization (avoids empty submissions and trims whitespace)
- Array manipulation and loop-based rendering logic generated with AI

## How to Run
1. Clone or download this repository.
2. Open `index.html` directly in any web browser (Chrome, Firefox, Safari).
3. Test by adding new guests using the input field and "Add" button.

## AI Tools Used
AntiGravity AI Assistant was used to help formulate the `generateListHTML` core logic array structure. 

**Prompt used:** 
> Act as a JavaScript developer. Write a function called generateListHTML that accepts one parameter: listData (an array of strings). The function must use a standard looping mechanism (such as a standard for loop or a .forEach() loop) to iterate through the array. For each element in the array, it should wrap the string text inside opening `<li>` and closing `</li>` HTML tags. The function should combine all these individual HTML list tags into one single string and return that string. If the array is empty, return an empty string. Return only the function code. Do not include DOM selectors or event listeners.
