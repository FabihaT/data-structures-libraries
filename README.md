# ENSF338_Project
## Project Overview 
The project involves creating a library for common data structures in Java. This library implements various data structures from scratch, ensuring they are efficient, reliable, and ready to integrate into larger applications. The library is organized into subfolders for each data structure, such as linear data structures and tree structures using nodes.

## Linear Data Structures:
Linked Lists: Implement various forms of linked lists (singly, doubly, circular singly, circular doubly) allowing for sequential traversal and modification of elements.
Stack: A LIFO (last in, first out) data structure with primary operations of push and pop, implemented via a linked list.
Queue: A FIFO (first in, first out) data structure, implemented via a linked list, supporting enqueue and dequeue operations.

## Tree Structures:
Binary Search Trees (BST): A tree data structure that maintains ordered data for quick search, insertion, and deletion.
AVL Trees: A self-balancing binary search tree where the difference in heights of subtrees of any node is less than or equal to one.

To run the App.  
To compile: javac -d target/classes src/main/java/mylib/*.java src/main/java/mylib/datastructures/linear/*.java src/main/java/mylib/datastructures/nodes/*.java src/main/java/mylib/datastructures/trees/*.java  
To run: java -cp target/classes mylib.App
