# Game of Life

![200px-Gospers_glider_gun](https://github.com/bolgaro4ka/gameoflife/assets/123888141/c31c4f4f-ed61-4a2e-a0b5-130a1ddfcad8)

The Game of Life is a cellular automaton invented by English mathematician John Conway in 1970. This is a game without players, in which a person creates an initial state, and then only observes its development. The game can create Turing-complete processes, which makes it possible to implement any Turing machine.

## Rules

- Development of colonies from three points
- The place of action of the game is a plane marked into cells, which can be unlimited, limited or closed.
- Each cell on this surface has eight neighbors surrounding it, and can be in two states: to be "alive" (filled) or "dead" (empty).
- The distribution of living cells at the beginning of the game is called the first generation. Each next generation is calculated based on the previous one according to the following rules:
    - in an empty (dead) cell, which is adjacent to three living cells, life is born;
    - if a living cell has two or three living neighbors, then this cell continues to live; otherwise (if there are less than two or more than three living neighbors), the cell dies (“from loneliness” or “from overcrowding”).
- The game ends if
    - not a single “living” cell will remain on the field;
    - the configuration at the next step will exactly (without shifts and rotations) repeat itself at one of the earlier steps (a periodic configuration is added)
    - at the next step, none of the cells changes its state (a special case of the previous rule, a stable configuration is formed)

## Run: 
gameoflife.py

## Settings and rules: 
config.py

## Keys:
- s - save the game as an image
- l - load save (image resolution must match monitor resolution)
- c - clear field
- enter - start cellular automaton
- d - drawing mode

## Imports:
- Pygame

![TM](https://github.com/bolgaro4ka/gameoflife/assets/123888141/52b8a841-c348-4016-bf43-12f7ae61d39f)

Explanations in config.py in Russian

**When copying, indicate authorship!**
