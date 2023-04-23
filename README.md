## Chess Board Implementation

#### Problem Domain

Implement a chessboard and then add in a red and blue queen.
Implement a function that determines if the queens are "under attack" based on their coordinates.

#### Feature Tasks Build Version 1.0

- [x] establish a ChessBoard class 

- [x] use the RGB format to establish the colors in the 8x8 grid

- [x] create an add_red method with column and row as input

- [x] create an add_blue method with column and row as input

- [x] create a render method to display the chessboard

    - [x] render should also allow correct coordinate input for red and blue queens
    
- [x] create a is_under_atttack method that returns a boolean

    - [x] check for horizontal attack
    
    - [x] check for vertical attack
    
    - [x] check for diagonal attack

#### Unit Tests

test the is_under-attack method with the following scenarios

- [x] horiztonal attack

- [x] vertical attack

- [x] four diagonals attack

- [x] "not under attack" attack
