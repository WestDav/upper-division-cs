# Chapter 2: Trees---Heaps---CRUD
Ahh so a Co-Creation can come in the form of any Commit / Push cahnge to the main branch ! 
(McDowell) 
Long-term Roadmap , Flow-charts, 
Arrays, 
Linked Lists, Stacks, Queues, Hash Table Collisions,
The Algorithm Design Manual 
Contiguous arrays, linked lists, stacks, queues, hash maps (dictionaries)
## Data Structures and Algorithm Analysis in Java (Weiss), the red and white book For DSA students doing Java. Sections 
LinkedList implementation, Stack ADT, Queue ADT  
Hashing 

Contiguous Arrays:

Arrays store elements in contiguous memory locations.
Elements are accessed by their indices, and they offer constant-time access to elements (O(1)) if the index is known.
However, inserting or deleting elements from the middle of the array (not at the end) is less efficient because it requires shifting elements, resulting in a time complexity of O(n), where n is the number of elements in the array.

Linked Lists:

Linked lists consist of nodes where each node contains a value and a reference (or pointer) to the next node in the sequence.
They allow for efficient insertion and deletion of elements at any position (assuming you have a reference to the node), typically O(1) time complexity.
However, accessing elements in a linked list requires traversing from the head or tail of the list, resulting in O(n) time complexity for accessing elements at an arbitrary index.

Stacks:

Stacks follow the Last In, First Out (LIFO) principle.
Elements are added or removed from only one end known as the top of the stack.
Operations like push (adding an element) and pop (removing an element) take constant time, O(1).

Queues:

Queues adhere to the First In, First Out (FIFO) principle.
Elements are added to the rear (enqueue) and removed from the front (dequeue) of the queue.
Both enqueue and dequeue operations take constant time, O(1) in typical implementations.

Hash Maps (Dictionaries):

Hash maps use a hash function to map keys to their associated values.
They offer fast insertion, deletion, and lookup operations (on average), typically O(1) time complexity for these operations.
The efficiency depends on the quality of the hash function and the collision resolution strategy used to handle situations where different keys produce the same hash.

