Binary Search Trees
Binary Search Trees possess all the properties of Binary Trees including some extra properties of their own, based on some constraints, making them more efficient than binary trees.

The data in the Binary Search Trees (BST) is always stored in such a way that the values in the left subtree are always less than the values in the root node and the values in the right subtree are always greater than the values in the root node, i.e. left subtree < root node ≤ right subtree.

binary serach tree
Advantages of BST

Binary Search Trees are more efficient than Binary Trees since time complexity for performing various operations reduces.

Since the order of keys is based on just the parent node, searching operation becomes simpler.

The alignment of BST also favors Range Queries, which are executed to find values existing between two keys. This helps in the Database Management System.

Disadvantages of BST

The main disadvantage of Binary Search Trees is that if all elements in nodes are either greater than or lesser than the root node, the tree becomes skewed. Simply put, the tree becomes slanted to one side completely.

This skewness will make the tree a linked list rather than a BST, since the worst case time complexity for searching operation becomes O(n).

To overcome this issue of skewness in the Binary Search Trees, the concept of Balanced Binary Search Trees was introduced.

Balanced Binary Search Trees
Consider a Binary Search Tree with ‘m’ as the height of the left subtree and ‘n’ as the height of the right subtree. If the value of (m-n) is equal to 0,1 or -1, the tree is said to be a Balanced Binary Search Tree.

The trees are designed in a way that they self-balance once the height difference exceeds 1. Binary Search Trees use rotations as self-balancing algorithms. There are four different types of rotations: Left Left, Right Right, Left Right, Right Left.

There are various types of self-balancing binary search trees −

AVL Trees

Red Black Trees

B Trees

B+ Trees

Splay Trees

Priority Search Trees
