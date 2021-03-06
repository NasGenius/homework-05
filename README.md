# Day-Planner
Homework-5 Day-Planner
## Billy Gray Homework-5 Code Quiz

* ['Day-Planner GitHub'](https://github.com/NasGenius/homework-05)
* ['Day-Planner GitHub IO'](https://nasgenius.github.io/homework-05/)
* ['Day-Planner Demo Video'](https://github.com/NasGenius/homework-05/blob/main/assets/demo/4melny.gif)

![Day-Planner Demo](assets/demo/4melny.gif)

### Summary
* HTML and CSS and Javascript documents create a day planner with an eight-hour work day
* The task manager aspect saves entries to local storage
* This project emphasizes the use of using Javascript to save and retrieve data from local storage
* This project utilizes the use of moment.js for time calculation and formatting  conversion 

## Code Validation
* Used Code Beauty for my code validation for HTML, Javascript, and CSS.

### This project has the following features: 
* A header with local time that updates live
* Seven Input Entries
* A Save button that saves items to local storage
    * Attribute changes for hour by hour time tracking 
    * Gray is past the current hour
    * Red is on the current hour
    * Green is before the current hour
    
### Psuedo code:  

* Start with Document onload
* Look up Javscript Calendar, write steps down and find matching Jquery methods
* Variables unknown until step above is complete
    ** Needs start time
    ** Needs end time
    ** Needs current time  
    ** Needs to compare each hour to current time, and determine if it is 
    ** Current time is always going to be more than start time
    ** Current time is always going to be less than end time
    ** Difference between the two
    ** For loop for starting time, it would only be able to loop up to the ending time, then what?
    ** How can we use moment duration to compare time?

### This project has script features of:

* Moment.js for local time, current time, and time conversion for individual hours
* Appended text to HTML for hour time
* Used "if/else" statement to compare time with the current time 
* Appended attributes for color current time 
* An event listener for the save buttons to save to local storage

### This project features responsive design using a Bootstrap layout
### Has responsive layout for: 
** Small devices (landscape phones, 576px and up)
** Medium devices (tablets, 768px and up)
** Large devices (desktops, 992px and up)
** Extra large devices (large desktops, 1200px and up)

### To Execute File:
> Open in browser

### Features: 
* One HTML Pages
    * Index.html 
        * Contains 8 inputs for an 8-hour work day
* One CSS Page
    * Styles.css
        * Contains styling for changing attributes and buttons
* One Javascript Page
        * Contains: 
        * Variables, including arrays and time conversion 
        * Event listeners
        * if/else if statements
        * For Loops
        * Functions 
        * Local Storage set and get 
        
### Final Thoughts
* I had a good time working on this project. Some things I didn't fully understand but my code works. I still have a lot to learn. Also, my local git is still giving me issues. I've narrowed it down to VS Code so I will continue working through that so I can get my commits pushed through locally for frequently.


