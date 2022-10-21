•	Linked lists
A linked list is a collection of nodes. The first node is called the head , and it's used as the starting point for any iteration through the list. The last node must have its next reference pointing to None to determine the end of the list.
Each element of a linked list is called a node, and every node has two different fields:
1.	Data contains the value to be stored in the node.
2.	Next contains a reference to the next node on the list.
>>> graph = {
...     1: [2, 3, None],
...     2: [4, None],
...     3: [None],
...     4: [5, 6, None],
...     5: [6, None],
...     6: [None]
... }
https://realpython.com/linked-lists-python/#:~:text=A%20linked%20list%20is%20a,the%20end%20of%20the%20list.
