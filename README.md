# A2-Minesweeper-Box-Model



A web box model for a Minesweeper game.



## Rules



Minesweeper is a game where mines are hidden in a grid of squares. Safe squares have numbers telling you how many mines touch the square. You can use the number clues to solve the game by opening all of the safe squares. If you click on a mine you lose the game.



Windows Minesweeper always makes the first click safe. You open squares with the left mouse button and put flags on mines with the right mouse button. Pressing the right mouse button again changes your flag into a questionmark. When you open a square that does not touch any mines, it will be empty and the adjacent squares will automatically open in all directions until reaching squares that contain numbers. A common strategy for starting games is to randomly click until you get a big opening with lots of numbers.



If you flag all of the mines touching a number, chording on the number opens the remaining squares. Chording is when you press both mouse buttons at the same time. This can save you a lot of work! However, if you place the correct number of flags on the wrong squares, chording will explode the mines.



### Functions of the Webpage



1 - Clickable buttons without functions yet;

2 - You can change the number of rows, columns and how many Mines will be generated in your game, currently only visual, doesn't work;

3 - Restart button

4 - Select the difficulty of the game, currently only clickable buttons, they don't have any functions yet;

5 - Timer and mine counter placeholders;

6 - Example of how the game board will look like;

7 - Statistics such as wins and how many games you played;



##### Tools used



This webpage was made with only HTML and CSS, no JavaScript implemented yet.



##### Files



This project contains 3 different files:

1 - main.html -> The main HTML file;

2 - styles.css -> The CSS dependency for the HTML file;

3 - layout.png -> A layout of the plan of the Webpage;



##### Future implementations



The Minesweeper game will be finished with full functionality;

Dark mode for the webpage;

Language dropdown selector;

