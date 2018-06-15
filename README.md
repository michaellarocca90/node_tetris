Welcome to 1618! 

This is a mob challenge, so you'll be working in teams. 
You might change teams week over week, so please create your own fork so we can easily keep track. 

Tetris Night 5 -

Form your team
Fork this repo for your member 
Create a file called team.txt, and put first, last names and email address for each participant
Commit and push team.txt to your forked repo 

Did that work? 
Great! 

Last week we consolidated collision detection and edge detection, and "game over" detection.
We also completed the set of pieces, and now they all spin, drop, and move. 
This week, we're all starting off from the same code-base again. 
We split up the growing source file into 3 files, and you can find them in this repo:

- tetris.js
- pieces.js
- mechanics.js

Please note that these files assume you're running in Node, and that pieces.js and mechanics.js are in a sub folder called "modules". 

Next challenges:

5.A Dropping Rows

Doesn't it just feel AMAZING when you line up all the pieces and drop a row?!?
How about 2 rows, or 3 - 4 rows at once =D 
Let's add that to the game. 

5.B Individual pieces 

In the current design, all pieces are essentially four 1's. 
As soon as a piece lands somewhere, it blends in with all the other pieces. 
Let's find a way to make the pieces stand out, so that it looks a little more like real Tetris

5.C Level up

Go faster! Faster! Faster! 

5.D Score 

Let's build some scoring. 
