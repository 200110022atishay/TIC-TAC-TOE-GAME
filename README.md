# TIC-TAC-TOE-GAME
In this project, we aim to develop a tic tac toe game that will be played between the computer and the human.
We will the using the MINMAX algorithm which is based on backtracking concept of Data Structures and Algorithm
We used a show instructions function which will show the tictactoe board with digits printed at each box so that the user can see where to fill 
At each step, we will also display the current situation of the board using the snowboard function so that the user can have a better idea
We will be using a character array of size 3 cross 3 and will be initializing it with *
After every input by either player or computer, we will also be using a game over function which will check whether some player had won or not by checking if any row/column/diagonal is crossed or not
We will also have a declare winner function which will tell us the winner based on whose turn it is
Whenever it is the turn of HUMAN we will tell him which blocks are empty by showing their integer value and the user will give the input to fill which box using an integer value.
Now if the turn is of the computer the computer will calculate the best move possible for calculating the best move it will use the minimax algorithm which actually calculates all the possible options.
It will calculate all the possibilities whether by choosing a particular box all that can happen and will only be picked the box which will lead to a computer win or draw.
