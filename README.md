CLI based chess game
=====

To play enter the piece name and destenation coordinates.
For example: `P4D4`

The board flips after every move.

-----

## OS centric changes
#### For linux:
Line 2146: system("clear")

#### For windows:
Line 2146: system("cls")

-----

## Known bugs:
#### Easy
1. Dosnt increment 9 point when a pawn is changed for a queen or whatever when it reaches the other side.
2. At the end press any key to exit dosnt work.

#### Medium

#### Hard
1. Implementation of en passant rule.
2. It does not take into considration stale mate.

-----


