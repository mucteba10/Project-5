# Project-5
The purpose of this project is to create a symbol table data type whose keys are two-dimensional points. We’ll use a 2dTree
to support efficient range search (find all the points contained in a query rectangle) and k-nearest neighbor search (find k
points that are closest to a query point). 2dTrees have numerous applications, ranging from classifying astronomical objects
to computer animation to speeding up neural networks to mining data to image retrieval.

ArraySt.java: (Array-based Symbol Table) Implement a data type called ArrayST that uses an unordered array as the underlying
data structure to implement the basic symbol table API.

Spell.java: (Spell Checker ) Implement a program called Spell that accepts f ilename (String) as command-line argument,
which is the name of a file containing common misspellings (a line-oriented file with each comma-separated line containing
a misspelled word and the correct spelling); reads text from standard input; and writes to standard output the misspelled
words in the text, the line numbers where they occurred, and their corrections.

BrutePointST.java (Brute-force Implementation) Develop a data type called BrutePointST that implements the above API using a
red-black BST (RedBlackBST) as the underlying data structure.

KdTreePointST.java (2dTree Implementation) Develop a data type called KdTreePointST that uses a 2dTree to implement the above
symbol table API.
