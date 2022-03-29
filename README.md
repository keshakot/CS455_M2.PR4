# CS455 Module 2 PR4: Goal-oriented Behaviors++   
Author: Georgiy Antonovich Bondar  

Go to https://keshakot.github.io/CS455_M2.PR4/ to play the game)

# Behaviors
Goal-oriented logic and movement: Assets/Scripts/GOBMovement.cs

# Description
1. The 'player' has four 'goals' which it seeks to satisfy - eating, sleeping, using the loo, and working.   
2. The player has the following actions: use the loo, eat a snack, eat a meal, sleep, and work.  
3. The AI selects an action by finding the one which minimizes the player's overall 'discontentment' (ex. eating will alleviate hunger, but will increase the need to use the loo).   
3. Timing here is incorporated into the impact on the weights of each action - e.g. sleeping increases the need to use the loo and to eat, for sleeping takes time, in theory. In the game, this time weight is reflected in the player needing to move to the location of the activity to perform it, as well as to stay at the location for an amount of time.  

# Changes
1. Added the 'work' action and need.  
2. Added a visualization of the rooms the actions are performed in, with the player moving around to perform the actions and then pausing at locations as the actions are performed.  
3. Actions now take a variable amount of time to perform (e.g. sleep=8s, loo=1s).  




