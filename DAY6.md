# DAY6
### DIfference Between def and cdef:
<ins>In Cython, def functions can be called from Python and Cython while cdef functions can be called from Cython and C.
The key difference between them is where the function can be called fromcdef functions are quicker to call than def functions because they translate
to a simple C function call. cdef functions can take any type of argument, including those that have no Python equivalent (for example pointers)def
functions cannot have these since they must be callable from Python. cdef functions can also specify a return type (if it is not specified then they return 
a Python object, PyObject* in C)def functions always return a Python object, so cannot specify a return type cpdef functions cause Cython to generate a cdef 
function (that allows a quick function call from Cython) and a def function (which allows you to call it from Python)</ins>
##
### How DFS And BFS Works?
DFS and BFS are two algorithms for traversing or searching a graph. They differ in the order in which they visit the nodes of the graph.
DFS stands for Depth-First Search and BFS stands for Breadth-First Search.

DFS visits the nodes by going deeper into the graph as much as possible before backtracking. It uses a stack data structure to keep track of the nodes t
o visit. DFS is more suitable for finding a path that is far from the root node or exploring the whole graph.

BFS visits the nodes by going level by level, starting from the root node. It uses a que
ue data structure to keep track of the nodes to visit. BFS is more suitable for finding a path that is close to the root
node or finding the shortest path in an unweighted graph.

Here is an example of how DFS and BFS would traverse a binary tree:

The order of traversal for DFS would be: A, B, D, E, C, F, G.

The order of traversal for BFS would be: A, B, C, D, E, F, G.
##

