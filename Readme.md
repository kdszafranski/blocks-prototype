# Falling Blocks

## Objective

The Objective of the game is to fall onto/land on your opponents pieces. The first player with 3 captures wins.

## Building the Board

The Starting board is flat at height 1. 4 x 4 with a row on each side that is 1 wide. 

In gameplay, each piece can become a board block, whereby it is converted to a part of the board and no longer is a movable piece. In this way the board is built up higher and higher, allowing Pieces to fall onto other pieces.

## Gameplay

- turn based
- 2 players
- start with 2 pieces each

Each turn a player can move one of their pieces up to 2 spaces. Movement up onto a higher level counts the same as a move on the same level. 

Pieces can only move up onto a level that is 1 higher than their current position.

After movement, the player can opt to convert that Piece into a Board Block. If so, the player replaces that Piece to an open starting position, leaving the converted block on the board. The converted block is no longer movable or owned by the Player. It is considered a part of the game board.

- Pieces can push opponent pieces.
- Gravity is a thing: Pieces fall down off edges if pushed or when they move.

## Capturing Pieces

Pieces can only captured by jumping down onto them from a level above. Captured pieces are converted to board pieces.