# Rug puzzle solver

Copyright 2018 Ben Eater

This code is [MIT licensed](http://en.wikipedia.org/wiki/MIT_License).

## Puzzle solver

This is a hacky visual solver for the rug puzzle presented by Matt Parker in his [rug puzzle video](https://www.youtube.com/watch?v=HViA6N3VeHw).

It turns out there are actually three different versions of the puzzle. The rug in the video which is 20 by 18 rectangles, the rug linked in the description of the video which is 15 by 13 rectangles, and the mini rug section that Matt drew which is 5 by 2 rectangles.

### 15 x 13 rug

I initially wrote this solver for the 15 by 13 rectangle version not realizing it was different than the original item. For that version, this solver finds 3178 unique triangles in the pattern. The output looks something like this:

![Output of this solver](https://raw.githubusercontent.com/beneater/rug-puzzle/master/triangles-15x13.png)

### 20 x 18 rug

However, the rug in the video—the one our 8-year old friend really cares about—is 20 by 18 rectangles. For that rug, this solver finds 7860 triangles.

![Output of this solver](https://raw.githubusercontent.com/beneater/rug-puzzle/master/triangles-20x18.png)

### 5 x 2 rug section

Matt also suggested a simpler version of the puzzle with just a 5 by 2 rectangle section:

![Output of this solver](https://raw.githubusercontent.com/beneater/rug-puzzle/master/triangles-5x2.png)
