# Structure-of-Fibonacci-Heap
The Fibonacci heap is a powerful data structure that allows for efficient implementation of priority queues. It has better amortized time complexity than other commonly used priority queue data structures like the binary heap or the binomial heap. It achieves this by using lazy merging and degree-bounded trees. The Fibonacci heap has a variety of useful operations, such as insert, find-min, extract-min, decrease-key, and delete. It also has some interesting properties, such as the potential function and the Fibonacci sequence property. However, the Fibonacci heap can be difficult to implement and may not be as space-efficient as other data structures. Overall, the Fibonacci heap is an important tool in computer science and is worth studying for anyone interested in algorithms and data structures.

The Fibonacci Heap is a collection of rooted trees, which are called Fibonacci Trees, each of which satisfies the heap property. The unique structure of the heap allows for efficient implementations of the key operations, which provide time complexities that are better than other popular data structures such as binary heaps and binomial heaps.
 1. Insert
This operation inserts a new element into the heap. It is done by creating a new node with the given key value and inserting it into the root list. This operation takes O(1) time complexity.
Inserting a node into an already existing heap follows the steps below.
Create a new node for the element.
Check if the heap is empty.
If the heap is empty, set the new node as a root node and mark it min.
Else, insert the node into the root list and update min  

2. Merge

This operation merges two Fibonacci heaps into a single one. It is done by concatenating the root lists of the two heaps and updating the minimum element accordingly. This operation takes O(1) time complexity.

 Merge of two fibonacci heaps consists of following steps.

Concatenate the roots of both the heaps.
Update min by selecting a minimum key from the new root lists.

3. Find-min

The minimum element is always given by the min pointer.

4. Extract-min
This operation returns the minimum element in the heap. It is done by accessing the minimum element's value in O(1) time complexity.


