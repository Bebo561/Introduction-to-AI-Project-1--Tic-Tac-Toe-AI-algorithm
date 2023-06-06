# Install Instructions
- Git clone into a local repository on your personal computer

- Navigate into the proper directory with repository files.

- Open Terminal, run the following lines "python3 Main.py", and enjoy your game!.

- If the command above does not work, simply run "python Main.py" instead, and if that does not work, make sure you have downloaded the python dependencies from the official website on your machine.

# Dependencies 
- Python 3.11 

# Referenced Sources 
- Kylie Ying Tic Tac Toe solution

- Sebastian Lague: https://www.youtube.com/watch?v=l-hh51ncgDI&ab_channel=SebastianLague

# Overview/Report
    This project was an implementation of the min-max algorithm with alpha beta pruning in a tic tac toe game, to create    unbeatable machine opponenet. To briefly review, min-maxxing is a type of adversarial search algorithm that, specifically in this implementation, goes through a tree of possible plays in the tic tac toe game, and evaluates the advantages resulting from choosing a certain set of moves. A simulated game with a higher rating means it holds a higher advantage for the computer player, while a lower "min" rating holds an advantage for the enemy player. Alpha beta pruning is a modification to the min-max algorithm, that dramatically speeds up the run time by eliminating the need to search useless branches by comparing them to the current min and max paths searched. In the creation of my code, I heavily referenced Kylie Yings Tic Tac Toe solution, mainly due to trouble on visualizing the creation of a tic tac toe board in a terminal environment, as I am more familiar with creating game boards in languages such HTML and CSS. Regardless, one major bit of trouble I had while developing was understanding the algorithm, as I have little to no familiarity with searching algorithms beyond that of BFS and DFS. On top of that, I also had trouble understanding how to implement alpha beta pruning, which is when I referenced the video above by Sebastian Lague. One thing that I implemented on top of the source code was commenting to explain what each piece of the function is doing, which greatly aided in my understanding of the program as I could always reference back when needed. Future improvements that could be added to the project is an implementation in a webpage, which I intend to go back on and do in typescript as I already have created an ai tic tac toe project in typescript. Other improvements include a score system to keep track of wins, and reset button so the player can restart a game that is already losing, and animations to create a more interactive game that could be implemented with GUI styling. Overall, this project was an excellent practice with tree searching algorithms, and I look forward to implementing this algorithm in the future with a better understanding of its mechanics.
    