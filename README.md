# CatFishChess
A pretty minimal chess program named after my favorite chess engine, stockfish.


Basic Chess engine, if you want to use this engine to get worse at chess you are free to do so.
You can see and analyze some of the engines games here: https://www.chess.com/member/CatFish_Chess (BANNED (lol))
----------------------------------------------------------------------------------------------------

Score: How the engine rates the position in pawns 

    - (+1 is 1 pawn better for white, -1 is 1 pawn better for black)
    
    - (+/-)Mx, x being the amount of turns to play a checkmate (turns being 1 move for white, and 1 for black)
    
Calculate move: Find the engine move with the given time (in seconds) or to the given depth (in ply)

    - A ply is a single move, (1 turn for white or black)
    
Auto White/ Black: Will make the engine automatically calculate on that sides turn, and move after the move is found (at time, depth, or manually making a move)

Analysis Board: Will calculate for infinite time, stopping at the provided depth, or when a move is made (but it will start calculating the next move afterwards).

Add/Save book: Read below.
----------------------------------------------------------------------------------------------------
This engine has features allowing you to add/ modify your own opening books.

What is a book move?

    - A book move is an automatically saved move, that the engine won't have to think about/ calculate in that position, this is used to boost performance in the opening.

To add book moves:

1) Hit the "Add book option", console should print "New book started"
2) Make a move on the board (drag the piece), the position won't update but the console will print "Book move added"
3) Adding multiple moves from the same position will make the engine pick a random one
4) hitting "Save Book" will save the moves to the "openingbook.txt" file.
5) You can clear the book by opening the file and deleteing the text inside.
6) The moves are stored in the format %previous fen%_%fen after move%
