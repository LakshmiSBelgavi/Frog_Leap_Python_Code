# Frog_Leap_Python_Code

Welcome to the Frog Leap Puzzle Game! This Python console-based game allows players to solve a classic frog leap puzzle, where a set of frogs can only move forward a certain number of steps or leap over another frog from the opposite side. The goal is to switch the positions of two sets of frogs, marked as 'G' and 'B', to win the game.

This code was wriiten with [Google colab] and the link to notebook (https://colab.research.google.com/drive/1owdUME2zI3iy7yuQNUlkl3vfGHjQrz33?usp=sharing)

## Instructions

- The left set of frogs ('G') can only move to the right.
- The right set of frogs ('B') can only move to the left.
- Frogs can move forward one space or leap over another frog from the opposite side.
- The puzzle is solved when the two sets of frogs have switched positions.

## How to Play

1. Run the Python script.
2. Enter the position of the selected frog (0-6) or press 'q' to quit.
3. Follow the on-screen prompts to make valid moves.
4. Continue making moves until you win the game or choose to quit.

### Example Game Board

```
Initial Game Board:
  0    1    2    3    4    5    6 
['G', 'G', 'G', '-', 'B', 'B', 'B']

Enter the position of the selected frog (0-6), or press 'q' to quit: 2
Valid move! Position 2: 3
Display Game :
  0    1    2    3    4    5    6
['G', 'G', '-', 'G', 'B', 'B', 'B']

Similarly keep entering the position values until the frogs are switched to the opposite sides and final display game status looks something like this :
   0    1    2    3    4    5    6
['B', 'B', 'B', '-', 'G', 'G', 'G']
```

Enjoy the challenge of solving the Frog Leap Puzzle Game! Feel free to contribute, report issues, or provide feedback.

