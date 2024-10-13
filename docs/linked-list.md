---
id: linked-list
title: Linked list
sidebar_label: Linked list
---

**A linked list** is a linear data structure where elements, called nodes, are stored in a sequence. Each node contains two parts:

Data: The actual value or information stored in the node.
Pointer (or Reference): A reference or pointer to the next node in the list.

## Types of Linked Lists :

There are several variations of linked lists:

## Singly Linked List:

Structure: Each node contains data and a pointer to the next node.
Characteristics: Traversal is possible only in one direction (from the head to the tail).

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240726165319/Singly-Linked-List.webp"/>



## Doubly Linked List:

Structure: Each node contains three parts—data, a pointer to the next node, and a pointer to the previous node.
Characteristics: Traversal is possible in both directions (forward and backward).

<img src="https://media.geeksforgeeks.org/wp-content/uploads/20240809123741/Insertion-at-the-End-in-Doubly-Linked-List-copy.webp"/>

## Circular Linked List:

Structure: Similar to a singly or doubly linked list, but the last node's next pointer refers to the first node instead of being null.
Characteristics: No null references at the end; it forms a circular chain.
In circular singly linked list: the last node points back to the head.
In circular doubly linked list: both the first node's previous pointer and the last node's next pointer connect, forming a loop.

<img src ="https://encrypted-tbn0.gstatic.com/images?q=tbn:ANd9GcRNLLQU9BmqL-7ME04qoAuQf60_bUBEn0tzdg&s"/>