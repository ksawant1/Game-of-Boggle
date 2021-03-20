# Game-of-Boggle
Boggle is one of the most popular word search games and is played on a N x N board made of cubes with letters printed on it.
We provide a manual dictionary and try to construct words on the board following these rules:
i. Can move from one letter to another if it is a neighbour (horizontally, vertically, or diagonally.).
ii. A word must be 3 or more letters long to be valid

In this problem, we are constructing a game of boggle by applying three search strategies binary search, brute force and trie
Our main aim is to find out which search strategy will be most efficient and fast in finding the word. We will compare our search strategies with one another based on number of inputs, time to search the string and performance


## Results
Time Complexity
The Boggle Solver can be considered as a type of NP problem so it cannot be solved in polynomial time. Although, our search techniques help improve time after comparison of words with the dictionary. We considere an example and observed the following;


Comparison
### Time complexity	(Comparison in the dictionary) 				
 * Boggle Traversal - O(n*n)	 
 * Brute Force	 -  O(n)	
 * Binary Search	 - O(logn)
 * Trie  - Building the tree O(W*L)
          where W=number or words
          L max length of word in a dictionary
          Searching depends on prefix of word length

#### Run Time
 * Brute Force	 - 19025841 ms	
 * Binary Search	 - 4852293 ms	
 * Trie  -  5874 ms	

#### Space Complexity for all Structures - n^2

