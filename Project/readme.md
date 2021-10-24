### Javi Rodriguez / October 23, 2021

### Executive Summary

For my project, I decided to create a game using Python and Pygame. Since I used Python for the first time in one of the labs, I decided to explore the language further within a context that I am interested in. Pygame is a cross-platform library for creating games with the Python programming language. Pygame is a set of modules that handle things like windows, graphics, input, and collisions to allow developers to create games quickly. My goal was to create a small game in which a player has 3 lives to shoot enemies and score points. The project changed slightly as I was developing it. I decided to use the mouse for shooting controls because I found it to be more fast paced and fun. I was not able to fully complete my vision for the game due to time, but I now have a better understanding of Python and creating games.

### Part Part 1: Project Intent and Plan

I intend to pursue option 2 and implement code. I plan to create a game using Python and Pygame. I want to create an arcade shooter game where the player has three lives to clear waves of enemies to score points. The player can move with W, A, S, D, and can shoot with spacebar. Enemies will spawn off screen and chase the player. The player will earn points by destroying enemies. When an enemy hits a player, the player will lose a life. The game is over when the player loses three lives.

### Project Part 2:

My program is a top-down shooter game. In this game, you play as a small cube man who must shoot deformed cube enemies to survive. The player can move using the W, A, S, D keys. The player cannot move off of the screen. The player can rotate by moving the mouse and can shoot in the direction of the mouse by holding down the left mouse button. Enemies spawn in a random position on the screen every 3 seconds. The player must shoot an enemy to kill it. The game is over when an enemy touches the player.

#### HOW TO PLAY:
* W,A,S,D to move
* Move mouse to look around/aim
* Hold left mouse button to shoot
* Enemies spawn every 3 seconds
* Game over when touched by an enemy

### Conclusion

I had a lot of fun working on this project even though I did not get as far as I hoped. I got a lot of practice working with classes in Python while creating classes for the game, player, enemy, and bullet objects. A frequent problem I ran into was having my program crash because of TypeErrors. I found it difficult to tell the types of the variables in both my own classes and some of pygame's built in variables and functions. Another problem I ran into was trying to work with normalized vectors. For things like shooting and enemy movement, I only cared about the direction between the mouse and the player or the enemy and the player, not the distance between them. But I found out that you cannot normalize a vector with a length of zero which was often the case in my game. This caused a lot of errors and a few refactors of my code. In the future, I would like to make this game more of an actual game. As it stands right now, there is not really any objective for the player. I did not get a chance to add lives or scoring to the game. I would like to play with the difficulty of the enemies by spawning more at a single time and making them faster as the game goes on. I could also make different types of enemies with different health values. I am excited for future classes and projects, so that I can expand my programming and game developing abilities.

I enjoyed this course as it covered a broad range of topics, many of which I only had a very general understanding of. I am going to continue on to IT1050 Programming Logic. My goal is still to earn an associate of science at Tri-C and eventually a bachelors of science in computer science.
