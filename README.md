# CatFishChess
A pretty minimal chess program named after my favorite chess engine, stockfish.


Basic Chess engine, if you want to use this engine to get worse at chess you are free to do so.
You can see and analyze some of the engines games here: https://www.chess.com/member/CatFish_Chess
https://www.chess.com/member/catfishofficial (Active)
----------------------------------------------------------------------------------------------------

Score: The position is either scored in pawns or mate count
    
Calculate move: The engine will think about a move and will use the depth/ time settings
    
Engine White/ Black: Will make the engine automatically plays

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

Clocks: Read below.
----------------------------------------------------------------------------------------------------
Use the arrows to set the time control (only certain ones are added) and then start the clocks by clicking "start clocks"
Time updates after the first move is played once the clocks are started
Times will not update, or be used to call a win/ loss on a position unless "start clocks" has been pushed
