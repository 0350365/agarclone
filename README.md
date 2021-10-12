# agarclone
Simple remake of Agar.io using only JavaScript and HTML5's Canvas API (**very WIP**)

The number of cells that are rendered on screen is determined by the number of iterations of the for-loop on line 322 (default is 500);

To view the boundaries of the different quadtree partitions (off by default), uncomment the chunk of code from lines 186-206 and the line at line 304.

# Known bugs:
- When the player's cell is at the cursor, it looks like there are 2 players cells (very apparent when the cell is small);
- Cells would sometimes grow bigger than the canvas itself;
- Collision detection across quadtree boundries is a bit buggy;

# Planned future updates:
- Add intro screen, settings, etc..;
- Have camera follow the player's movements;
- Customizable player cell;
- Improve collision detection;
- Do boundary checks with the sides of the canvas only in partitions that are at the edges of the screen to improve performance. 


