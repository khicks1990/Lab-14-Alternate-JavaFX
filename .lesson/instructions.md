# Instructions  

Create a JavaFX application that simulates a game of tic-tac-toe. Figure 12-38 shows an example of the application’s GUI. The GUI shown in the figure uses eight ImageView controls to display the Xs and Os. (You will find images for the X and the O to the left.)

The application should use a two-dimensional  array to simulate the game board in memory. When the user clicks the New Game button, the application should step through the array, storing a random number in the range of 0 through 1 in each element. The number 0 represents the letter O, and the number 1 represents the letter X. The application’s window should then be updated to display the game board. The application should display a message indicating whether player X won, player Y won, or the game was a tie.

Much of the code is given for you, there are comments for the sections you need to add before the main method, and in the start method. The rest is given.