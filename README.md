# KemenyConsensusExamples
A set of examples of permutations sets and their (optimal) Kemeny Consensus.

There are two files of examples: one that contains 750 sets of (m = 3-15) small and medium permutations (n = 10-90) and one that contains 1700 sets of (m = 3-9) big permutations (n = 80-110). 

Each instance is encoded as follows:

m = (the number of permutations)
n = (the size of permutations)
R = (the set of permutatioins)
Consensus = (a consensus permutation)
KemenyScore = (the Kemeny Score of that permutation)
Time = (the time it took to solve that instance with ILP)

An example:

m = 7
n = 10
R = {[5, 8, 4, 1, 6, 3, 2, 9, 7, 10],
[2, 10, 9, 1, 7, 5, 4, 6, 3, 8],
[1, 4, 8, 2, 5, 9, 7, 6, 3, 10],
[8, 3, 1, 10, 9, 5, 6, 7, 4, 2],
[3, 9, 10, 1, 5, 6, 4, 2, 8, 7],
[5, 4, 9, 2, 10, 3, 8, 1, 7, 6],
[7, 5, 10, 1, 3, 4, 9, 6, 8, 2]}
Consensus = [1, 5, 4, 3, 9, 2, 10, 8, 7, 6]
KemenyScore = 112.0
Time = 0.0337021350861 sec
