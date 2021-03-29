# PacMan-Game


WHAT IS THIS ?
---------------
This project is a Graphical User Interface of the Arcade Game PacMan. The rules of PacMan are as follows: 

The player controls Pac-Man, who must eat all the dots inside an enclosed maze while avoiding four colored ghosts. Eating large dots called "Power Pellets" causes the ghosts to turn go into 'Pellet mode', allowing Pac-Man to eat the ghosts for a temporary period of time. 

Since I could not find a way for the Ghosts to move regardless if the User (PacMan) moves, instead I programmed it such that every move the user makes is one random movement for the ghosts. I added 4 different 'Portals' on the screen where one portal allows the User to jump across the screen. Each regular pellet PacMan collects is +1 to the final score. PacMan has 3 lives, if he loses all 3 (meaning he collides with one of the ghosts) or wins the game before dying, the final score of all the pellets collected is displayed.

I also added a feature where if one of the 3 big pellets are collected, PacMan is able to eat one of the ghosts if it can catch it in the next 15 moves.


WHY DID I MAKE THIS?
---------------------
I made this game because PacMan was my favorite Arcade game growing up and would be a fun final project for my CS 2 class. I learned more about Object Oriented Design and particularly more about the data structure of 2D arrays and when to implement them effectively.

HOW DO I USE THIS?
-------------------
In order to Compile this code, you have to run it in eclipse or another Java IDE since it is all coded in Java. Make sure to run the main method ('Main_Method') for the code to begin or else it won't compile. There are a total of 12 images that must be downloaded in order for the game to run correctly. All 12 end in either 'jpg' or 'gif' so they should be easy to spot and download.

OPTIMAL DESIGN CHOICES
-----------------------
My mindset while coding this project was to split everything into classes whenever I ran into issues. This helped me break down complex problems such as how to keep track of the ghost's locations along with PacMan's along with every pellet it collected. I had a seperate class for each ghost and PacMan location and a 'MovePacMan' class which implemented a 'KeyListener' class that told the Computer when a certain key was pressed. This prompted certain locations to change. I also had a 'PacManBoard' class that kept track of what specifically to repaint after the user clicks a key on the board.

FUTURE IMPROVEMENTS
-------------------
There are mainly two things that I would improve. The first would be to create a Timer class so that a certain move left, right, up, or down would keep PacMan going in one direction until stopped instead of currently only stopping after one move. The second thing I would do is make the Ghost's play 'smarter' rather than simply doing random moves. Since I have the PacMan location in one of the classes, perhaps I could have the ghosts get closer and closer to the ghost location as the game plays out.
