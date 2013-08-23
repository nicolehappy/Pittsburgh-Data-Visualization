Pittsburgh-Data-Visualization
=============================

Created to house D3.js (and others as time goes by) files used at the Pittsburgh Data Visualization meetup

Example  5) Duplicate polygons 1) as SVG and 2) as D3.js

Data time! 
D3.js runs off this idea of “update”, “enter”, and “exit”.
Update is needed for both Enter and Exit. Basically it updates your SVG object with new data. 

Example 6) This shows how to apply the data to SVG Circle. At this point, looks pretty ugly. CSS to the rescue!

Example 7) 
Much better! Plus, clicking the button will remove all the odd values from the array and update the visualization. Nice, but buttons are so 1998. 

Example 8) Adding a click event to the circles themselves.
Some more info about this: https://github.com/mbostock/d3/wiki/Selections#wiki-on

Example 8b) So Franklin brought up an interesting question and I was unable to code it on the spot. Why? I made two pretty bad errors. The question was “how to add a click event to a particular circle?” 
1) I was correct in the logic, BUT in terms of IDs and Classes, they can’t start with a numeric. So instead of referencing circle#1 I should have reference circle#circle1 (the circle with ID = “circle1”) 
2) This was also incorrect logic, because the data should dictate the click events, not me. So there should be click events for all the circles that are even or odd or primes or something.....

Example 9) At this point, we know how to update, enter, and exit, but the visualization should transition from one state to another. This is huge topic in visualizations called change blindness (http://www2.psych.ubc.ca/~rensink/flicker/). 

Example 10) Lastly, let’s attach a few affordances. So users know they can select (in this case, rectangles). The user will see both a cursor and the object will change with mouse-over and mouse-out events. 

