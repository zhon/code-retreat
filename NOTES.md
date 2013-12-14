Code Retreat
============

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
You have a world containing cells. Each cell has up to 8 neighbors.
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
- Polymorphism vs Conditionals vs Matrix math

### Functional Programming
- Closures
- Fist order functions
- Functions: map, reduce, filter, unions, intersection
- Recursion
- Lambda

Activities
----------

### Testing
- Ping Pong
- Mute Ping Pong - Same as Ping Pong, but the pair is not allowed to talk.  No cheating with comments or any form of writing.  You can talk about things not related to the problem, but you cannot talk about design. (Facilitator note: this should be teaching about expressive design)
-Evil coder - an activity where the person implementing tries to implement the code in a way the tester doesn’t expect (also teaches expressive design)
You could combine Mute ping pong and Evil coder
-Baby steps - Every pair has their own timer. They set it for 5 minutes. They have 5 minutes to write the code.  Then 5 minutes to implement the test.  Then 5 minutes to refactor.  If they don’t finish before the timer goes off they have to delete and start over.  (People get frustrated for the first 10 minutes.)


- Remove language concepts
- No conditional statements (no ifs, no switch, no loops for conditional)
The alternatives are polymorphism and hashtables
Conditional statements are a form of primitive obsession (we tend to use the lowest level of abstraction instead of choosing a higher level).  For example, we may choose an int for an employee number instead of an employee number class.
Every method must be void (very challenging, encourages “tell don’t ask” style)
In game of life, you might have a GetNextGenaration method.  Instead you might write CreateNextGeneration
- No loops
- No naked primitives, they must be enclosed in a class
- Only 4 lines per method
- Only use immutable objects
- Not allowed to touch the mouse (you can use the mouse to discover the keystrokes)
No editor (not the best idea) teaches people to know their languages well enough they don’t need

Basic Activities
----------------

Simple activities which are good for less-experienced groups.

- Ping pong
- Navigator-driver

Missing Tool Activities
-----------------------

Activities which involve removing a tool developers are used to using in order to help them learn how to use other tools more effectively.

- No Mouse
- Text editor only
- Paper only

Missing Feature Activities
--------------------------

Activities which involve removing a common langauge feature developers are used to using in order to help them learn how to use higher-levels of abstraction to write better code.

- No naked primitives
- No conditional statements
- No loops

Quality Constraint Activities
-----------------------------

Activities which impose specific quality constraints to help developers practice a particur aspect of well-written code.

- Only four lines per method
- Immutables only, please

Stretch Activities
------------------

Activities designed to stretch a group. Most of these activities tend to try to push developers into new ways of thinking about their code.

- Verbs instead of Nouns
- Code Swap
- Mute with find the loophole

