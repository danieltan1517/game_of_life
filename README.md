This is an didactic implementation of John Conway's Game of Life in Jai. The algorithm is meant to be a demonstrate a simple Game of Life implementation. For the sake of code simplicity, this code assumes that the dimensions of the grid will always be a power of 2 (e.g. 2x2, 4x4, 8x8, 16x16, 32x32, 64x64, etc.). The code implements a torus Game of Life, meaning that as soon as the grid hits the edge, it wraps around to the other side. 

### On John Conway's Game of Life
John Conway's Game of Life is a cellular automaton created by British mathematican John Conway. The Game of Life is a grid of cells. For each cell, each cell has the following properties:
* Any live cell with fewer than two live neighbours dies, as if by underpopulation.
* Any live cell with two or three live neighbours lives on to the next generation.
* Any live cell with more than three live neighbours dies, as if by overpopulation.
* Any dead cell with exactly three live neighbours becomes a live cell, as if by reproduction.
With these rules in mind, the cells can make interesting, chaotic, and aesthetically pleasing patterns based on these 4 simple rules.

[John Conway's Game of Life](https://en.wikipedia.org/wiki/Conway%27s_Game_of_Life)

### Controls
Click on a grid square to toggle the square on or off.

Click `Simulate` to simulate the Game of Life board. Click `Stop` to stop the simulation.

Click `Next` to go to the next generation.

Click `Zoom In` to zoom in.

Click `Zoom Out` to zoom out.

Click `Clear` to clear the board to zero.

Slide the slider back and forth to change the simulation speed.

Change the color of live cells with the combo box.

Use the arrow keys to move the camera up, down, left, or right.
