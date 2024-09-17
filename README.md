# Avl-IN-C
 i was board at the train
# AVL Tree Implementation in C

## Overview

This project is an implementation of an AVL Tree in C, providing a detailed exploration of the AVL (Adelson-Velsky and Landis) tree data structure. AVL trees are self-balancing binary search trees where the difference between heights of left and right subtrees cannot be more than one for all nodes.

## Features

- **Dynamic Tree Structure**: Automatically maintains balance during insertions and deletions.
- **Insertion and Deletion**: Supports insertion and deletion operations while maintaining the balance of the tree.
- **Tree Visualization**: Provides a utility to visualize the tree structure in a 2D view, making it easier to understand the tree layout.
- **Interactive Menu**: Allows users to interactively add nodes, print the tree, or exit the program.

## Compilation and Execution

### Requirements

- GCC compiler
- Standard C library

### Compiling the Program

To compile the program, navigate to the directory containing `avl_tree.c` and use the following GCC command:

```bash
gcc -o avl_tree avl_tree.c
Running the Program
After compilation, run the program using:

bash
Copy code
./avl_tree
Follow the on-screen prompts to interact with the AVL tree. You can add nodes, view the tree, or exit the program.

Implementation Details
Node Structure: Each node contains integers for value and height, pointers to left, right children, and parent, and a flag indicating if it is the root.
Balance Factor: Each node's balance factor is calculated to decide rotations during insertion and deletions to maintain tree balance.
Rotations: Implements left, right, left-right, and right-left rotations to keep the tree balanced.
Functions
createRoot(): Initializes the root of the AVL tree.
addNode(): Adds a new node and rebalances the tree as necessary.
print2D(): Visualizes the tree in a 2D format.
isBalanced(): Checks if the tree is balanced.
fixAvl(): Fixes the AVL property after insertion or deletion.
freeTree(): Frees memory allocated for the tree upon exiting the program.
Example Usage
The program is designed to be interactive. Here is an example of how you might interact with it:

Start the program.
Choose to add nodes.
Input values for the nodes.
Choose to print the tree to see its structure.
Exit the program.
Contributing
Contributions to the project are welcome. If you have improvements or bug fixes, please fork the repository, make your changes, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

Contact
For more information or queries regarding this implementation, please reach out to [RanWurembrand@gmail.com].
