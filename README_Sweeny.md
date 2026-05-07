# OOP_DSA_ASSIGNMENT_1
Part 4: Concept Questions

1) Role of a class in a linked list? 
The class acts as a blueprint. The Node class defines what an individual data point looks like (its value and its pointer), while the LinkedList class acts as the manager that organizes these nodes into a sequence.  


2) Difference between a node and a linked list? 
A node is a single "building block" containing data and a reference to the next item. A linked list is the entire collection or "chain" of these nodes, starting from the very first one (the head).  


3) Why do we use None in next? 
None serves as a "stop sign." It indicates the end of the list, telling the program that there are no more nodes to follow.  


4) How is a linked list different from a Python list? 
Python lists are stored in contiguous memory blocks and allow fast access by index (like list[5]). Linked lists are scattered in memory; to find the fifth element, you must start at the beginning and follow the pointers one by one.  


5)Why is OOP useful for data structures? 
OOP allows us to "encapsulate" data and logic. By bundling the data (nodes) with the actions we perform on them (append, search), the code becomes much more organized, reusable, and easier to debug.
