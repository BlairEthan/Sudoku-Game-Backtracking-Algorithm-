<h1> Sudoku-Game 🔢🧩<br>
(Backtracking-Algorithm)</br></h1>


<h2>Description</h2>
Backtracking is a type of algorithm that solves constrained solution problems by abandoning solutions as soon as it determines that the integer can not possibly be used to complete the solution. In this case we implement it to solve a soduku game.

<h3><br><b> Algorithm: </b></br></h3>
<b><i> Find a vacant area on the board</b></i>
<br> 1. Try to fill in the numbers 1 through 9 there. <br>
<br> 2. Using the present board, determine whether the digit is correct in the current position. <br>
<br> 3. Recursively try to fill the board using steps 1-3 if the digit is valid. <br>
<br> 4. Reset the square you just filled and return to the first step if it is invalid. <br>
<br> 5. We have a solution once the board is complete, as defined by this algorithm. <br>
<h2>Languages and Utilities Used</h2>

- <b>Python3</b> 
- <b>PyCharm</b>

<h2>Environments Used </h2>

- <b>macOS</b>

<h2>Program walk-through:</h2>

<p align="center">
Original Board: <br/>
<img src="Original Sudoku Board.png" height="80%" width="80%" />
<br />
<br />
Original Board along with the Completed Results <br/>
<img src="Original board along with solved results.png" height="80%" width="80%" />
<br />
<br />
By inserting the "print" function within the "solve" function we are able to see the entire solving process. <br/>
<img src="Sudoku solving pt.1.png" height="80%" width="80%" />
<img src="Sudoku solving pt.2.png" height="80%" width="80%" />
<br />
<br />
<br><h3>I also implemented a GUI for a more completed version of the code:</br></h3>
<img srs="Sudoku GUI.png" height="80%" width="80%" />
<br><h3><i>(Source code is in repository folder).</br></h3></i>
</p>
