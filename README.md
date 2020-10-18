# AVL Tree Implementation
Implementing an balanced AVL tree in Java

## Purpose
Learning the properties of an AVL tree and learn how to maintain such properties after insertions/deletions. Used as lab work for a data structures and algoithms course.

## Content Path
https://github.com/quinnwai/shortest-path-impl/tree/master/labs/spath/ShortestPaths.java

## Overview
The most important functions are `updateHeight`, `getBalance`, `rebalance`, and `rightRotate`. Here is more about each function:
 - `updateHeight(TreeNode<T> root)`: Recalculates and updates the height of the tree using the subtrees at the left and right children.
 - `getBalance(TreeNode<T> root)`: Returns the balance factor: the difference between heights of each subtree rooted at the left and right children.
 - `rebalance(TreeNode<T> root)`: returns the root of the tree after everything is balanced, i.e. when the balance factor is between -1, 0, or 1.
 - `rightRotate(TreeNode<T> root)`: Changes the tree. The right child of `root` becomes the new root, `root` becomes the left child, and the left subtree on the right child becomes the right subtree of `root`.
