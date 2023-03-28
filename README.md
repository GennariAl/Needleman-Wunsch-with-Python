# Needleman-Wunsch-with-Python
I developed a script implementing the Needleman_Wunsch algorithm. The file format is .ipynb: for the algorithm there is a code cell with functions definition and a test cell to see the function working. Running the algorithm require the definition of the class typeException, written in the first cell. This class is used to implement unit tests.

Needleman_Wunsch implementation is a function which takes as inputs the match, mismatch, gap cost and the two sequences to align. It returns a list of two elements (strings), collecting the two sequences aligned. It work smoothy with long sequences, I tested the algorithm with two sequences long nearly 700 bp and it took 6.45s 
