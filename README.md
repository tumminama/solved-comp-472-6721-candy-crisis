Download Link: https://assignmentchef.com/product/solved-comp-472-6721-candy-crisis
<br>
In this project you will implement a heuristic search to play a puzzle called Candy Crisis. Candy Crisis is a type of sliding puzzle played with 14 tokens representing different types of candies in a box. The box has 15 predetermined positions arranged in a box of 3 rows and 5 columns.

Initially, the player is given a random arrangement of candies in it, and the goal of the game is to rearrange the candies into a symmetrical arrangement by sliding them one at a time into the empty space. Only a candy directly next to the empty space, not including diagonally, can be moved into it.

A symmetrical arrangement (a goal state) is one which is balanced around the middle row, and there are no constraints on the middle row. In other words, if the top row is identical to the bottom row, then the puzzle is solved.

<h3><a id="user-content-play-modes" class="anchor" href="https://github.com/elmb/candy_crisis_AI#play-modes" aria-hidden="true"></a>Play Modes</h3>

Your program should be able to run in manual mode and in automatic mode. This means that you should be able to run your program with:

<ol>

 <li>Manual entry for the player, i.e. a human indicating the moves by hand. Note that if a human enters an illegal move, your program should give a warning and allow the user to enter a new move.</li>

 <li>Automatic mode, i.e. your “AI” solving and indicating the moves. Note that if your program generates an illegal move, the entire puzzle solution will be considered wrong. After each move, your program must display the new configuration of the candy box.</li>

</ol>