<h2>Minimax AI with Alpha-beta pruning for the board game Othello/Reversi.</h2>

<div>
<h3>How is the game played?</h3>

<h4>Setting up the game</h4>

<p>AI plays as white and the user plays as black.<br>Initially, each player places two black and two white pieces in diagonals in the middle of the board in the form of a square.<br>
<br>Example:<br>
- - - - - - - -<br>
- - - - - - - -<br>
- - - - - - - -<br>
- - -WB- - -<br>
- - -BW- - -<br>
- - - - - - - -<br>
- - - - - - - -<br>
- - - - - - - -<br>


<h4>Playing the Game</h4>

<ul>
<li>The AI goes first.</li>
<li>You capture an opponent’s pieces when they lie in a straight line (in a row, column, or diagonal) between a piece you already had on the board and a piece you just played.</li>
<li>You can only play a piece that would capture at least one piece. If you have no legal moves, the turn is passed.</li>
<li>The game is over when neither player has any legal moves left. Whoever controls the most pieces on the board at that point wins.</li>
<li>THe game can be over before the board is full.</li>
</ul>

<h4>Minimax with Alpha-beta pruning</h4>
 
 <p>At each turn of the AI, it calculates the best possible move by using a minimax algorithm with predefined search depth. Larger the search depth, the more time it would
 take the AI to make its decision.</p>
 
