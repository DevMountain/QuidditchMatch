#  Quidditch Match

For this project, we will use functions and loops to handle the ultimate quidditch match, The Holyhead Harpies vs The Montrose Magpies! 

First, a few things to keep in mind:
1) A goal is worth 10 points.
2) Catching the snitch is worth 150 points.
3) The game will only end once a team has caught the snitch.


### Part One: Introduce The Captains
Before starting the game, we must introduce the captain of each team. Create a function that takes in two parameters. One parameter to represent the captain of The Holyhead Harpies, and one parameter to represent the captain of The Montrose Magpies. Add a print statement to the body of the function that prints out "Ladies & Gentlemen, your two captains, <insert name 1> and <insert name 2>!" Call this function in your code. You may pass in whatever names you would like for the captains, but if you would like accurate captain names, visit https://harrypotter.fandom.com/wiki/Montrose_Magpies & https://harrypotter.fandom.com/wiki/Holyhead_Harpies


### Part Two: Create Our Match Functions
We will need a few different functions for our match. We are going to call these functions based on the commentary that is provided to us (as you will see below). However, before you create any more functions, create two constants or variables (whichever you think is best). The first will keep track of The Holyhead Harpies' points, and the second will keep track of The Montrose Magpies' points. Set both of these equal to zero to begin with.

1) Create a function for The Montrose Magpies' scoring of a goal with the following information in mind. We know that a goal is worth 10 points. Commentary on the match might say something like "The Magpies scored twice in a row!" so our function will need a parameter that takes in how many times the Magpies scored. Something to consider: if the Magpies score four times, we don't want to add 40 points to the scoreboard all at once. Instead, we want to add 10 points, four times. This better represents how actual game scoring would happen. So, to reflect this more realistic way of score keeping, create a for-in loop that runs for however many times the Magpies scored (hint: create a range from 1 to the number of times the team scored). Each run through of this for-in loop should add 10 points to the teams total score.

2) Following the pattern for the Magpies' scoring function, create a function for when The Holyhead Harpies score a goal. This time however, refactor your code so that a while-loop is used instead of a for-in loop (hint: you might want to add a counter variable to make sure your while-loop doesn't run forever).

3) Create a function for when The Montrose Magpies catch the snitch. Keep in mind that two major things should happen at this point. First, the Magpies should get 150 points. Any thoughts on what should happen after that? (Hint: As soon as the snitch is caught, the match is over. Double-hint: look at step 5! It is possible to call a function inside of another function!)

4) Similar to step 3, create a function for when The Holyhead Harpies catch the snitch. 

5) Create a function that will print out the winner and final score in one sentence. This should only print out once, and should compare the current scores to determine who the winner of the game is, before finally printing that winning teams' name. 



### Part Three: Let The Match Begin
Read through the following commentary and call the appropriate function.
(hint: some of the commentary below will require no call, and some will require multiple calls)

1) The whistle blows and we are underway!
2) The Holyhead Harpies get off to a fantastic start and score 4 in a row.
3) Finally the Magpies get into the match with an amazing long distance goal.
4) But the Harpies immediately counter with another 2 back-to-back goals.
5) It looks like the snitch has come into play, but neither seeker has been able to catch it.
6) The Harpies are temporarily down a player for an illegal move from their beater.
7) The Magpies are taking advantage of this situation and have scored six times while the Harpies have only managed one goal in that same amount of time.
8) The Harpies are back to full strength, and it's showing, as they just scored 3 times in a row!
9) The Harpies are dominating, but wait! It looks like the Magpies have just caught the snitch, and the game is over!


If you called your functions correctly, at the end you should have a printed out statement declaring who the winner is and what the final score is.

## Copyright
© Devmountain LLC, 2020. Unauthorized use and/or duplication of this material without express and written permission from DevMountain, LLC is strictly prohibited. Excerpts and links may be used, provided that full and clear credit is given to Devmountain with appropriate and specific direction to the original content.
