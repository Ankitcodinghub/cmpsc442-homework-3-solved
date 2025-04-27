# cmpsc442-homework-3-solved
**TO GET THIS SOLUTION VISIT:** [CMPSC442 Homework 3 Solved](https://www.ankitcodinghub.com/product/cmpsc-442-homework-3-100-points-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;123471&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;2&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (2 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;CMPSC442 Homework 3 Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (2 votes)    </div>
    </div>
TO PREPARE AND SUBMIT HOMEWORK

Follow these steps exactly, so the Gradescope autgrader can grade your homework. Failure to do so will result in a zero grade:

1. You *must* download the homework template file homework3_cmpsc442.py from Canvas. Each template file is a python file that gives you a headstart in creating your homework python script with the correct function names for autograding. For this homework (Homework 3), you will also need to download these files from Canvas:

homework3_dominoes_game_gui.py homework3_grid_navigation_gui.py homework3_tile_puzzle_gui.py

2. You *must* rename the file by replacing cmpsc442 with your PSU id from your official PSU. For example, if your PSU email id is abcd1234, you would rename your file as homework1_abcd1234.py to submit to Canvas, and to Gradescope.

4. Make sure your file can import before you submit; the autograder imports your file. If it won’t import, you will get a zero.

Instructions

In this assignment, you will explore a number of games and puzzles from the perspectives of informed and adversarial search.

A skeleton file homework3-cmpsc442.py containing empty definitions for each question has been provided. Since portions of this assignment will be graded automatically, none of the names or function signatures in this file should be modified. However, you are free to introduce additional variables or functions if needed.

You will find that in addition to a problem specification, most programming questions also include a pair of examples from the Python interpreter. These are meant to illustrate typical use cases to clarify the assignment, and are not comprehensive test suites. In addition to performing your own testing, you are strongly encouraged to verify that your code gives the expected output for these examples before submitting.

You are strongly encouraged to follow the Python style guidelines set forth in PEP 8, which was written in part by the creator of Python. However, your code will not be graded for style.

1. Tile Puzzle [40 points]

Recall from class that the Eight Puzzle consists of a 3 x 3 board of sliding tiles with a single empty space. For each configuration, the only possible moves are to swap the empty tile with one of its neighboring tiles. The goal state for the puzzle consists of tiles 1-3 in the top row, tiles 4-6 in the middle row, and tiles 7 and 8 in the bottom row, with the empty space in the lower-right corner.

A natural representation for this puzzle is a two-dimensional list of integer values between 0 and r · c – 1 (inclusive), where r and c are the number of rows and columns in the board, respectively. In this problem, we will adhere to the convention that the 0-tile represents the empty space.

2. [0 points] Suggested infrastructure.

In the TilePuzzle class, write a method get_board(self) that returns the internal representation of the board stored during initialization.

&gt;&gt;&gt; p = TilePuzzle([[1, 2], [3, 0]]) &gt;&gt;&gt; p = TilePuzzle([[0, 1], [3, 2]])

&gt;&gt;&gt; p.get_board() &gt;&gt;&gt; p.get_board()

[[1, 2], [3, 0]] [[0, 1], [3, 2]]

Write a top-level function create_tile_puzzle(rows, cols) that returns a new TilePuzzle of the specified dimensions, initialized to the starting configuration. Tiles 1 through r · c – 1 should be arranged starting from the top-left corner in row-major order, and tile 0 should be located in the lower-right corner.

&gt;&gt;&gt; p = create_tile_puzzle(3, 3) &gt;&gt;&gt; p = create_tile_puzzle(2, 4)

&gt;&gt;&gt; p.get_board() &gt;&gt;&gt; p.get_board()

[[1, 2, 3], [4, 5, 6], [7, 8, 0]] [[1, 2, 3, 4], [5, 6, 7, 0]]

In the TilePuzzle class, write a method perform_move(self, direction) that attempts to swap the empty tile with its neighbor in the indicated direction, where valid inputs are limited to the strings “up”, “down”, “left”, and “right”. If the given direction is invalid, or if the move cannot be performed, then no changes to the puzzle should be made. The method should return a Boolean value indicating whether the move was successful.

&gt;&gt;&gt; p = create_tile_puzzle(3, 3) &gt;&gt;&gt; p = create_tile_puzzle(3, 3)

&gt;&gt;&gt; p.perform_move(“up”) &gt;&gt;&gt; p.perform_move(“down”) True False

&gt;&gt;&gt; p.get_board() &gt;&gt;&gt; p.get_board()

[[1, 2, 3], [4, 5, 0], [7, 8, 6]] [[1, 2, 3], [4, 5, 6], [7, 8, 0]]

In the TilePuzzle class, write a method is_solved(self) that returns whether the board is in its starting configuration.

In the TilePuzzle class, write a method copy(self) that returns a new TilePuzzle object initialized with a deep copy of the current board. Changes made to the original puzzle should not be reflected in the copy, and vice versa.

&gt;&gt;&gt; p = create_tile_puzzle(3, 3) &gt;&gt;&gt; p = create_tile_puzzle(3, 3)

&gt;&gt;&gt; p2 = p.copy() &gt;&gt;&gt; p2 = p.copy()

&gt;&gt;&gt; p.get_board() == p2.get_board() &gt;&gt;&gt; p.perform_move(“left”) True &gt;&gt;&gt; p.get_board() == p2.get_board()

False

&gt;&gt;&gt; p = create_tile_puzzle(3, 3) &gt;&gt;&gt; b = [[1,2,3], [4,0,5], [6,7,8]]

&gt;&gt;&gt; for move, new_p in p.successors(): &gt;&gt;&gt; p = TilePuzzle(b)

… print move, new_p.get_board() &gt;&gt;&gt; for move, new_p in p.successors(): … … print move, new_p.get_board() up [[1, 2, 3], [4, 5, 0], [7, 8, 6]] …

left [[1, 2, 3], [4, 5, 6], [7, 0, 8]] up [[1, 0, 3], [4, 2, 5], [6, 7, 8]] down [[1, 2, 3], [4, 7, 5], [6, 0, 8]] left [[1, 2, 3], [0, 4, 5], [6, 7, 8]] right [[1, 2, 3], [4, 5, 0], [6, 7, 8]]

Hint: This method is most easily implemented using recursion. First define a recursive helper method iddfs_helper(self, limit, moves) that yields all solutions to the current board of length no more than limit which are continuations of the provided move list. Your main method will then call this helper function in a loop, increasing the depth limit by one at each iteration, until one or more solutions have been found.

&gt;&gt;&gt; b = [[4,1,2], [0,5,3], [7,8,6]] &gt;&gt;&gt; b = [[1,2,3], [4,0,8], [7,6,5]]

&gt;&gt;&gt; p = TilePuzzle(b) &gt;&gt;&gt; p = TilePuzzle(b)

&gt;&gt;&gt; solutions = p.find_solutions_iddfs() &gt;&gt;&gt; list(p.find_solutions_iddfs()) &gt;&gt;&gt; next(solutions) [[‘down’, ‘right’, ‘up’, ‘left’, ‘down’, [‘up’, ‘right’, ‘right’, ‘down’, ‘down’] ‘right’], [‘right’, ‘down’, ‘left’,

‘up’, ‘right’, ‘down’]]

Recall that the Manhattan distance between two locations (r_1, c_1) and (r_2, c_2) on a board is defined to be the sum of the componentwise distances: |r_1 – r_2| + |c_1 – c_2|. The Manhattan distance heuristic for an entire puzzle is then the sum of the Manhattan distances between each tile and its solved location.

&gt;&gt;&gt; b = [[4,1,2], [0,5,3], [7,8,6]] &gt;&gt;&gt; b = [[1,2,3], [4,0,5], [6,7,8]]

&gt;&gt;&gt; p = TilePuzzle(b) &gt;&gt;&gt; p = TilePuzzle(b)

&gt;&gt;&gt; p.find_solution_a_star() &gt;&gt;&gt; p.find_solution_a_star()

[‘up’, ‘right’, ‘right’, ‘down’, ‘down’] [‘right’, ‘down’, ‘left’, ‘left’, ‘up’,

‘right’, ‘down’, ‘right’, ‘up’, ‘left’,

‘left’, ‘down’, ‘right’, ‘right’]

If you implemented the suggested infrastructure described in this section, you can play with an interactive version of the Tile Puzzle using the provided GUI by running the following command:

The arguments rows and cols are positive integers designating the size of the puzzle.

2. Grid Navigation [15 points]

In this section, you will investigate the problem of navigation on a two-dimensional grid with obstacles. The goal is to produce the shortest path between a provided pair of points, taking care to maneuver around the obstacles as needed. Path length is measured in Euclidean distance. Valid directions of movement include up, down, left, right, up-left, up-right, down-left, and down-right.

&gt;&gt;&gt; scene = [[False, False, False], &gt;&gt;&gt; scene = [[False, True, False],

… [False, True , False], … [False, True, False],

… [False, False, False]] … [False, True, False]]

&gt;&gt;&gt; find_path((0, 0), (2, 1), scene) &gt;&gt;&gt; print find_path((0, 0), (0, 2), scene)

Once you have implemented your solution, you can visualize the paths it produces using the provided GUI by running the following command:

The argument scene_path is a path to a scene file storing the layout of the target grid and obstacles. We use the following format for textual scene representation: “.” characters correspond to empty spaces, and “X” characters correspond to obstacles.

3. Linear Disk Movement, Revisited [15 points]

Recall the Linear Disk Movement section from Homework 2. The starting configuration of this puzzle is a row of L cells, with disks located on cells 0 through n – 1. The goal is to move the disks to the end of the row using a constrained set of actions. At each step, a disk can only be moved to an adjacent empty cell, or to an empty cell two spaces away, provided another disk is located on the intervening square.

In a variant of the problem, the disks were distinct rather than identical, and the goal state was amended to stipulate that the final order of the disks should be the reverse of their initial order.

Implement an improved version of the solve_distinct_disks(length, n) function from Homework 2 that uses an A* search rather than an uninformed breadth-first search to find an optimal solution. As before, the exact solution produced is not important so long as it is of minimal length. You should devise a heuristic which is admissible but informative enough to yield significant improvements in performance.

4. Dominoes Game [25 points]

In this section, you will develop an AI for a game in which two players take turns placing 1 x 2 dominoes on a rectangular grid. One player must always place his dominoes vertically, and the other must always place his dominoes horizontally. The last player who successfully places a domino on the board wins.

As with the Tile Puzzle, an infrastructure that is compatible with the provided GUI has been suggested. However, only the search method will be tested, so you are free to choose a different approach if you find it more convenient to do so.

The representation used for this puzzle is a two-dimensional list of Boolean values, where True corresponds to a filled square and False corresponds to an empty square.

1. [0 points] In the DominoesGame class, write an initialization method

2. [0 points] Suggested infrastructure.

In the DominoesGame class, write a method get_board(self) that returns the internal representation of the board stored during initialization.

&gt;&gt;&gt; b = [[False, False], [False, False]] &gt;&gt;&gt; b = [[True, False], [True, False]]

&gt;&gt;&gt; g = DominoesGame(b) &gt;&gt;&gt; g = DominoesGame(b)

&gt;&gt;&gt; g.get_board() &gt;&gt;&gt; g.get_board()

[[False, False], [False, False]] [[True, False], [True, False]]

Write a top-level function create_dominoes_game(rows, cols) that returns a new DominoesGame of the specified dimensions with all squares initialized to the empty state.

&gt;&gt;&gt; g = create_dominoes_game(2, 2) &gt;&gt;&gt; g = create_dominoes_game(2, 3)

&gt;&gt;&gt; g.get_board() &gt;&gt;&gt; g.get_board()

[[False, False], [False, False]] [[False, False, False], [False, False, False]]

In the DominoesGame class, write a method reset(self) which resets all of the internal board’s squares to the empty state.

&gt;&gt;&gt; b = [[False, False], [False, False]] &gt;&gt;&gt; b = [[True, False], [True, False]]

&gt;&gt;&gt; g = DominoesGame(b) &gt;&gt;&gt; g = DominoesGame(b)

&gt;&gt;&gt; g.get_board() &gt;&gt;&gt; g.get_board()

[[False, False], [False, False]] [[True, False], [True, False]]

&gt;&gt;&gt; g.reset() &gt;&gt;&gt; g.reset()

&gt;&gt;&gt; g.get_board() &gt;&gt;&gt; g.get_board()

[[False, False], [False, False]] [[False, False], [False, False]]

If the vertical parameter is True, then the current player intends to place a domino on squares (row, col) and (row + 1, col). If the vertical parameter is False, then the current player intends to place a domino on squares (row, col) and (row, col + 1). This convention will be followed throughout the rest of the section.

&gt;&gt;&gt; b = [[False, False], [False, False]] &gt;&gt;&gt; b = [[True, False], [True, False]]

&gt;&gt;&gt; g = DominoesGame(b) &gt;&gt;&gt; g = DominoesGame(b)

In the DominoesGame class, write a method legal_moves(self, vertical) which yields the legal moves available to the current player as (row, column) tuples. The moves should be generated in row-major order (i.e. iterating through the rows from top to bottom, and within rows from left to right), starting from the top-left corner of the board.

&gt;&gt;&gt; g = create_dominoes_game(3, 3) &gt;&gt;&gt; b = [[True, False], [True, False]]

&gt;&gt;&gt; list(g.legal_moves(True)) &gt;&gt;&gt; g = DominoesGame(b)

[(0, 0), (0, 1), (0, 2), (1, 0), (1, 1), &gt;&gt;&gt; list(g.legal_moves(True))

(1, 2)] [(0, 1)]

&gt;&gt;&gt; list(g.legal_moves(False)) &gt;&gt;&gt; list(g.legal_moves(False))

[(0, 0), (0, 1), (1, 0), (1, 1), (2, 0), [] (2, 1)]

In the DominoesGame class, write a method perform_move(self, row, col, vertical) which fills the squares covered by a domino placed at the given location in the specified orientation.

&gt;&gt;&gt; g = create_dominoes_game(3, 3) &gt;&gt;&gt; g = create_dominoes_game(3, 3)

&gt;&gt;&gt; g.perform_move(0, 1, True) &gt;&gt;&gt; g.perform_move(1, 0, False)

&gt;&gt;&gt; g.get_board() &gt;&gt;&gt; g.get_board()

[[False, True, False], [[False, False, False],

[False, True, False], [True, True, False],

[False, False, False]] [False, False, False]]

In the DominoesGame class, write a method game_over(self, vertical) that returns whether the current player is unable to place any dominoes.

&gt;&gt;&gt; b = [[False, False], [False, False]] &gt;&gt;&gt; b = [[True, False], [True, False]]

&gt;&gt;&gt; g = DominoesGame(b) &gt;&gt;&gt; g = DominoesGame(b)

&gt;&gt;&gt; g.game_over(True) &gt;&gt;&gt; g.game_over(True) False False

&gt;&gt;&gt; g.game_over(False) &gt;&gt;&gt; g.game_over(False)

False True

In the DominoesGame class, write a method copy(self) that returns a new DominoesGame object initialized with a deep copy of the current board. Changes made to the original puzzle should not be reflected in the copy, and vice versa.

&gt;&gt;&gt; g = create_dominoes_game(4, 4) &gt;&gt;&gt; g = create_dominoes_game(4, 4)

&gt;&gt;&gt; g2 = g.copy() &gt;&gt;&gt; g2 = g.copy()

&gt;&gt;&gt; g.get_board() == g2.get_board() &gt;&gt;&gt; g.perform_move(0, 0, True) True &gt;&gt;&gt; g.get_board() == g2.get_board()

False

In the DominoesGame class, write a method successors(self, vertical) that yields all successors of the puzzle for the current player as (move, new-game) tuples, where moves themselves are (row, column) tuples. The second element of each successor should be a new DominoesGame object whose board is the result of applying the corresponding move to the current board. The successors should be generated in the same order in which moves are produced by the legal_moves(self, vertical) method.

&gt;&gt;&gt; b = [[False, False], [False, False]] &gt;&gt;&gt; b = [[True, False], [True, False]]

&gt;&gt;&gt; g = DominoesGame(b) &gt;&gt;&gt; g = DominoesGame(b)

&gt;&gt;&gt; for m, new_g in g.successors(True): &gt;&gt;&gt; for m, new_g in g.successors(True):

… print m, new_g.get_board() … print m, new_g.get_board() … …

(0, 0) [[True, False], [True, False]] (0, 1) [[True, True], [True, True]]

(0, 1) [[False, True], [False, True]]

Optional.

In the DominoesGame class, write a method get_random_move(self, vertical) which returns a random legal move for the current player as a (row, column) tuple. Hint: The random module contains a function random.choice(seq) which returns a random element

from its input sequence.

3. [25 points] In the DominoesGame class, write a method get_best_move(self, vertical, limit) which returns a 3-element tuple containing the

best move for the current player as a (row, column) tuple, its associated value, and the number of leaf nodes visited during the search. Recall that if the vertical parameter is True, then the current player intends to place a domino on squares (row, col) and

(row + 1, col), and if the vertical parameter is False, then the current player intends to place a domino on squares (row, col) and (row, col + 1). Moves should be explored rowmajor order, described in further detail above, to ensure consistency.

Your search should be a faithful implementation of the alpha-beta search given on page 170 of the course textbook, with the restriction that you should look no further than limit moves into the future. To evaluate a board, you should compute the number of moves available to the current player, then subtract the number of moves available to the opponent.

&gt;&gt;&gt; b = [[False] * 3 for i in range(3)] &gt;&gt;&gt; b = [[False] * 3 for i in range(3)]

&gt;&gt;&gt; g = DominoesGame(b) &gt;&gt;&gt; g = DominoesGame(b)

&gt;&gt;&gt; g.get_best_move(True, 1) &gt;&gt;&gt; g.perform_move(0, 1, True) ((0, 1), 2, 6) &gt;&gt;&gt; g.get_best_move(False, 1)

&gt;&gt;&gt; g.get_best_move(True, 2) ((2, 0), -3, 2)

((0, 1), 3, 10) &gt;&gt;&gt; g.get_best_move(False, 2)

((2, 0), -2, 5)

If you implemented the suggested infrastructure described in this section, you can play with an interactive version of the dominoes board game using the provided GUI by running the following command:

The arguments rows and cols are positive integers designating the size of the board.

5. Feedback [5 points]

1. [1 point] Approximately how long did you spend on this assignment?

2. [2 points] Which aspects of this assignment did you find most challenging? Were there any significant stumbling blocks?

3. [2 points] Which aspects of this assignment did you like? Is there anything you would have changed?
