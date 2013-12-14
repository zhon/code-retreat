Code Retreat
============

Who is here for the first time?

Attribut to Corey Haines & ______

Global Day
3000 programmers around the world
United at a Craftsmanship Movement
http://live.coderetreat.org/

#gdcr13

post pictures site? hashtag

sponsers

Pluralsight
Swag

Writers and Musicians Practice
------------------------------

What does a Writer, a Poet, and a Conductor have in common?

### Ray Bradbury
http://en.wikipedia.org/wiki/File:Ray_Bradbury_2009.jpg

    - Wrote every day of his life

"Ray Bradbury burned his first million words because they were unsaleable garbage."

"You can't learn to write in college. It's a very bad place for writers because the teachers always think they know more than you do—and they don't."

"Write a thousand words a day and in three years you will be a writer."

"Quantity produces quality. If you only write a few things, you are doomed."


he wrote 3,000,000 words before his first story was accepted at the age of 20


### Richard P. Gabriel
http://www.dreamsongs.com/Files/rpg-adj.jpg
Poet, Geek, Musician

In 2011, he wrote a poem every day.

"How many of you have written the same program more than ten times?"

"you must be able to see all the craft elements and thought processes the poet used to create that poem."

### Benjamin Zander
http://www.bgsu.edu/images/mc/img60160.jpg

"If you make a mistake, celebrate."

"You can't play great music until your heart has been broken; I say let's have more broken hearts and get on with it."


Code Retreat Format
---------------------

### Schedule
- Introduction
- Session 1
- Sharing & Break
- Session 2
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

### Rules of Code Retreat
- Write all code test first
- Code in 2-tuples (maybe one 3-tuple)
- Stop means STOP in the middle of
- Share your code with others
- Delete code (Save you code for the last session)


Rules of Simple Design
----------------------
- Passes all tests
- Express Intent
- No Duplication
- Minimal methods, classes, & modules

Conway's Game of Life
---------------------
http://en.wikipedia.org/wiki/Conway's_Game_of_Life

### Rules
You have a world containing cells. Each cell has 8 neighbors.
```
...
.x.
...
```

Every generation, cells live or die according to the following rules:

```Haskel
nextState :: CellState -> NeighborCount -> CellState
nextState Dead 3 = Alive
nextState _ n | n < 2 = Dead
              | n > 3 = Dead
              | Alive
```

All rules are applied to every cell at the same time.

### Videos

http://pmav.eu/stuff/javascript-game-of-life-v3.1.1/ (In JS Running)

http://www.youtube.com/watch?v=a9xAKttWgP4 (APL)


Online Editors
--------------

- http://www.cyber-dojo.com/
- http://C9.io

Programming Concepts
--------------------------------
- OO vs Functional
- Polymorphism vs Conditionals vs Hashtable vs Matrix
- Coupling/Cohesion
- Single Responsibility
- Dependency Inversion (not learned here)
- List processing
- Recursion

### Functional Programming
- Closures
- Fist order functions
- Functions: map, reduce, filter, unions, intersection
- Recursion
- Lambda

### Process of Programming
- thin slice
- intention revealing
- short method
- test coverage
- tdd

Activities
----------

### Basic Activities

- Ping pong *
- Navigator-driver
- Paper Design *
- No Computer for 10 minutes

### Missing Tool Activities

Activities which involve removing a tool developers are used to using in order to help them learn how to use other tools more effectively.

- Mute Pairing *
- No Mouse
- Text editor only
- Paper only

### Missing Feature Activities

Activities which involve removing a common langauge feature developers are used to using in order to help them learn how to use higher-levels of abstraction to write better code.

- No naked primitives
- No conditional statements *
- No loops *
- No recursion
- No objects *

### Quality Constraint Activities

Activities which impose specific quality constraints to help developers practice a particur aspect of well-written code.

- Only three lines per method *
- Immutables only, please
- Tell don't ask *

### Stretch Activities

Activities designed to stretch a group. Most of these activities tend to try to push developers into new ways of thinking about their code.

- Verbs instead of Nouns
- Code Swap
- Evil Pair *
- Baby Steps *
- Use Metaphor

Other Stuff
-----------
https://docs.google.com/document/d/1bNPnb2VGOXLxBWZLyVDyLLZ0MB-F9pEV4GNKQzl0AhM/edit
