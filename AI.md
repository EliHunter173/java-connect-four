# AI Types

This is a description of all of the different type of AIs and their methodology.

## Random AI

This AI randomly places tokens at valid columns, not considering whether or not
they are full or whether or the current board state.

## Simple AI

This AI maximizes the number of the player's tokens within a given square
radius, defined by a class constant.

## Non-competitive AI

This AI maximizes the length of the sequence of the player's tokens that can be
created from adding a token.

## Competitive AI

This AI maximizes the length of the sequence of the player's tokens that can be
created from adding a token and minimizes the length of a sequence of other
players tokens.