
Writers and Musicians Practice
==============================

What does a Writer, a Poet, and a Conductor have in common?

Ray Bradbury
------------
http://en.wikipedia.org/wiki/File:Ray_Bradbury_2009.jpg

    - Wrote every day of his life

"Ray Bradbury burned his first million words because they were unsaleable garbage."

"You can't learn to write in college. It's a very bad place for writers because the teachers always think they know more than you do—and they don't."

"Write a thousand words a day and in three years you will be a writer."

"Quantity produces quality. If you only write a few things, you are doomed."


he wrote 3,000,000 words before his first story was accepted at the age of 20


Richard P. Gabriel
------------------
http://www.dreamsongs.com/Files/rpg-adj.jpg
Poet, Geek, Musician

In 2011, he wrote a poem every day.

"How many of you have written the same program more than ten times?"

"you must be able to see all the craft elements and thought processes the poet used to create that poem."

Benjamin Zander
---------------
http://www.bgsu.edu/images/mc/img60160.jpg

"If you make a mistake, celebrate."

"You can't play great music until your heart has been broken; I say let's have more broken hearts and get on with it."


Code Retreat Format
=====================

Schedule
--------
- Introduction
- Session 1
- Sharing & Break
- Session 3
- Sharing
- Lunch
- Session 4
- Sharing & Break
- Session 5 (Save your code!)
- Sharing & Break
- Session 6
- Final Group Sharing

Rules of Code Retreat
---------------------
- Write all code test first
- Code in 2-tuples (maybe one 3-tuple)
- Stop means STOP in the middle of
- Share your code with others
- Delete code (except next to last session)


Rules of Simple Design
======================
- Passes all tests
- Express Intent
- No Duplication
- Minimal methods, classes, & modules

Conway's Game of Life
=====================
http://en.wikipedia.org/wiki/Conway's_Game_of_Life

Rules
-----
You have a world containing cells. Each cell has up to 8 neighbors

```
...
.x.
...
```

Every generation cells live or die according to the following rules


```Haskel
nextState :: CellState -> NeighborCount -> CellState
nextState Dead 3 = Alive
nextState _ n | n < 2 = Dead
              | n > 3 = Dead
              | Alive
```

All rules are applied at the same time.

Videos
------

http://pmav.eu/stuff/javascript-game-of-life-v3.1.1/ (In JS Running)

http://www.youtube.com/watch?v=a9xAKttWgP4 (APL)


Online Editors
==============

- http://www.cyber-dojo.com/
- http://C9.io

Interesting Programming Concepts
================================

- closures
- fist order functions
- matrix math
- functions: map, reduce, filter, unions, intersection
- recursion
- lambda

