# PacMan-Game
I created a PacMan game using JFrame GUI with 4 ghosts that move at random. This project demonstrated my knowledge using object oriented design as I used over 11 classes all to connect back to my main method of running the program. 

In the game, every move I make creates a random move for each of the 4 ghosts. If I run into any of the ghosts, I lose a life and start back over. However, if i collect one of the larger pellets, PacMan goes into 'Pellet mode' and is able to eat one of the ghosts.

Now, to discuss the design of the project. The two main classes I used to connect other classes and methods was 'PacMan_Board' and 'MovePacMan'. PacMan_Board held my paint() class which repainted the board when prompted to do so. It is prompted by the MovePacMan class which implements the 'keyListener' class which tells the class whether or not a certain key has been pressed.

After pressing a 'right' or 'left' key, I repaint the PacMan image accordingly. I have to have specific classes to keep track of the PacMan location, Ghost Location, whether or not coins have been collected, and lastly whether or not the PacMan is in 'Pellet Mode'. The main DATA STRUCTURE I used to do so was 2D arrays. 
