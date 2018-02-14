# Toadwork Assignment 1
## Yoda Says

All code should be entered within the second script tag in `index.html`. The 
tag has the class "`yoshi-code`". Feel free to examine `style.css` and change 
any colors or size values you want :-) 

1. Update the code so that every time the player clicks on a game square the
color they have chosen is listed in the box on the left. Make sure that this 
list is cleared when the player clicks "Reset"
2. Continue altering the game so that when the player clicks "Begin" a random
set of 4 colors is flashed. Then record the user's clicks and determine if 
they have followed the pattern correctly. For now, just log this result to the 
console. 
3. Now add a new function called `displayResult()` that adds a list item telling
the user whether they have succeeded or failed. You can use the code in 
`displayColor(color)` as a template for how to achieve this using `jQuery`. 
4. Extend the game in any way you want. Maybe the game can get progressively 
more difficult as the player succeeds. Maybe the game should automatically reset
all colors every time a new pattern begins. Maybe you can track the number of 
correct colors clicked and create a scoring system. 

## ROUND 2!!!
5. The `displayColor` and `displayResults` functions are very similar. Combine
them into a single function with 2 parameters that you can use for both events.
6. A new control, a number select, has been added. The value shows the number 
of flashes to start the game with. Update your code to use this number. You 
should start in `updateNumberFlashes`. 
7. As the game progresses it should get more difficult. There is a function,
`setNumberFlashes`, that will update the select with a new number of flashes. 
Every time the user gets this right the number should go up one (to a max of 
15). When they get it wrong it should go back to the default 4.