# cppChessEngine
A slightly more complicated chess engine from the old.

Basic Chess AI, if you want to use this AI to get worse at chess you are free to do so.

You can see and anaylize some of the engines games here: https://www.chess.com/member/quarelai (Anything before July 2021 is from the old engine)

This engine has features allowing you to add/ modify your own opening books, and use custom search depth.

To add book moves:

1) Hit the "Add book option", console should print "New book started"
2) Make a move on the board (drag the piece), the position won't update but the console will print "Book move added"
3) Adding multiple moves from the same position will make the engine pick a random one
4) hitting "Save Book" will save the moves to the "openingbook.txt" file.
5) You can clear the book by opening the file and deleteing the text inside.
6) The moves are stored in the format %previous fen%_%fen after move%

The library https://github.com/nkarve/surge#readme is used for move generation.
