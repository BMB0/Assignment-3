## Teeko Game

### Description:

The game consists of 25 spaces connected with vertical, horizontal and diagonal lines.

The game can be divided into two phases.

### First Phase:

There are 4 black pieces and 4 red pieces. The players must select among the available squares and make a move, by the end of this phase there are 8 pieces on the board, 4 black and 4 red.

It is possible to win in the first phase, if no one wins, you move to the second phase.

### Second Fase:
In this phase the players select one of their pieces on the board and in each turn they can move the pieces in an adjacent empty field, either vertically, horizontally or diagonally.

This phase continues until one of the players is the winner.

### Rules:
- If a player forms a line of 4 tiles, he wins the game (Horizontal, Diagonal and Vertical).

- If a player forms a square, he wins the game.

- Once the 4 pieces are assigned, the player can select one and move it to an unassigned square.


### SOLUTION DESCRIPTION:

For the implementation of adversarial search, three algorithms were used: min max, alpha beta pruning and min max with depth (with and without the alpha beta pruning variant). The aforementioned algorithms were tested for their performance playing against humans in the Teeko Game. We also used a hueristic that has a matrix representing each square with a set weighting where the objective of the matrix is to place the chips in positions where there are more chances of winning.

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/winning_moves_position.png?raw=true)

Subsequently, the number of turns is taken into account, the fewer turns it takes to complete the move is worth more, and if a winning solution is found, it is worth even more(Strength).

## EXPERIMENTS:

### Execution Times per Shift

- Test 1 w/ ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Test_Times_1.png?raw=true)

- Test 1 w/o ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_No_ABP_Test_Times_1.png?raw=true)

- Test 1 w/ Shuffle

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Shuffle_Test_Times_1.png?raw=true)

- Test 1 Avg Time

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Times_Bars_Test1.png?raw=true)

- Test 2 w/ ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Test_Times_2.png?raw=true)

- Test 2 w/o ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_No_ABP_Test_Times_2.png?raw=true)

- Test 2 w/ Shuffle

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Shuffle_Test_Times_2.png?raw=true)

- Test 2 Avg Time

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Times_Bars_Test2.png?raw=true)

- Test 3 w/ ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Test_Times_3.png?raw=true)

- Test 3 w/o ABP

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_No_ABP_Test_Times_3.png?raw=true)

- Test 3 w/ Shuffle

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Min_Max_With_Depth_Shuffle_Test_Times_3.png?raw=true)

- Test 3 Avg Time

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Times_Bars_Test3.png?raw=true)

- Expanded States Test 1

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Expanded_States_test1.png?raw=true)

- Expanded States Test 2

![alt text](https://github.com/BMB0/Assignment-3/blob/main/img/Expanded_States_test2.png?raw=true)


## Conclusions.

The objective of this assignment was to develop the Teeko game and apply the MinMax algorithms and its variants. It was determined that the MinMax and MinMax Alpha beta pruning algorithms cannot be used when the state space is large. The algorithms were evaluated using both time and expanded states. The Min Max With Depth ABP and Min Max With Depth ABP and Shuffle algorithms had very similar results, but the number of expanded states and time spent in the Min Max With Depth ABP and Shuffle algorithm were lower.

Overall, the goal and challenge of developing the Teeko game and implementing the algorithms has been achieved. Obtaining satisfactory results with a number of expanded states given a clean board of: 250k+ states for the Min Max With Depth w/o Alpha Beta Pruning algorithm and less than 50k states for the Min Max With Depth ABP and Min Max With Depth ABP and Shuffle algorithms.





