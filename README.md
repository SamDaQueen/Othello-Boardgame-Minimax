<h2>Minimax AI with alpha-beta pruning for the board game Othello/Reversi</h2>
<h4>Created as part of course CS5100-Foundations of Artificial Intelligence at Northeastern University</h4>

<div>

	<p><em>The base code in 'othello.py' other than the 'minimax_value' function was provided by the professor of the course.</em></p>

	<h3>How is the game played?</h3>

	<h4>Setting up the game</h4>

	<p>AI plays as white and the user plays as black.<br>Initially, each player places two black and two white pieces in diagonals in the middle of the board in the form of a square.<br></p>
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

	<ol>
		<li>Run 'othello.py. using the command 'python3 othello.py'</li>
		<li>Type 'play' on the next line</li>
	</ol>

	<p>Rules:</p>
	<ul>
		<li>The AI goes first.</li>
		<li>At the user's turn, they are given a list of possible moves to select from</li>
		<li>You capture an opponent’s pieces when they lie in a straight line (in a row, column, or diagonal) between a piece you already had on the board and a piece you just played.</li>
		<li>You can only play a piece that would capture at least one piece. If you have no legal moves, the turn is passed.</li>
		<li>The game is over when neither player has any legal moves left. Whoever controls the most pieces on the board at that point wins.</li>
		<li>The game can be over before the board is full.</li>
	</ul>

	<h4>Minimax with alpha-beta pruning</h4>

	<p>At each turn of the AI, it calculates the best possible move by using a minimax algorithm with predefined search depth. Larger the search depth, the more time it would
	take the AI to make its decision.</p>

	<h3>Files included</h3>

	<ol>
		<li>othello.py - Python code for the game</li>
		<li>Text files 'arbitraryBoard5.txt', 'arbitraryBoard8.txt', 'board1.txt', 'clearBestCounterMove.txt', 'clearBestMove.txt', 'endgame.txt' - Contain a search depth on first line and then an 8*8 Othello board with some board state representation</li>
		<li>Results.pdf - The comparison table between 'minimax algorithm' and 'minimax algorithm with alpha-beta pruning' for time taken (in seconds) on all the boards in text files.</li>
	</ol>

</div>