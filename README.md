# AI engine for the game Gomoku, played on a n × n board. There are two players. One player plays with black stones and the other player plays with white stones. A player moves by placing a stone on an empty square on the board. The player who plays with black stones always moves first. After the first move, the players alternate. A player wins if she has placed five of her stones in a sequence, either horizontally, or vertically, or diagonally. 

# The computer determines its move by finding the move that maximises the return value of the score function. The score function returns a value between 0 and 100000 depending on the state of the board, namely the number of sequences of the computer's stone color that it contains, and also the type of sequence. The AI tries every possible move it can attempt on the board, calculates the score, and finally makes its actual move with the move that has the highest score. 

# There are four possible directions for a sequence: left-to-right, top-to-bottom, upper-left-to-lower-right, and upper-right-to-lower-left. 

# A sequence can be: (open: a stone can be put on a square at either side of the sequence), (closed: the sequence is blocked on both sides, so that no stone can be placed on either side of the sequence. This can occur either because the sequence begins/ends near the border of the board, or because there is a stone of a different colour in the location immediately next to the beginning/end of the sequence), (semi-open: the sequence is neither open or closed).
   
           
