# SudokuSolver-nodejs
Sudoku solver in node.js

I've always loved the sudoku game, so writing a solver will be fun. I'll try to take a few different approaches.

I won't be looking at anyone else's approach until I've got at least one approach working.

## Approaches

### Brute force approach

Just loop through each cell and attempt to insert a number that works. This should prove to be very slow. So slow I might have to abandon it.

### My personal approach to solving it manually

I'll attempt to program my own approach when solving a puzzle. I'll try this approach first.

Basically, my approach is to start with the given cells and start listing all possibilities for each un-resolved cell. Then I start to resolve the cells with only one possibility (if any). Next, I update the un-resolved cells possible values given my last resolution, and repeat. This will take some time to write out my algorythm enough to turn it into code.
