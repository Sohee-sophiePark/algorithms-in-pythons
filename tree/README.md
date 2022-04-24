# Tree

## Tree Condition
- Cannot be cyclic
- N Nodes / N-1 Edges


## Real-life Use Cases
- File System
- Social Hierarchy
- Source Code Decomposition
- Mathematical Expression
- Webpage - HTML Dom Structure
- Decision Making

## How to store undirected tree
- edge list
- adjacency list
- adjacency matrix (hugh space required)

## Types
- Rooted Tree - designated root
- Binary Tree - each node has at most two child nodes
- Binary Search Tree - left subtree always has less or equal values of root value / - right subtree always has more or equal values of root value

### Rooted Tree
- Defined in Recursive Top-down manner
- Root reference Pointer
- Each node can access child - can be bidirectional
- can be implemented in flattened array

### Flattened Array for Tree
- left node index = current node index * 2 + 1
- right node index = current node index * 2 + 2


