List of edge cases to check before submit a task solution:

### Vocabulary:

1. DS – data structure;
2. DP – dynamic programming;

### Check lists

#### Before writing code:

1. Check input data restrictions – which DS should you use?

#### Before submit code:

1. General:
   1. Slices – check start and end indexes. End idx is not included, and maybe you need and `end + 1` (`slice(start, end + 1)`)?
   2. Do you start from correct idx in loop?
   3. Do functions expect for correct arguments?
2. DFS / BFS
   1. Is current task required undo cached nodes of the DS (e.g. [Word search](https://leetcode.com/problems/word-search/) on m x n grid required)?
3. Cache structure:
   1. Is cache structure has correct size? Maybe cache has to have +1 element (dp)?
   2. If it's a 2D array (matrix):
      1. Does its rows and columns have correct sizes?
      2. Does cache rows and columns equal (size) to main DS rows and column?
4. Optimizations
   1. Map / Set
      1. Does it require to store number of entries of the elements? If yes – use Map, if not use Set;
