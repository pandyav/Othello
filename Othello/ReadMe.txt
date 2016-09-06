ReadME DOC

src:Node.java,OthelloMove.java,OthelloPlayer.java,OthelloRandomplayer.java, OthelloState.java, Test.java,VPPlayer.java,VPPlayerMCTS.java

Test.java contains the main()

All of the required functions and algorithms are in VPPlayer.java and VPPlayerMCTS.java,Node.java

Node class is a game tree node

VPPlayer is a agent using minimax algo
VPPLayerMCTS uses MCTS algo, this class has all of the required functions for MCTS

MCTS and minimax can play as player 1 or 2

For MCTS, more than 1000 iterations really slows down the program(I got descent results with 1000 iterations)
For minimax, more than 6 depth really slows down the program


How to run?
- Run ‘make’ to build (if ‘make’ doesn’t work, do ‘javac *.java’)
- Run ‘java Test’ to run
-choose a number ( 1 for minimax vs random, 2 for MCTS vs ranodm, 3 for MCTS vs Minimax) 
-any other number to exit



