# AVL Tree Implementation in Java
This project implements an AVL tree data structure in Java.

## Functionality Implemented
The AVL tree supports the following operations:
- **empty()**: Check if the tree is empty.
- **search(int k)**: Search for a node with key `k` and return its associated value.
- **insert(int k, String s)**: Insert a node with key `k` and value `s` into the tree.
- **delete(int k)**: Delete the node with key `k` from the tree.
- **min()**: Get the minimum key node's value from the tree.
- **max()**: Get the maximum key node's value from the tree.
- **keysToArray()**: Return a sorted array of all keys in the tree.
- **infoToArray()**: Return an array of values sorted by their corresponding keys.
- **size()**: Get the number of nodes in the tree.
- **split(int x)**: Split the tree into two AVL trees based on key `x`.
- **join(IAVLNode x, AVLtree t)**: Join the current tree with another AVL tree `t` based on a node `x`.
- **getRoot()**: Get the root node of the AVL tree.

## Implementation Details
- The AVL tree is implemented using the `AVLNode` class which implements the `IAVLNode` interface.
- Virtual nodes are used to maintain structure and facilitate rotations.
- Operations are designed to achieve efficient performance with a time complexity typically in `O(log n)`.

## Usage
To use the AVL tree in your Java application, you can instantiate `AVLTree` and use its methods to perform operations like insertion, deletion, searching, and more.
